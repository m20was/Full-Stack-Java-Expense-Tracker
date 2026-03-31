# Full Stack Expense Tracker 💰

A complete Full-Stack Expense Tracker built entirely in Java. Features a Spring Boot REST API backend with MySQL for secure data storage, and a custom JavaFX client for the frontend. Includes user authentication, custom category creation, transaction logging, and interactive monthly financial charts.

## ✨ Features
* **User Authentication:** Secure Sign Up and Log In functionality.
* **Interactive Dashboard:** View current balance, total income, and total expenses at a glance.
* **Transaction Management:** Add, edit, delete, and view income and expenses.
* **Custom Categories:** Create custom categories with personalized colors.
* **Data Visualization:** Monthly bar charts to visually track income vs. expenses.
* **Pagination:** Efficiently load recent transactions using paginated API calls.

## 🛠️ Tech Stack
* **Language:** Java (v23)
* **Backend:** Spring Boot, Spring Data JPA, REST API
* **Frontend:** JavaFX, Gson (for JSON parsing)
* **Database:** MySQL
* **Build Tool:** Maven

## 📂 Project Structure
This repository contains both the client and server applications in separate directories:
* `/expense-tracker-spring-boot-server`: The backend Spring Boot REST API.
* `/expense-tracker-client`: The frontend JavaFX application.

## 🚀 Getting Started

### Prerequisites
Before you begin, ensure you have the following installed:
* [Java Development Kit (JDK) 23](https://jdk.java.net/23/) or higher
* [Maven](https://maven.apache.org/)
* [MySQL Server and Workbench](https://dev.mysql.com/downloads/)

### 1. Database Setup
1. Open MySQL Workbench.
2. Create a new schema named `expense_tracker_db`:
   ```sql
   CREATE SCHEMA expense_tracker_db;
