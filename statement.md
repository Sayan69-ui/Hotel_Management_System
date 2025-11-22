Project Statement: Hotel Management System

1. Problem Statement
   -
Small hospitality operators often use manual or disparate systems, causing errors in room status and hindering basic revenue calculation. This project addresses the need for a lightweight, simple, and reliable digital system to centralize core front-desk operations (Rooms, Guests, Bookings) and provide accurate status and financial oversight, replacing error-prone manual methods.

2. Scope of the Project
   -
The project is a single-file, desktop-based GUI application implemented using Python/Streamlit and SQLite for persistent storage.

The system modules include:

Room Management: Full CRUD operations for room entities, price setting, and status tracking.

Guest Management: Creation and viewing of basic guest profiles.

Booking Management: Creating, viewing, and deleting reservations (check-out), with automated room status updates.

Basic Reporting: Calculation and display of total revenue from active bookings.

Exclusions: The scope excludes multi-user support, detailed user authentication, complex financial reporting (e.g., invoices), advanced search/filters, or third-party integrations (SMS/Email).

3. Target Users
   -

Primary users include:

Hotels, Lodges, Homestays, and PGs: Hospitality businesses needing an efficient, internal system.

Front Desk/Reception Staff: Key operators processing daily check-in, check-out, and room allocation.

Small Hospitality Operators: Owners requiring a simple, offline management tool.

4. High-level Features
   -
The system offers three functional modules plus reporting:

Room Management (CRUD): Registers rooms, defines price/type, and tracks occupancy status in real-time.

Guest Management (Create/Read): Quickly adds guest profiles (Name, Contact, Email) for booking.

Booking Management (CRUD): Creates reservations, linking guests to available rooms, calculating total amount, and automatically handles room status upon check-out.

Revenue Reporting: Displays the total revenue sum from all active bookings.


