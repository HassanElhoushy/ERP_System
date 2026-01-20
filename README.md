Enterprise Resource Planning (ERP) System - DEPI Graduation Project
A high-performance, enterprise-grade ERP solution engineered to automate and unify core business operations into a single, scalable digital ecosystem. Developed as a graduation project for the Digital Egypt Pioneers Initiative (DEPI).

🚀 Overview
This system transforms manual business operations into a data-driven environment, managing everything from procurement and inventory to complex financial reporting. It features a modern, responsive UI with full Dark Mode and RTL (Arabic) support.

🛠 Tech Stack
Framework: ASP.NET Core MVC (.NET 8).

Architecture: Clean Architecture (Onion Architecture) for strict Separation of Concerns.

Database: SQL Server with Entity Framework Core.

Data Logic: Advanced LINQ queries and database constraints for high data integrity.

UI: Responsive design with support for Light/Dark modes and RTL localization.

✨ Key Features
📦 Inventory & Warehouse Management
Core Focus: Engineered robust tracking for real-time quantity monitoring and stock movements.

Multi-Warehouse Support: Manage stock across various locations with detailed transfer logs.

Categorization: Comprehensive management of products, units (Piece, Box, etc.), and manufacturing brands.

💰 Financial & Accounting Suite
Full Cycles: Integrated Sales and Purchase cycles supporting both Cash and Credit transactions.

Accounting Tools: Includes a Chart of Accounts, Journal Entries, and dedicated tracking for Revenues and Expenses.

Returns Management: Streamlined process for handling sales and purchase returns.

📊 Advanced Analytics & Reporting
Dynamic Dashboards: Interactive charts for monthly purchase/sales analysis and supplier performance.

Data Portability: Built-in functionality for Excel Export and professional printing of reports.

👥 Human Capital & Supply Chain
User Management: Centralized database for Employees, Suppliers, and Customers.

Role-Based Access: System security managed through defined user roles and permissions.

🏗 Architecture
The project follows Clean Architecture to ensure the code remains maintainable and testable:

Domain: Core entities and business logic.

Application: Interfaces, DTOs, and service logic.

Infrastructure: Database context and external service implementations.

Web UI: The presentation layer using ASP.NET Core MVC.

📸 Screenshots
(Add your screenshots here) | Dashboard | Inventory Management | | :--- | :--- | | | |

⚙️ Getting Started
Clone the repository:

Bash
git clone https://github.com/YourUsername/ERP-System.git
Update Connection String: Modify the appsettings.json file in the Web project with your SQL Server credentials.

Apply Migrations:

Bash
dotnet ef database update
Run the Project:

Bash
dotnet run
👨‍💻 Author
Hassan Elhoushy

Computer Science Student at Tanta University

Specialized in .NET Development and Problem Solving
