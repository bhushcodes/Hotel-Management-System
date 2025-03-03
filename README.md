# Hotel Management System

## Overview
Hotel Management System is a comprehensive and user-friendly platform that streamlines various hotel functions, including reservations, check-ins, check-outs, room assignments, billing, and more. This README provides an overview of the project, installation instructions, and important information for developers and users.

## Table of Contents
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Prerequisites](#prerequisites)
- [Usage](#usage)
- [Entity Descriptions](#entity-descriptions)

## Features
- **Reservation Management**: Easily create, modify, and manage reservations.
- **Check-In and Check-Out**: Streamlined processes for guest check-ins and check-outs.
- **Room Assignment**: Assign and reassign rooms to guests.
- **Billing**: Generate bills for guests.
- **User-friendly Interface**: Intuitive and responsive UI for staff and guests.

## Technologies Used
- Servlets
- JSP (Java Server Pages)
- HTML
- CSS
- JavaScript (JS)
- Java
- Hibernate with JPA

## Prerequisites
Before you start, make sure you have the following tools and dependencies installed:
- Java Development Kit (JDK)
- Apache Tomcat
- MySQL

## Usage
### 1. Visit the Application
Open your web browser and navigate to the application's URL. Typically, you can access it at `http://localhost:8080/quick-stay-pro` (or the appropriate URL where your Tomcat server is running).

### 2. Sign Up (If You're a New User)
If you're a new user, you need to sign up to use the system. To sign up:
- Click on the "Sign Up" or "Create Account" link on the login page.
- Fill in the required information, which may include your name, email, username, and password.
- Complete the registration process as guided.
- Your registration details may be subject to approval by the respective administrator.

### 3. Log In
Once the signup process is completed, log in with your credentials. The login information includes a username and password created during the signup process.

### 4. Explore Features
Once logged in, you can start exploring the various features of the Hotel Management System, including:
- **Reservation Management**: Create, modify, and manage reservations for guests.
- **Check-In and Check-Out**: Efficiently handle guest check-ins and check-outs.
- **Room Assignment**: Assign or reassign rooms to guests.
- **Billing**: Generate bills for guest stays.
- **User-Friendly Interface**: Utilize the intuitive and responsive user interface designed for both staff and guests.

## Entity Descriptions
### **Admin**
**Responsibilities:**
- Manages Managers.
- Ensures the proper functioning of the entire system.

### **Manager**
**Responsibilities:**
- Manages Users.
- Manages Owners for property-related tasks.
- Approves or disapproves property additions by Owners.
- Oversees day-to-day operations, including staff and guest services.

### **Owner**
**Responsibilities:**
- Lends properties (hotels) to the system.
- Adds hotels after approval from a Manager.
- Provides property-related services and offerings.

### **User**
**Responsibilities:**
- Books rooms.
- Cancels room bookings.
- Views available hotels.
- Interacts with the system for reservations and hotel information.

---
This project provides an efficient and scalable solution for hotel management, ensuring smooth operations for administrators, managers, owners, and guests.

