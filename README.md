# ABC-Cars-Portal

A web application that connects buyers and sellers of used cars, providing users a seamless platform to browse a wide variety of used cars and easily place bids or book test drives. With a dedicated administration panel, the application ensures efficient management of user and car data, ensuring a smooth and secure transaction process for all parties involved.

## Project Overview

### There are 2 types of users in this Used Cars Sales portal. They are

- Users
- Administrator


### User Features

- Register in the Portal
- Login to the Portal
- Post a Car for Sale along with Picture upload
- Deactivate an Existing car sale
- Update their Profile after logging in.
- Book an appointment for test drive
- Post the bidding price

### Administrator Features

- Register in the Portal
- Login to the portal
- View List of Registered Users
- Mark a User as Administrator
- Activate / Deactivate a Car post
- Update their profile
- Approve or deny the users appointment based on the bidding
- Transact the sales if price is right

### Common Features for Users & Administrators

- Visit Home Page
- View Car Listing
- Search for a Car by Make, Model, Registration Year & Price Range
- About Us Page
- Contact Us Page

## Technologies Used

The ABC-Cars-Portal project utilizes the following technologies:

- Front-end: JSP(Jakarta Server Page)
- Back-end: Node.js, Express.js
- Database: MySQL
- Authentication: Spring Security
- UI/UX Design: CSS, Tailwind

## Installation and Setup

To run the ABC-Cars-Portal project locally, please follow these steps:

1. Import Existing Project into Visual Studio Code or other IDE that supports Java.
2. Create a MySQL database:

    ```
    mysql> create database cars_portal
    ```

3. Setup `application.properties`:

    ```
    spring.mvc.view.prefix=/views/
    spring.mvc.view.suffix=.jsp
    server.port=8080
    spring.datasource.url=jdbc:mysql://localhost:3306/cars_portal
    spring.datasource.username=<YOUR_DB_USERNAME>
    spring.datasource.password=<YOUR_DB_PASSWORD>   
    spring.jpa.properties.hibernate.dialect = org.hibernate.dialect.MySQL5Dialect
    spring.jpa.hibernate.ddl-auto = update
    spring.jpa.properties.hibernate.show_sql=true
    ```

4. Run the Java application and open http://localhost:8080.

   
