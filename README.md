## Urban Gear Ecommerce Platform Documentation

## Project Repository Name: UrbanGear-Ecommerce

### Table of Contents
1. [Introduction](#introduction)
2. [Project Requirements](#project-requirements)
3. [Project Plan](#project-plan)
4. [Source Code](#source-code)
5. [Database Schema](#database-schema)
6. [User Documentation](#user-documentation)
7. [Technical Documentation](#technical-documentation)
8. [Screenshots](#screenshots)
   - [Welcome Page](#welcome-page)
   - [Login Page](#login-page)
   - [Registration Page](#registration-page)
   - [User Homepage](#user-homepage)
   - [Checkout Page](#checkout-page)
   - [Success Order Page](#success-order-page)
   - [Admin Welcome Page](#admin-welcome-page)
   - [Admin Insert Item Page](#admin-insert-item-page)
   - [Admin Items List Page](#admin-items-list-page)
   - [Admin Update Manage Orders Page](#admin-update-manage-orders-page)

---

### 1. Introduction<a name="introduction"></a>

Welcome to the documentation for the **Urban Gear Ecommerce Platform**, an innovative and feature-rich web application developed for Urban Gear's shoe collection. This document provides a comprehensive guide to the project, including its requirements, design, implementation details, and usage instructions.

### 2. Project Requirements<a name="project-requirements"></a>

#### 2.1 Purpose of the Project
The purpose of the Urban Gear Ecommerce Platform is to provide users with a seamless and secure online shopping experience for Urban Gear's shoe collection. The platform includes both user and admin dashboards, ensuring a personalized and efficient journey for clients and administrators.

#### 2.2 Expected Outcomes
- User-friendly interfaces for both clients and administrators.
- Secure user authentication and authorization mechanisms.
- Efficient management of product listings, orders, and client inquiries.
- Seamless payment processing and order fulfillment.
- Robust error handling and graceful user feedback.

#### 2.3 Specific Constraints or Limitations
- Session duration limited to 5 minutes of inactivity.
- Passwords are encrypted during user registration for enhanced security.

### 3. Project Plan<a name="project-plan"></a>

The project plan outlines the scope, timeline, and resources used to complete the Urban Gear Ecommerce Platform. It includes the following phases:
- Requirement Identification
- Database Design
- Spring Boot Project Setup
- Database Setup
- Domain Model Creation
- Service Layer Implementation
- Controller Layer Implementation
- View Layer Implementation
- Testing
- Deployment
- Authentication and Authorization
- Validation
- Pagination
- Search and Filtering
- Error Handling
- Caching
- File Upload and Download

### 4. Source Code<a name="source-code"></a>

#### 4.1 Maven Spring Boot Application
To run the application, execute the following Maven command in the terminal:

```bash
mvn spring-boot:run
```

#### 4.2 Start Redis Server
Ensure Redis is installed and start the server using the following command:

```bash
redis-server
```

#### 4.3 Start MySQL Server
Start the MySQL server using your preferred method or the following command:

```bash
mysql.server start
```

### 5. Database Schema<a name="database-schema"></a>

#### 5.1 Entity Relationships
The project involves three main entities: User, Shoe, and Order. Their relationships are illustrated in the following diagram:
