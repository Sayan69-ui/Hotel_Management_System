#Hotel Management System
-
Overview
This project is a lightweight, single-file Hotel Management System built using Python and Streamlit. It provides a simple graphical user interface (GUI) for front desk operations, including managing rooms, guests, bookings, and generating basic reports. The application uses SQLite as its backend database for persistent storage.
It satisfies the requirement for a project with multiple functional modules (Room Management, Guest Management, and Booking Management) and demonstrates CRUD (Create, Read, Update, Delete) operations.
Features
This application implements the following core functionalities:
1.	Room Management (CRUD):
o	Add Room: Create new room entries with details like Room Number, Type (Standard, Deluxe, Suite), Price Per Night, and initial Status.
o	View Rooms: Display a table of all rooms and their current availability status.
o	Update Status: The room status is automatically updated to 'Occupied' upon booking and back to 'Available' upon check-out.
2.	Guest Management (Create & Read):
o	Add Guest: Register new guests with their Name, Contact number, and Email.
3.	Booking Management (CRUD):
o	Book Room: Create a new booking by selecting an available room and a registered guest, along with Check-In and Check-Out dates.
o	View Bookings: Display all active bookings and calculate the Total Revenue from all active bookings.
o	Check-Out: Delete an active booking and automatically update the corresponding room status back to 'Available'.
4.	Reporting:
o	Displays total revenue from all current bookings.

Technologies & Tools Used
Category	Technology	  Purpose
Main Application	Python 3.x	Core programming language.
Frontend/GUI	Streamlit	Used to create the interactive web application interface.
Database	SQLite3	Lightweight, serverless database for persistent storage (rooms, guests, bookings).
Data Handling	Pandas	Used for fetching SQL query results into DataFrames for easy display and processing.


Steps to Install & Run the Project
This project requires Python 3.6+ and the necessary libraries (streamlit and pandas).
1.	Clone the Repository:
git clone https://github.com/Sayan69-ui/Hotel_Management_System.git
2.	Install Dependencies:
pip install streamlit pandas
3.	Run the Application: Save the provided Python code as app.py and run it from your terminal:
streamlit run app.py
4.	Access the App: The application will automatically open in your web browser, typically at ( http://localhost:8501) .
Instructions for Testing
Follow these steps to test the major functional modules:
1. Initial Setup
•	Database Initialization: The application will automatically create the hotel_management.db  file and the necessary tables (rooms, guests, bookings) when first run via init_db().
•	Test Case: Verify that the hotel_management.db file is created in the project directory.
2. Add Room (CRUD - Create)
1.	Navigate to the Add Room menu item in the sidebar.
2.	Input a Room Number .
3.	Select Type.
4.	Input Price per night .
5.	Select Status .
6.	Click Save Room.
7.	Test Case: Go to View Rooms and confirm that room appears with the correct details and 'Available' status.
3. Add Guest (CRUD - Create)
1.	Navigate to the Add Guest menu item.
2.	Input Name .
3.	Input Contact .
4.	Input Email.
5.	Click Save Guest.
4. Book Room (Booking - Create)
1.	Navigate to the Book Room menu item.
2.	Select the room and the guest .
3.	Set Check-In Date (e.g., today) and Check-Out Date (e.g., 2 days from today).
4.	Verify the calculated Total Amount is correct (2 nights * 2500 = ₹5000.00).
5.	Click Create Booking.
6.	Test Case 1: Go to View Bookings and confirm the new booking is listed.
7.	Test Case 2: Go to View Rooms and confirm Room status has automatically updated to 'Occupied'.
5. Check-Out (Booking - Delete)
1.	Navigate to the Check-Out menu item.
2.	Select the booking created in the previous step .
3.	Click Confirm Check-Out.
4.	Test Case 1: Go to View Bookings and confirm the booking is removed.
5.	Test Case 2: Go to View Rooms and confirm Room status has automatically updated back to 'Available'.
Target Users
Hotels, lodges, PGs, homestays ,
Small hospitality operators requiring an offline management system .
Future Enhancements
1.	Online multi-user system
2.	Customer invoice generation
3.	Advanced search + filters
4.	Revenue analytics dashboards
5.	Email/SMS guest confirmation system
Developer 
SAYAN BHOWMIK
License
This project is for educational purposes under VIT academic guidelines.


