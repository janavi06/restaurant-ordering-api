Restaurant Ordering API

A .NET backend for a QR-based restaurant ordering and POS platform, supporting digital menus, order processing, and restaurant operations.

Built for a real-world restaurant workflow, with customer ordering and dedicated interfaces for restaurant staff.

Frontend: [Restaurant Ordering Frontend](https://github.com/janavi06/restaurant-ordering-frontend)

 Features

- Menu Management: Manage restaurant menu data and products.
- Order Processing: Handle order creation and order status updates.
- Restaurant Operations: Support kitchen, waiter, and manager workflows.
- Inventory Management:  Backend functionality for restaurant stock operations, where implemented.
- Reporting: Support management reporting and operational insights, where implemented.
- Data Persistence:   Manage application data using Entity Framework Core.

Tech Stack

- Backend: C#, ASP.NET Core Web API
- ORM: Entity Framework Core 8
- Database: Confirm the database provider configured in the project
- API: REST, JSON

Architecture

The backend uses ASP.NET Core Web API for HTTP endpoints and Entity Framework Core for database access. API controllers handle incoming requests, while service-layer components organize business logic.

 Project Structure

Menu/
├── Controllers/
├── Services/
├── Interface/
├── Implementation/
├── Models/
├── DTOs/
├── Data/
└── Migrations/


 Getting Started

Prerequisites: Compatible .NET SDK and the configured database.

git clone https://github.com/janavi06/restaurant-ordering-api.git
cd restaurant-ordering-api
dotnet restore
dotnet build

Open Menu/ and run the API project using its configured launch settings. Configure the required database connection and application secrets locally before starting the application.

 Author
 
Janavi Korgaonkar
