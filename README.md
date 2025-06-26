# smart-medicine-reminder
Smart Medicine Reminder &amp; Tracker is a Java Swing desktop app to schedule medicines, track doses (taken/missed), and generate compliance reports with CSV export. Built using OOP, file handling, and a modular architecture for clean and scalable design.
# 💊 Smart Medicine Reminder & Tracker (Java + OOPs)

A complete desktop-based application to help users manage their medicine schedules, track doses, and monitor compliance over time. Built with **Java OOP principles** and **Swing GUI**, this project is ideal for your SDE resume and interviews.

---

## 🚀 Features

- ✅ Add & schedule medicines with dosage, time(s), and duration
- 📆 Show daily schedule with remaining/missed doses
- 🕒 Track doses taken or missed (Mark Taken / Mark Missed)
- 📊 View compliance summary with statistics
- 📤 Export compliance report to CSV
- 💡 Modular design using OOPs: Inheritance, Abstraction, Encapsulation, Interfaces

---

## 📁 Project Structure

smartmedicinereminder/
├── AppLauncher.java # CLI version (optional)
├── model/ # Core classes
│ ├── Medicine.java
│ ├── Schedule.java
│ └── User.java
├── service/ # Utility & logger
│ └── DoseLogger.java
├── ui/ # Java Swing UI components
│ ├── MainWindow.java
│ ├── MedicineFormPanel.java
│ ├── SchedulePanel.java
│ ├── DoseNowPanel.java
│ ├── MarkDosePanel.java
│ ├── MarkMissedPanel.java
│ ├── ComplianceReportPanel.java
│ └── ExportPanel.java
└── dose_log.txt # Auto-generated log file

yaml

---

## 🛠️ Technologies Used

- 🧠 Java (OOP concepts, Collections, File I/O)
- 🖥️ Swing (for GUI)
- 🗃️ File Handling (`dose_log.txt`, `compliance_report.csv`)
- 📁 Java Packages for modular design

---

## ✅ How to Run

### 1. Compile

```bash
javac --release 8 model/*.java service/*.java ui/*.java AppLauncher.java
java ui.MainWindow
Medicine,Taken,Missed,Compliance %
Paracetamol,3,1,75.00%
Ibuprofen,5,0,100.00%
Concepts Covered
Object-Oriented Programming (Classes, Encapsulation, Inheritance)

File Handling & Logging

Java Collections (Map, List)

GUI Programming (Java Swing)

Modular Architecture & Clean Code


