Mobile Shop Management System (C#)
Overview
This is a C# Windows Forms application for managing a mobile shop. The system allows users to manage mobiles, accessories, customers, and bills efficiently. It includes login authentication,
data management, and bill generation features. The database is normalized up to Second Normal Form (2NF) to reduce redundancy and maintain data integrity.

Features

*** Login Page

User authentication using UserID and Password.

User roles supported with UserType.

*** Homepage

Navigation to:

Mobiles

Accessories

Customer Info

Bills

**** Mobiles Page

Manage mobile products:

Fields: MobileID, Brand, Model, RAM_GB, ROM_GB, Camera_MP, Price, Stock

Operations: Add, Update, Delete, Clear, Back

Data displayed in a DataGridView.

***** Accessories Page

Manage accessory products:

Fields: AccessoryID, Brand, Model, Price, Stock

Operations: Add, Update, Delete, Clear, Back

Data displayed in a DataGridView.

**** Bills Page

Generate bills for mobiles and accessories:

Input: BillID, ProductID, ProductName, Price, Quantity

Operations: Create, Print, Back

Prints detailed bill with total price calculation.

**** Database Normalization

The database is normalized up to 2NF for data integrity and efficiency:



**** Language: C#

**** Framework: Windows Forms (WinForms)

**** Database: SQL Server (LocalDB)

**** UI Components: DataGridView, Buttons, TextBoxes


**** Usage

Launch the application and log in using your UserID and Password.

Navigate through Homepage to manage Mobiles, Accessories, or Bills.

Add, update, or delete products as needed.

Generate bills for customers and print them if required.

Contributing

Contributions are welcome! You can:

Add new features (e.g., reporting, analytics)

Improve UI/UX

Optimize database queries

**** License

This project is open-source and free to use.
