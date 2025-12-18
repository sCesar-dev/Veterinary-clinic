# 🐾 [PetCare System - Veterinary Clinic Management System in Java](https://www.google.com/search?q=https://github.com/sCesar-dev/Veterinary-clinic)
***Portuguease version: [README.md](README.md)***

## Overview

**PetCare System** is a desktop solution developed in Java to automate and manage the operational workflow of veterinary clinics. The system centralizes everything from pet owner and patient registration to detailed clinical control, including vaccine management and automated billing.

The goal of this project is to demonstrate the practical application of solid Software Engineering and Object-Oriented Programming (OOP) concepts to solve real-world business problems.

## Key Features

* **Medical Records Management:** A complete history system allowing the registration and consultation of diagnoses, treatments, and clinical evolution of animals.
* **Smart Vaccine Card:** A module dedicated to immunological control, monitoring application dates and automatically calculating due dates/returns.
* **Automated Billing System:** Financial integration that calculates the total service value by summing consultations (based on the veterinarian's specialty) and vaccines administered on the day.
* **Fluid GUI:** Interface built with **Java Swing** using the `CardLayout` manager, providing intuitive and fast navigation between screens without opening multiple windows (Single Window Application).

## Architecture and Design

The project was structured following the pillars of **Object-Oriented Programming (OOP)**:

* **Inheritance:** Used to model the hierarchy of users and employees.
* *Example:* The `Veterinario` class extends `Funcionario`, inheriting common attributes and adding specifics such as CRMV (Medical License) and Specialty.
* *Example:* The `Tutor` (Owner) class extends `Pessoa` (Person).


* **Encapsulation:** All attributes of model classes (`Animal`, `Consulta`, `Agendamento`) are private and accessed via getter and setter methods, ensuring data integrity.
* **Polymorphism:** Applied in the generic treatment of lists and the manipulation of derived objects.
* **Organization:** The code is separated into logical packages (`vet.clinic`), clearly distinguishing between model classes, screens (Views), and control logic (`Sistema`).

## Technologies Used

* **Language:** Java (JDK 8+)
* **GUI:** Swing (JFrame, JPanel, CardLayout)
* **Date Handling:** Java Time API (`LocalDate`, `LocalDateTime`, `DateTimeFormatter`) for precision in scheduling and due dates.
* **IDE:** NetBeans

## 📸 Screenshots

* *Main Menu Screen*
<img width="659" height="481" alt="Screenshot from 2025-12-18 14-56-04" src="[https://github.com/user-attachments/assets/d59a7430-1583-4237-9cef-c0bbd5391d00](https://github.com/user-attachments/assets/d59a7430-1583-4237-9cef-c0bbd5391d00)" />
* *Animal Registration*
<img width="659" height="481" alt="Screenshot from 2025-12-18 14-58-53" src="[https://github.com/user-attachments/assets/f7632678-7d63-4586-9a68-4d1c703548f7](https://github.com/user-attachments/assets/f7632678-7d63-4586-9a68-4d1c703548f7)" />
<img width="659" height="481" alt="Screenshot from 2025-12-18 15-01-54" src="[https://github.com/user-attachments/assets/9cbefcdb-5655-441a-8140-de075b1222e5](https://github.com/user-attachments/assets/9cbefcdb-5655-441a-8140-de075b1222e5)" />
* *Medical Record & History*
<img width="659" height="481" alt="Screenshot from 2025-12-18 15-02-09" src="[https://github.com/user-attachments/assets/b4bb61f4-9126-469d-98ce-9b018116b758](https://github.com/user-attachments/assets/b4bb61f4-9126-469d-98ce-9b018116b758)" />
<img width="659" height="481" alt="Screenshot from 2025-12-18 15-04-11" src="[https://github.com/user-attachments/assets/4bfea19b-00b3-4d29-aa13-71babffc4468](https://github.com/user-attachments/assets/4bfea19b-00b3-4d29-aa13-71babffc4468)" />
<img width="659" height="481" alt="Screenshot from 2025-12-18 15-04-24" src="[https://github.com/user-attachments/assets/a27ae9fc-4e95-49b4-bac9-aa76b845a427](https://github.com/user-attachments/assets/a27ae9fc-4e95-49b4-bac9-aa76b845a427)" />

## ▶️ How to Run

1. **Clone the repository:**
```bash
git clone git@github.com:sCesar-dev/Veterinary-clinic.git

```


2. **Open the project:** Import the project folder into your preferred IDE (NetBeans or IntelliJ IDEA recommended).
3. **Run:** Locate the main class `Main.java` in the package `src/main/java/vet/clinic` and execute the file.

---

Developed by **Samuel Cesar, Isabel Souza, and Caio Lopes**
[LinkedIn](https://www.linkedin.com/in/samuel-cesar-193275219/) | [Resume/CV](https://drive.google.com/drive/folders/18tICYCLwsoPX-RiXlsOtCtOEBoI_dBR2?usp=sharing)