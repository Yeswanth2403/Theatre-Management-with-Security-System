# Theater Management with Security System

## Introduction

Welcome to the Theater Management with Security System project! This system is designed to manage theater operations seamlessly, while incorporating security features such as CAPTCHA, a timer module for secure payments, and a maximum limit of wrong login credentials.

## Features

- MySQL Database Integration: The project uses mysql-connector-j-8.2.0 for seamless integration with a MySQL database. Ensure you have the necessary database setup before running the application.

- CAPTCHA Security: An added layer of security is provided with CAPTCHA to prevent automated attacks and ensure secure user interactions.

- Timer Module for Payment Page: The payment page includes a timer module that automatically closes the page after a specified duration, enhancing the security of the payment process.

- Login Security: To prevent unauthorized access, the system has a maximum limit of 5 wrong login credentials. After reaching this limit, additional security measures may be implemented to protect against potential attacks.

## Security Implementations

### 1. Captcha Integration

To prevent automated attacks and ensure that users are human, we have implemented a CAPTCHA system. This additional layer of security is applied to the registration, login, and other critical forms within the application.

### 2. Timer Module in Payments Page

To mitigate the risk of unauthorized access and potential fraudulent activities during payment processes, a timer module has been incorporated on the payments page. Users are required to complete the transaction within a specified time limit, enhancing the security of financial transactions.

### 3. User Authentication

User authentication is a fundamental security measure implemented to validate the identity of users. This includes secure password storage, multi-factor authentication options, and account lockout policies to protect against unauthorized access.

## Prerequisites

- Ensure you have a MySQL database set up.
- Install the required dependencies, including mysql-connector-j-8.2.0.

## Getting Started

1. Clone the repository:

    bash
    git clone https://github.com/PrithviKamalanathan/theater-management.git
    

2. Set up the MySQL database by executing the SQL scripts provided in the database-scripts folder.

3. Update the config.properties file with your MySQL database credentials.

4. Run the application and navigate to the provided URL.

## Configuration

- Modify the config.properties file to update database credentials, CAPTCHA settings, and other configuration parameters.


## Usage

### Login Page
![image](https://github.com/Prithvikamalanathan/Theatre-Management-System/assets/158607175/629ac94c-229a-418b-b114-89499dc1eff8)
![image](https://github.com/Prithvikamalanathan/Theatre-Management-System/assets/158607175/13ef5c11-f1b5-4362-8463-d0ef5f60165d)

### Register Window
![image](https://github.com/Prithvikamalanathan/Theatre-Management-System/assets/158607175/e0e407e4-425e-4ac2-86f1-d38c18815a2f)

### Movie Window
![image](https://github.com/Prithvikamalanathan/Theatre-Management-System/assets/158607175/2a8c23ed-d21b-4ec7-9657-b585838279db)

### Booking Details
![image](https://github.com/Prithvikamalanathan/Theatre-Management-System/assets/158607175/a05a7918-9a09-4102-a99e-1fea708a7d72)

### Payment Window
![image](https://github.com/Prithvikamalanathan/Theatre-Management-System/assets/158607175/3d4f2630-20f2-420f-83b9-2b9edd6cf280)
![image](https://github.com/Prithvikamalanathan/Theatre-Management-System/assets/158607175/25a973ca-b6ea-4a5d-82f7-f5f6a8fb8c69)

### Receipt Window
![image](https://github.com/Prithvikamalanathan/Theatre-Management-System/assets/158607175/309c58a9-c31e-4980-8931-cfb7cba4cce4)


## Conclusion
We developed this theatre management system using Java Swing ideas, which are a collection of libraries, events, and Graphical User Interface components for the desktop application's design and execution. Customisation of the programme is increased by using the swinging concept. Our project tackles a few security issues. This project provides useful solutions for problems with the Theatre Management System, including safe payment, resource allocation, and brute force attacks.
