# Hospital-Management-System
The Hospital Management System is a comprehensive application designed to streamline healthcare management processes. This project is built using **Java** for backend logic and **MySQL with JDBC** for database operations. It enables efficient handling of patient and doctor records, appointment bookings, and availability checks.
## Features

- **Patient Management:** Add, view, and update patient records.
- **Doctor Management:** Maintain doctor profiles and check availability.
- **Appointment Booking:** Schedule and manage patient appointments.
- **Database Integration:** Uses MySQL for efficient data storage and retrieval.

---

## Technologies Used

- **Programming Language:** Java
- **Database:** MySQL
- **Database Connectivity:** JDBC

---
## Setup Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/HospitalManagementSystem.git
   ```

2. Import the project into your IDE.

3. Configure the database:
   - Update the `db.properties` file with your MySQL credentials.

4. Run the project:
   - Execute the `Main.java` file to start the application.

---

## Project Structure

```
HospitalManagementSystem/
├── src/
│   ├── main/
│   │   ├── java/
│   │   │   ├── db/
│   │   │   │   └── DatabaseConnection.java
│   │   │   ├── models/
│   │   │   │   ├── Patient.java
│   │   │   │   ├── Doctor.java
│   │   │   │   └── Appointment.java
│   │   │   ├── services/
│   │   │   │   ├── PatientService.java
│   │   │   │   ├── DoctorService.java
│   │   │   │   └── AppointmentService.java
│   │   │   ├── Main.java
│   ├── resources/
│   │   ├── db.properties
├── README.md
├── LICENSE
└── .gitignore
```

---
