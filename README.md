# UserManagementAPI

This is a simple ASP.NET Core Web API project to manage users, built with Microsoft Copilot assistance.

## Features

- CRUD operations for users (GET, POST, PUT, DELETE)
- Validation on user data (Name and Email)
- Middleware for:
  - Global error handling with JSON responses
  - Token-based authentication (simple token check)
  - Logging HTTP requests and responses

## How to Run

1. Clone the repo
2. Open the solution in Visual Studio or VS Code
3. Run the project (`dotnet run` or F5 in VS)
4. Test API endpoints with Postman or curl

## Authentication

- Add header `Authorization: Bearer valid-token` to access protected endpoints.

## Notes

- User storage is in-memory for demo purposes.
- Replace token validation logic with your real auth system.
