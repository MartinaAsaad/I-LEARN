Due to GitHub's file size limitations, the entire project, including any large assets and additional files, has been uploaded as a `.rar` file on Google Drive.

## Download the Project

You can download the entire project as a `.rar` file from the following link:

[Download Project Files from Google Drive](https://drive.google.com/file/d/1Ffvlx_A_D77MFA_lj08f1kLPADWIAwja/view?usp=drive_link)

## **Description**

**I-LEARN** is an ASP.NET MVC web application designed to  to manage courses, handle user authentication, and facilitate interaction between trainees and instructors. It allows for seamless course registration, tracking progress, and managing roles within an educational setting, creating an efficient platform for learning and teaching. This application demonstrates key features of state management, user roles, and database operations in a modern web application. It includes CRUD operations, authentication, and role-based authorization using ASP.NET Identity.

The project utilizes:
- ASP.NET Core MVC for the backend
- Entity Framework Core for database management and migrations
- Bootstrap for responsive design and layout
- Client-side state management with cookies, session, and local storage

### **Features**
- **User Authentication and Authorization**: Implements user registration, login, and role-based access control (Admin, Instructor, Trainee).
- **CRUD Operations**: Manage courses, departments, and users through the admin interface.
- **State Management**: Uses TempData, ViewData, and session to handle data across requests.
- **Responsive UI**: Bootstrap is used for a mobile-first, responsive design.
- **Database Migrations**: Includes Entity Framework Core migrations to update the database schema.

### **Technologies Used**
- **ASP.NET Core MVC**
- **Entity Framework Core** (Code-First)
- **SQL Server** (or SQLite, depending on setup)
- **Bootstrap**
- **jQuery / JavaScript** for dynamic user interactions

### **Installation and Setup Instructions**
1. Download the `.rar` file from the link above then extract it.
2. Open the project in **Visual Studio**.
3. Set up the database:
   - Ensure you have a local SQL Server instance running or modify the connection string in `appsettings.json`.
   - Run the following command in the **Package Manager Console** to apply migrations:
     ```bash
     Update-Database
     ```
4. Run the application:
   - Press `F5` in Visual Studio to build and run the application.

