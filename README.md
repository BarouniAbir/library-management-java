# Library Management System — Java SE + MySQL

> **Academic project** — A simple and functional library management system built with **Java SE**, **Swing**, **JCalendar**, and **MySQL**.  
> This project allows managing books, members, and loans with a graphical user interface and database persistence.

---

## Project Description
This application was developed as part of an academic assignment to simulate the management of a small library.  
It allows administrators to:
- Add, edit, or remove books and members
- Manage book loans and returns
- Track loan history
- Use a friendly Swing interface enhanced with **JCalendar** for date selection
- Store and retrieve data from a **MySQL** database

The project is structured for easy understanding and extension, making it a good starting point for learning **Java GUI development** and **database integration**.

---

## Features
- Book management (add, update, delete)
- Member management
- Loan and return tracking
- Calendar integration with **JCalendar**
- MySQL database support
- Lightweight and easy to run locally

---

## Tech Stack
- **Language:** Java SE  
- **GUI Framework:** Swing + JCalendar  
- **Database:** MySQL  
- **IDE:** NetBeans / IntelliJ / Eclipse (any Java IDE works)

---

## Installation & Setup

### 1. Clone the repository
```bash
git clone https://github.com/<your-username>/library-management-java.git
cd library-management-java
````

### 2. Import into your Java IDE

* Open the project in NetBeans / IntelliJ / Eclipse.
* Make sure JCalendar is added to your project libraries (if not, download the jar and include it in the build path).

### 3. Set up the database

* Create a MySQL database.
* Import the provided SQL script:

```bash
mysql -u root -p < Base_de_données.sql
```

* Update the database credentials in the project configuration file or directly in the connection class.

### 4. Run the application

* Compile and run the project from your IDE.
* The main GUI will open and you can start managing books, members, and loans.

---

## Project Structure

```
Java Project/
 ├─ Biblio/                  # Main application code (Java)
 ├─ JCalendar/               # JCalendar library files
 ├─ Base_de_données.sql      # MySQL database structure
 ├─ README.md
 └─ .gitignore
```

---

## Future Improvements

* Authentication system for admin users
* Advanced search and filters
* Statistics dashboard
* Export reports (PDF/Excel)
* Better exception handling

---

## Author

Developed with by**Barouni Abir**
