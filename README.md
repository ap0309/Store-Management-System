# Store Management System

## Introduction

This project implements a **Store Management System** using **MySQL** and **Python** with the Python-MySQL connector. It provides a rich **Graphical User Interface (GUI)** built using the Tkinter library to make the system accessible and easy to use for all users.

The main goal of the project is to deliver a **user-friendly, scalable, and secure** application capable of managing a store’s inventory, sales, purchases, and customer data efficiently. The system is designed to automate core store operations, minimizing errors and saving time for store owners.

## What is Store Management System?

A Store Management System is an essential software tool for store owners to handle inventory, sales, purchases, and customer information effectively. By automating these processes, it helps reduce operational costs, improve accuracy, and boost overall business efficiency.

## Technologies Used

- **MySQL** – For database management  
- **Python** – For application logic  
- **Python-MySQL Connector** – To connect Python with MySQL  
- **Tkinter** – For building the graphical user interface  

## Problem Statement

Manual management of inventory, sales, purchases, and customer data can be time-consuming and prone to human errors. This leads to issues such as incorrect inventory counts, inaccurate sales records, and incomplete customer data, causing lost sales and customer dissatisfaction.

With modern stores becoming more complex and online sales increasing, store owners require an automated, reliable, and efficient system to manage operations seamlessly.

This project addresses these challenges by designing a **Store Management System** that is:

- User-friendly  
- Scalable  
- Secure  

The system helps track inventory levels, manage sales and purchases, maintain accurate customer records, and provides real-time reporting for better business decisions.

## About the Project

This system automates key store management processes through:

- Designing a comprehensive **database schema** to support store operations  
- Developing application logic in **Python**  
- Creating an intuitive and easy-to-navigate **user interface**  

Features include:

- Inventory management (add, update, delete products)  
- Sales management and transaction tracking  
- Purchase history and management  
- User account and role management  
- Generating reports on inventory, sales, purchases, and profits  

The system is built to be **scalable, secure**, and supports **real-time reporting** to help store owners make informed decisions.

## ER Diagram

### Entities:
- CUSTOMER  
- DEALER  
- INVOICES  
- INVOICE DETAILS (Weak Entity)  
- PURCHASES  
- PURCHASE DETAILS (Weak Entity)  
- PRODUCT  

### Entity Relationships:
- CUSTOMER — INVOICES  
- PRODUCT — PURCHASE DETAILS  
- INVOICE — INVOICE DETAILS  
- INVOICE DETAILS — PRODUCT  
- DEALER — PURCHASES  
- PURCHASE DETAILS — PURCHASES  

## Usage

1. Install Python and MySQL on your system.  
2. Configure the MySQL database using the provided schema.  
3. Run the Python application; the GUI will allow you to manage store operations.  

## License

[Specify your license here, e.g., MIT License]
