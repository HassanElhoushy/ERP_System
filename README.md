# Enterprise Resource Planning (ERP) System – DEPI Graduation Project

## Overview
This project is a **comprehensive Enterprise Resource Planning (ERP) System** developed as part of the **Digital Egypt Pioneers Initiative (DEPI)**.  
The system provides a unified platform to manage core business lifecycles, including procurement, inventory control, and financial accounting.

## Features
- Smart inventory management across multiple warehouses  
- Complete Sales and Purchase cycles with support for **Cash** and **Credit** transactions  
- Accounting modules including **Chart of Accounts** and **Journal Entries**  
- Dynamic reports with data visualization and **Excel export**  
- Employee, supplier, and customer management  
- Responsive UI with and full **RTL (Arabic) support**

## Tech Stack
- **Backend:** ASP.NET Core MVC (.NET 8), Entity Framework Core  
- **Frontend:** Razor Views, Bootstrap, JavaScript  
- **Database:** SQL Server  
- **Architecture:** Clean Architecture (Separation of Concerns)  
- **Tools:** Git, GitHub, Visual Studio  

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/HassanElhoushy/ERP_System_DEPI.git
Update the database connection string in appsettings.json.

Apply migrations to your local SQL Server:

bash
Copy code
dotnet ef database update
Run the application using Visual Studio or the .NET CLI.
