# 🛒 E-commerce Project - Spring Boot

This is a basic E-commerce web application built using **Spring Boot**, **Spring MVC**, **Spring Data JPA**, and **Thymeleaf**, with **MySQL** as the backend database. The project demonstrates core functionalities like product management, user authentication, shopping cart operations, and order processing.

## 🔧 Technologies Used

- **Backend**: Java, Spring Boot, Spring MVC, Spring Data JPA
- **Frontend**: HTML, CSS, Thymeleaf
- **Database**: MySQL
- **Build Tool**: Maven
- **Security**: Spring Security (basic)

## ✨ Features

- 🔐 User Registration & Login
- 🛍️ Product Listing and Detail View
- ➕ Add to Cart Functionality
- 🛒 View and Manage Cart
- 📦 Place Orders
- 🧑 Admin Panel for Product Management

## 🗃️ Project Structure
src/ ├── main/ │ ├── java/ │ │ └── com.ecommerce/ # Main Java package │ │ ├── controller/ # Web controllers │ │ ├── model/ # Entity classes │ │ ├── repository/ # Spring Data JPA Repositories │ │ └── service/ # Business logic │ └── resources/ │ ├── application.properties │ └── static/templates/ # JSP files


## 🧑‍💻 How to Run

1. **Clone the repository**
   ```bash
   git clone https://github.com/praveshbajpai/E-commerce-project-springBoot-master.git
   cd E-commerce-project-springBoot-master
Set up MySQL Database

Create a new database named ecommerce_db

Update your application.properties with your MySQL username and password

Build and Run the Application

bash
mvn spring-boot:run
Access the App

User Panel: http://localhost:8080/

Admin Panel: http://localhost:8080/admin (Login credentials can be hardcoded or extended using Spring Security)

🔐 Future Enhancements
Integrate Spring Security for authentication & role-based access

Add payment gateway integration (e.g., Razorpay or Stripe)

Add product search and filtering

Email notifications for order confirmation
