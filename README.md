# Student Management System | SAP ABAP RAP & Fiori Elements

## 📌 Project Overview

The **Student Management System** is a hands-on project developed using **SAP ABAP RESTful Application Programming Model (RAP)** and **SAP Fiori Elements**.

The application allows users to manage student information through a user-friendly interface. It demonstrates how SAP RAP can be used to build and expose business applications using CDS Views, Behavior Definitions, and OData Services.

This project helped me understand the end-to-end development process of a basic SAP RAP application.

## 🎯 Features

* Create new student records.
* View student details.
* Update existing student information.
* Delete student records.
* Display student data using SAP Fiori Elements.
* Expose application functionality through an OData V2 UI service.

## 🛠️ Technologies Used

* **SAP ABAP** – Backend programming
* **ABAP RAP** – Application development framework
* **CDS Views** – Data modeling
* **Behavior Definitions** – Business operation handling
* **OData V2** – Service exposure
* **SAP Fiori Elements** – User interface
* **Eclipse ADT** – Development environment

## 🏗️ Project Architecture

The application follows the SAP RAP development architecture:

1. **Database Table:** Stores student information.
2. **Root CDS View:** Defines the core data model.
3. **Projection CDS View:** Exposes the required fields for the application.
4. **Behavior Definition:** Defines supported operations such as Create, Update, and Delete.
5. **Behavior Implementation:** Handles the RAP behavior implementation.
6. **Metadata Extension:** Defines UI annotations for Fiori Elements.
7. **Service Definition:** Exposes the projection view as a service.
8. **Service Binding:** Publishes the service using OData V2 UI.

## 📂 Main Development Objects

| Object Type                   | Object Name        |
| ----------------------------- | ------------------ |
| Database Table                | `ZSTUDENT_01`      |
| Root CDS View                 | `ZR_STUDENT_01`    |
| Projection CDS View           | `ZC_STUDENT_01`    |
| Behavior Implementation Class | `ZBP_R_STUDENT_01` |
| Service Definition            | `ZSD_STUDENT_01`   |

*Additional objects include Behavior Definitions, Behavior Projections, Metadata Extensions, and Service Binding.*

## ⚙️ Application Operations

The application supports the following CRUD operations:

* **Create:** Add new student records.
* **Read:** Display student information.
* **Update:** Modify existing student details.
* **Delete:** Remove student records.

## 📸 Screenshots
<img width="1280" height="680" alt="image" src="https://github.com/user-attachments/assets/3c21eaab-ac0e-46d0-9c4a-7a1428365e28" />

<img width="1280" height="680" alt="image" src="https://github.com/user-attachments/assets/ee532a0c-e4b5-4b5e-a795-4e28c666054a" />


## 📚 Key Learnings

Through this project, I gained practical experience in:

* Understanding the fundamentals of SAP ABAP RAP.
* Creating and using CDS Root and Projection Views.
* Working with Managed Behavior Definitions.
* Configuring UI annotations using Metadata Extensions.
* Creating Service Definitions and Service Bindings.
* Exposing backend functionality through OData.
* Building a functional application using SAP Fiori Elements.

## 🚀 Project Status

**Completed – Basic CRUD functionality implemented.**

This is a learning project developed to gain hands-on experience with SAP ABAP RAP and Fiori Elements.

**Developed as part of my SAP ABAP learning journey.**
