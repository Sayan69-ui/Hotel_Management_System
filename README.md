# Hotel_Management_System

🏨 Hotel Management System

A streamlit-based hotel automation software that handles room management, guest registration, and booking operations with an internal SQLite database.

The goal is to provide a lightweight hotel administration solution that works offline and simplifies operational workflows.


---

📌 Overview

Manual record-keeping in hotels is slow and prone to mistakes. This system digitizes key restaurant/hotel workflows such as:

✔ Adding rooms with pricing and status
✔ Capturing guest details
✔ Booking rooms with automatic billing
✔ Viewing active bookings and total revenue
✔ Processing check-outs and releasing rooms

The project demonstrates full-stack Python development including UI, database CRUD, and business logic — aligned with project guidelines .


---

✨ Features

🔹 Room management (Add, status tracking)

🔹 Guest database with contact information

🔹 Automated billing based on number of nights

🔹 Booking lifecycle operations (Book → Check-Out)

🔹 Real-time data display inside UI

🔹 Full SQLite persistence for all records



---

🛠 Technologies Used

Tool	Purpose

Python	Backend logic
SQLite	Persistent local database
Streamlit	UI framework
Pandas	Tabular data visualization & transformation



---

📂 Project File Structure

**📁 hotel-management-system
│── hotel_management.db (auto-created after first run)
│── app.py
│── README.md**


---

🚀 How to Install & Run

1️⃣ Install Required Libraries

pip install streamlit pandas

2️⃣ Launch the App

streamlit run app.py

3️⃣ Use the Sidebar Menu to Operate


---

🧪 Testing the Application

Test Case	Expected Output

Add room with duplicate number	Shows integrity error
Booking without valid dates	Check-out must be after check-in
List rooms/bookings	Table displays correctly
Check-out booking	Deletes booking and frees room



---

👥 Target Users

Hotels, lodges, PGs, homestays

Small hospitality operators requiring an offline management system



---

🔮 Future Enhancements

Online multi-user system

Customer invoice generation

Advanced search + filters

Revenue analytics dashboards

Email/SMS guest confirmation system



---

📚 References

VIT Build Your Own Project Submission Guidelines

Streamlit Documentation

SQLite Official Docs



---

