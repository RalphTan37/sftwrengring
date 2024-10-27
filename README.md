# Hotel Booking System Application

Developing a Hotel Booking System Application in C++. Urban Oasis Hotel!

## Running the Program:

Compile the Program:
```
g++ -o main main.cpp
```

Run the Executeable:
```
./main.exe
```

## Running SQL Files on VS Code:

1. Install SQL Server (mssql) as an extension & Microsoft SQL Server Management Studio
```
https://learn.microsoft.com/en-us/sql/ssms/download-sql-server-management-studio-ssms?view=sql-server-ver16
```
2. Open the command palette (Crtl+Shift+P)
3. Make the language is set to SQL
4. Select MS SQL: Add Connection

## System Requirements:
Compatible with Windows, macOS, and Linux.
g++ (GNU C++ Compiler) version 5.0 or higher

## Library Requirements:
- Open Source Libraries: Qt

## High-Level Design Overview:
This section provides a high-level design of the Hotel Booking System Application, including key components and architecture.

### Main Components:
1. User Interface (GUI):
   - Handles user interactions for booking, checking availability, and managing reservations.
2. Database:
   - Stores login credentials, hotel rooms
3. Core Classes :
   - Booking: Manages booking details, including check-in and check-out dates, customer information, and room selection.
   - Room: Represents room details, such as type, availability, and pricing.
   - UserAccount: Handles user authentication and profiles.
  
### Architecture Overview:
The application follows a modular architecture, separating concerns between the user interface, business logic, and data management. This design ensures maintainability and scalability as new features can be added with minimal impact on existing code.

   ![Screenshot 2024-10-08 153142](https://github.com/user-attachments/assets/fd4d9177-b32f-4dd6-a6f1-6234c9c97e3d)

![Screenshot 2024-10-08 154019](https://github.com/user-attachments/assets/6e628204-d9b6-4c39-b50c-2b87abc4b761)

![Screenshot 2024-10-08 154859](https://github.com/user-attachments/assets/a7d6a149-ce5a-4eee-ab6f-b25849e1940f)
