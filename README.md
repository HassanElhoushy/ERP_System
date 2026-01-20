Enterprise Resource Planning (ERP) System – DEPI Graduation Project
Overview
This project is a comprehensive Enterprise Resource Planning (ERP) System developed as the final graduation project for the Digital Egypt Pioneers Initiative (DEPI). The system is designed to provide a unified digital ecosystem for businesses, automating core operations such as inventory tracking, financial accounting, and performance analytics to ensure data-driven decision-making.

Features
Inventory & Multi-Warehouse Management: Real-time tracking of quantities, stock movements across different locations, and product categorization.

Financial & Accounting Suite: Full management of Sales and Purchase cycles (Cash/Credit), including a Chart of Accounts and Journal entries.

Dynamic Reporting & Analytics: Interactive dashboards for monthly sales/purchase trends with the ability to export data to Excel or print reports.

User Management: Role-based access control for employees, along with dedicated modules for suppliers and customers.

Modern UI/UX: Fully responsive interface featuring professional Dark/Light modes and complete RTL (Arabic) support.

Supply Chain Integration: Comprehensive management of manufacturers, brands, and measurement units.

Tech Stack
Backend: ASP.NET Core MVC (.NET 8), Entity Framework Core.

Frontend: Razor Views, Bootstrap, JavaScript (Support for Dark Mode and RTL).

Database: SQL Server.

Architecture: Clean Architecture (Onion Architecture) for better maintainability and scalability.

Tools: Git, GitHub, Visual Studio 2022.

Installation
Clone the repository:

Bash
git clone https://github.com/HassanElhoushy/ERP_System_DEPI.git
Configure the Database:

Open appsettings.json.

Update the DefaultConnection string with your local SQL Server credentials.

Apply Migrations:

Open the Package Manager Console in Visual Studio.

Run the command: Update-Database.

Run the application:

Press F5 or click Start in Visual Studio to launch the system.
