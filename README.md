# Chinook Music Store

A web application built with **ASP.NET Core MVC** that acts as a customer portal for the sample Chinook digital music store database. The application enables authenticated users to view their order history and detailed invoice information.

## Tech Stack
- **Framework:** ASP.NET Core MVC (.NET)
- **Database / ORM:** Entity Framework Core with SQLite (`chinook.db`)
- **Authentication:** ASP.NET Core Identity
- **Frontend:** Razor Views (HTML/C#), Bootstrap

## Key Features
- **User Authentication:** Secure login and account management integrated with ASP.NET Core Identity.
- **Customer Association:** User accounts are linked directly to `CustomerId` records in the Chinook database.
- **Order History (`MyOrders`):** Displays a list of all invoices belonging to the logged-in customer, including dates, billing addresses, and total costs.
- **Invoice Details (`OrderDetails`):** Detailed breakdown of specific orders, showing purchased music tracks, track IDs, and individual prices.

## How to Run the Project

1. Make sure you have the [.NET SDK](https://dotnet.microsoft.com/download) installed.
2. Open a terminal in the root directory of the project.
3. Restore dependencies and run the application:
   ```bash
   dotnet run
