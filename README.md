# 🏨 **Buff Hotel Management System** 💻

Simplify hotel management with the **Buff Hotel Management System**—a robust, terminal-based application built with **C# .NET** ⚙️ and **MySQL** 💾. Designed to streamline operations, it handles reservations, room statuses, and user authentication effortlessly. 🎯

---

## 🛠️ **Key Features**

- 🏡 **Dynamic Room Management**: Real-time updates on room availability and status.
- 🔒 **Secure Authentication**: Keep data safe with authorized access only.
- 📆 **Reservation Tracking**: Manage active, completed, and all reservations seamlessly.
- ⚡ **Efficient Check-In/Out**: Process guest actions quickly and update room statuses dynamically.
- 🪹 **Error Handling**: Clear feedback for invalid inputs and system issues.
- 🔄 **Extensibility**: Modular design for easy future enhancements.

---

## 🚀 **Getting Started**

### 1 **Set Up Credentials**
Use the following to log in:
- **Username**: `alice`
- **Password**: `alice123`

### 2 **Run the Application**

1. Clone the repository and navigate to the project folder:
   ```bash
   git clone https://github.com/YourRepo/BuffHotelManagementSystem.git
   cd BuffHotelManagementSystem
   ```

2. Configure your database credentials in the `.env` file.

3. Build and launch the application:
   ```bash
   dotnet build
   dotnet run
   ```

---

## 📜 **Menu Options**

- 🛏️ **Show Available Rooms**: View all unoccupied rooms.
- 🔑 **Check-In**: Assign customers to suitable rooms based on capacity.
- 📋 **Show Active Reservations**: Display all ongoing bookings.
- 🚪 **Check-Out**: Mark rooms as available upon guest departure.
- 📂 **Show All Rooms**: Categorize rooms by status (available, reserved, etc.).
- 🗂️ **Show Completed Reservations**: Review past guest stays.
- 📜 **Show All Reservations**: Access a full log of both active and completed reservations.
- 🔓 **Log Out**: Exit securely.

---

## 🏗️ **Behind the Scenes**

### 🔍 **Core Components**

- **DBConnect**: Manages secure database connectivity, loads `.env` configurations, and provides helper methods like `EnsureConnection` and `CloseConnection`.
- **Service**: Contains methods for database interactions, such as retrieving rooms and reservations, and handling check-in/check-out processes.
- **HotelController**: Handles user interaction with the system, including the main menu, and coordinates with other components.
- **MethodHelper**: Provides utility methods for user input validation and filtering data.

---

## 💡 **Troubleshooting**

### ⚙️ **Common Issues**

1. **Database Connectivity**: Ensure `.env` credentials and SQL procedures are correct.
2. **Login Errors**: Verify the username and password.
3. **Debugging**: Use breakpoints in key files like `Program.cs`, `Controllers.cs`, `Service.cs`, and `MethodHelper.cs`.


---

## 📂 **Project Structure**

```plaintext
/BuffHotelManagementSystem
│
├── 📂 CodeFilesSQL        # SQL scripts for database setup
├── 📂 Controllers         # Business logic and operations (e.g., HotelController.cs)
├── 📂 Models              # Data models (e.g., Room.cs, Reservation.cs)
├── 📂 Services            # Service methods for database interactions
├── 📂 Utilities           # Helper methods (e.g., MethodHelper.cs)
├── 📄 BuffHotel.csproj    # Project file
├── 📄 BuffHotel.sln       # Solution file
├── 📄 DBConnect.cs        # Database connection management
├── 📄 Program.cs          # Entry point for the application
└── 📄 README.md           # 📜 Documentation
```

---

## 📞 **Contact**

For support, feedback, or inquiries, reach out to:  
**Jesus Torres** ✉️
