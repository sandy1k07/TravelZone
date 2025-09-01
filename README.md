# travel-management-system
Travel Agency Management System in C++ | Object Oriented Programming | File Handling
# Travel Management System (C++)

## 📌 Overview
The **Travel Management System** is a console-based project written in **C++**.  
It allows administrator to manage travel bookings on behalf of users.  
Currently, the system stores user data such as **Name, Age, and Address**,  
but user onboarding (self-registration) is not implemented yet.

---

## 🚀 Features
- Add new travelers with details (Name, Age, Address, etc)
- Store data persistently in files
- View list of travelers
- Manage bookings by the admin

---

## 🛠️ Tech Stack
- **Language**: C++
- **File Handling**: Used for storing user data
- **OOP Concepts**: Classes, Encapsulation

---

## 📂 Project Structure
```
TravelManagement/
├── travel.cpp          # Core logic (Traveler class, file handling)
├── receipt.txt         # Booking receipt
├── old-customers.txt   # File storing traveler details
└── README.md           # Documentation
```

---

## ⚙️ How to Run
1. Clone the repository or download the project files.
2. Compile using g++:
   ```bash
   g++ main.cpp travel.cpp -o TravelZone
   ```
3. Run the program:
   ```bash
   ./TravelZone.exe
   ```

---

## 📌 Future Enhancements
- ✅ Add user self-onboarding (registration/login)
- ✅ Provide different roles (Admin & User)
- ✅ Add searching and filtering options

---

## 👤 Author
Developed as part of a **C++ Project** for learning **OOP & File Handling** concepts.
