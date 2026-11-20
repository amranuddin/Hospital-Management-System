# 🏥 Hospital Management Mini System (OOP & DBMS Academic Project)

<p align="center">
  👉 **Live Demo Website:** [https://hms-kitten-5b6d93.netlify.app/](https://hms-kitten-5b6d93.netlify.app/)
</p>

An interactive **Hospital Management Mini System** developed as an academic project to streamline essential healthcare administrative workflows. The system combines **Object-Oriented Programming (OOP)** principles with **Database Management System (DBMS)** concepts and follows the **Model-View-Controller (MVC)** architectural design pattern.

The project provides a structured solution for managing patient records, doctor information, and appointment scheduling, with database integration for persistent data storage and retrieval.

---

## 🛠️ OOP Implementation in This Project

This project demonstrates the four fundamental pillars of Object-Oriented Programming:

### 1. Encapsulation
- Patient and Doctor attributes are declared as `private` (e.g., `private String name`).
- Data access and modification are controlled through public getter and setter methods.
- Protects object data from unauthorized direct access.

### 2. Inheritance
- The main UI controller class extends Java's built-in Swing framework: `public class Project extends JFrame`.
- Inherits window management and GUI functionalities from the `JFrame` class.

### 3. Polymorphism
- Method overriding is implemented by redefining the standard `toString()` method in the `Patient` and `Doctor` model classes.
- Enables dynamic and meaningful object representation inside selection components such as `JComboBox`.

### 4. Abstraction
- Separates user interface operations from internal business logic.
- The View interacts with high-level system methods without needing to understand the underlying data processing and database operations.

---

## 🎯 Core Feature Modules

### 1. Patient Registration Module
- **Data Collection:** Registers patient information, including name, age, and medical symptoms or diseases.
- **Input Validation:** Uses exception handling, including `NumberFormatException`, to validate numeric age input.
- **Database Integration:** Stores patient information in the database for persistent record management.
- **Live Directory Sync:** Updates the patient directory and appointment selection components after successful registration.

### 2. Doctor Appointment Scheduler
- **Dynamic Patient Selection:** Retrieves registered patient records to ensure appointments are associated with existing patients.
- **Doctor Portfolio:** Provides doctor profiles categorized by medical specialties, including Cardiologist, Pediatrician, and Neurologist, along with chamber room information.
- **Appointment Management:** Facilitates appointment scheduling by connecting patient and doctor information.
- **Digital Confirmation Voucher:** Generates an appointment confirmation slip through a modal dialogue after successful submission.

### 3. Database Management Module
- **Persistent Data Storage:** Stores application records in a database instead of relying solely on temporary runtime memory.
- **Data Retrieval:** Retrieves previously stored records when required.
- **Data Consistency:** Maintains structured relationships between application entities.
- **DBMS Integration:** Demonstrates practical database operations for managing hospital information.

---

## 🏗️ Architectural Pattern (MVC)

The application follows the **Model-View-Controller (MVC)** architectural pattern and the Separation of Concerns (SoC) principle.

- **Model (`Patient`, `Doctor`):** Represents the application's data entities and provides controlled access to their attributes.
- **Controller/Core Engine (`HospitalSystem`):** Manages application operations, business logic, and interactions between the View and data layer.
- **View (`Project` / UI Components):** Handles the graphical user interface using Java Swing components and layout managers.
- **Database Layer:** Responsible for storing, retrieving, and managing application data through database operations.

---

## 🗄️ Database Integration (DBMS)

Database integration has been added to make the system more reliable and capable of maintaining records beyond a single application session.

Key database capabilities include:

- Storing and retrieving patient records.
- Managing doctor information.
- Maintaining appointment-related information.
- Supporting persistent data management.
- Connecting application operations with the database.

---

## ⚙️ Technical Specifications

| Category | Technology / Concept |
|---|---|
| Programming Language | Java |
| GUI Framework | Java Swing |
| OOP Concepts | Encapsulation, Inheritance, Polymorphism, Abstraction |
| Architecture | Model-View-Controller (MVC) |
| Data Structures | ArrayList |
| Database | Database Integration (DBMS) |
| Exception Handling | Java Exception Handling |
| Deployment | Netlify |

---

## 🎓 Project Objectives

- Apply fundamental OOP concepts in a real-world-inspired application.
- Understand MVC architecture and separation of concerns.
- Implement database connectivity and persistent data storage.
- Practice CRUD-oriented data management.
- Develop an interactive desktop-based hospital management solution.
