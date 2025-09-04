🏥 Hospital Management System (Java)
📌 Project Overview
The Hospital Management System (HMS) is a Java-based desktop application designed to manage hospital operations efficiently.
It helps in handling patients, doctors, pharmacists, services, appointments, and hospital information through an interactive GUI built with Java Swing.

This project is built following Object-Oriented Programming (OOP) principles, making it modular and scalable.

✨ Features
✅ Patient Management – Add, update, delete, and search patient details.
✅ Doctor Management – Manage doctor profiles and their availability.
✅ Pharmacist & Services – Keep track of medicines, pharmacy records, and hospital services.
✅ Appointment Handling – Patients can book/check appointments with doctors.
✅ GUI Interface – User-friendly Java Swing forms.
✅ Modular OOP Design – Each entity (Doctor, Patient, Pharmacist, etc.) is managed through separate classes.

🛠️ Tech Stack
Language: Java

GUI Framework: Java Swing

Database: (If you used any: MySQL / SQLite / File handling. If not, mention file-based storage.)

IDE: Eclipse / IntelliJ IDEA / NetBeans

📂 Project Structure
Hospital-management-System/
│── ContactUs.java       # Contact form module
│── Doctor.java          # Doctor entity & operations
│── FAQs.java            # Frequently asked questions section
│── Frame1.java          # Main application frame (UI)
│── Frame2.java          # Secondary frame (UI)
│── Hotels.java          # Linked hospital accommodation/hotel info
│── Map.java             # Hospital location map
│── Patient.java         # Patient entity & operations
│── Pharmacist.java      # Pharmacist entity & medicine handling
│── Services.java        # Services provided by hospital
│── README.md            # Project documentation

🚀 How to Run the Project

1️⃣ Clone the Repository
git clone https://github.com/Anmolsingh1222/Hospital-management-System.git
cd Hospital-management-System

2️⃣ Compile the Java files
javac *.java

3️⃣ Run the Application
java Frame1
(or whichever class contains your main() method)

📈 Future Improvements
Add a database (MySQL/SQLite) for persistent storage.
Implement login & authentication for Admin, Doctor, and Patient roles.
Create a billing system to generate patient invoices.
Add report generation using JasperReports or PDF export.
