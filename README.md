# ⚡ Online Electricity Billing System

## 📌 Overview
Managing electricity consumption and billing manually is inefficient, time-consuming, and prone to errors. This project introduces an **automated online electricity billing system** that enables consumers to **view and pay their bills online** without requiring a meter reader to visit their home.  

This system eliminates manual errors, improves efficiency, enhances **privacy**, and ensures **real-time bill generation** through an internet-connected **smart meter**.

---

## 🚀 Features & Technologies

### 🔗 Key Features:
- **Automated Meter Reading**: No need for physical meter readings.
- **Online Bill Viewing & Payment**: Consumers can check and pay bills online.
- **Secure Login & Authentication**: Provides access control for both consumers and administrators.
- **Bill History Tracking**: Consumers can view previous bills and payments.
- **Eco-Friendly**: Reduces paperwork and physical visits.

### 🏗 Tech Stack:
- **Programming Language:** Java (NetBeans)
- **Frontend:** Java Swing (GUI)
- **Backend:** MySQL Workbench
- **Database:** MySQL for storing consumer details, meter readings, and payment history.

---

## 🔍 System Architecture
1. **Smart Meter**:  
   - Tracks electricity units consumed.  
   - Sends readings to the software through an **internet connection (wired/wireless)**.
  
2. **Database (MySQL)**:  
   - Stores meter readings, consumer details, bills, and payments.

3. **User Interface (Java Swing)**:  
   - Allows consumers to **view bills, make payments, and check usage history**.

---

## 🛠 Modules Implemented:
| Module | Description |
|--------|-------------|
| **Login & Signup** | User authentication for secure access. |
| **Consumer Details** | Stores and retrieves consumer data. |
| **Meter Details** | Tracks unit consumption per customer. |
| **Bill Generation** | Calculates the electricity bill based on consumption. |
| **Payment System** | Allows users to pay bills online. |

---

## 📊 Problem Statement
### ❌ Existing System Issues:
- **Manual meter readings** are inconvenient.
- Consumers **must be home** for meter reading.
- **High operational costs** for meter reading staff.
- **Billing errors** due to human miscalculations.
- **No digital bill access**—requires visiting the office.

### ✅ Proposed System Benefits:
- **Eliminates manual readings** by automating the process.
- **Online bill payments** save time and effort.
- **Improves data accuracy** with automated calculations.
- **Reduces operational costs** for energy providers.
- **Enhances customer experience** through real-time bill access.

---

## 💻 Installation & Usage
### 🔽 Prerequisites:
- **Java JDK** installed.
- **NetBeans IDE** for running Java code.
- **MySQL Workbench** for database management.

### ▶️ How to Run:
1. **Clone the repository:**
   ```bash
   https://github.com/SSHarshitha/E-billing-system.git
   cd online-electricity-billing
2. Import the project into NetBeans.
3. Set up the database:
      Open MySQL Workbench.
      Run the provided SQL schema to create necessary tables.
4. Run the application through NetBeans.
