# 🍕 PizzaKid POS Database

---

### *Streamlining Orders. Automating Inventory. Powering Pabayo CDO.*

<p align="left">
  <img src="https://img.shields.io/badge/DATABASE-MYSQL-00758F?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL" />
  <img src="https://img.shields.io/badge/TOOL-PHPMYADMIN-D16100?style=for-the-badge&logo=phpmyadmin&logoColor=white" alt="phpMyAdmin" />
  <img src="https://img.shields.io/badge/ENVIRONMENT-XAMPP-F37C20?style=for-the-badge&logo=xampp&logoColor=white" alt="XAMPP" />
</p>

Welcome to the **PizzaKid POS Database Repository**! 👋

This repository contains the complete MySQL relational database schema and seed data for the **PizzaKid Point of Sale (POS) System** (Pabayo St. Branch, Cagayan de Oro City). It is engineered to handle high-throughput cashier ordering, automated recipe inventory deduction, custom menu modifiers, and kitchen prep workflows.

The database supports 20 core relational tables covering multi-role user authentication, itemized transactions, split payments, recipe-based stock deduction, KDS updates, and operational audit logs.

---

## 📌 Table of Contents

* [🎯 Project Overview](#-project-overview)
* [✨ Database Features](#-database-features)
* [⚙️ Stored Functions and Procedures](#%EF%B8%8F-stored-functions-and-procedures)
* [🛠️ Technologies Used](#%EF%B8%8F-technologies-used)
* [🚀 Getting Started](#-getting-started)
* [💻 Sample SQL Queries](#-sample-sql-queries)
* [🔒 Project Notes](#-project-notes)
* [⭐ Support the Project](#-support-the-project)

---

## 🎯 Project Overview

The **PizzaKid POS Database (`pizza_db`)** serves as the data storage foundation of a Point of Sale and Inventory Management System tailored for PizzaKid (Pabayo St. Branch, Cagayan de Oro City).

It provides an organized 20-table relational database structure for storing, retrieving, and maintaining records involved in daily store transactions, kitchen prep workflows, and ingredient inventory management.

It also includes automated database triggers, relational constraints, and indexed queries that support common store operations, such as recipe-based stock deductions, dynamic menu modifier pricing, cashier shift tracking, and multi-terminal synchronization.

**The goal is simple: Streamline order processing, automate inventory tracking, and make daily store operations easier to manage.**

---

## ✨ Database Features

| Feature | Description |
| :--- | :--- |
| 👤 **User & Role Management** | Stores manager, cashier, and kitchen staff credentials and role assignments. |
| 🍕 **Menu Catalog** | Stores pizza categories, items, descriptions, prices, and availability status. |
| 🧀 **Modifier Engine** | Handles crust options, extra toppings, selection limits, and add-on pricing. |
| 📦 **Inventory Control** | Tracks raw ingredient stock levels, minimum reorder thresholds, and units. |
| 📖 **Recipe Mapping** | Links menu items directly to ingredients for automatic inventory deduction. |
| 🛒 **Order Engine** | Manages dine-in, takeout, and delivery transactions and line item sub-totals. |
| 💳 **Payment Records** | Tracks split payments, payment methods (Cash, GCash, Maya, Card), and statuses. |
| 🍳 **Kitchen Display System** | Monitors station-specific prep progress from order receipt to completion. |
| 🔄 **POS Sync Logging** | Maintains terminal sync status and handles transaction transmission logs. |
| 🛡️ **Audit & Notifications** | Records user action logs, stock reorder alerts, and system overrides. |


## 🛠️ Technologies Used

* **MySQL** – Relational database management system.
* **phpMyAdmin** – Database administration and management.
* **XAMPP** – Local development environment.
* **SQL** – Database queries, automated inventory triggers, and relational schemas.
* **Draw.io** – ERD schema modeling and database relationship mapping.

## 🚀 Getting Started

Ready to explore the database? Follow these steps!

### 1. Prepare the Environment

* Install [XAMPP](https://www.apachefriends.org/).
* Open XAMPP Control Panel.
* Start Apache and MySQL.

### 2. Open phpMyAdmin

Visit:

```text
http://localhost/phpmyadmin

