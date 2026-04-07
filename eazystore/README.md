# CardsStore

A comprehensive Spring Boot backend application for the EazyStore e-commerce platform. This project provides a robust, secure, and scalable API for managing products, customers, orders, and payments.

## 🚀 Features

- **Authentication & Authorization**: JWT-based authentication with Spring Security
- **User Management**: Customer registration, login, and profile management
- **Product Management**: CRUD operations for products with popularity tracking
- **Order Processing**: Complete order management system
- **Payment Integration**: Stripe payment gateway integration
- **Security Features**: 
  - Compromised password detection
  - CORS configuration
  - Role-based access control
- **Caching**: Caffeine cache for performance optimization
- **API Documentation**: OpenAPI/Swagger integration
- **Monitoring**: Spring Boot Actuator endpoints
- **Validation**: Comprehensive input validation

## 🛠️ Technology Stack

- **Framework**: Spring Boot 4.0.3
- **Language**: Java 25
- **Database**: MySQL with JPA/Hibernate
- **Security**: Spring Security with JWT
- **Payment**: Stripe Java SDK
- **Caching**: Spring Boot Cache with Caffeine
- **Documentation**: SpringDoc OpenAPI
- **Build Tool**: Maven
- **Additional Libraries**:
  - Lombok for boilerplate reduction
  - Bean Validation for input validation

## 📁 Project Structure

```
src/main/java/com/eazybytes/eazystore/
├── EazystoreApplication.java          # Main application class
├── config/                            # Configuration classes
├── constants/                         # Application constants
├── controller/                        # REST API controllers
│   ├── AuthController.java           # Authentication endpoints
│   ├── ProductController.java        # Product management
│   ├── OrderController.java          # Order processing
│   ├── PaymentController.java        # Payment handling
│   └── ...                           # Other controllers
├── dto/                              # Data Transfer Objects
├── entity/                           # JPA entities
│   ├── Customer.java                 # Customer entity
│   ├── Product.java                  # Product entity
│   ├── Order.java                    # Order entity
│   └── ...                          # Other entities
├── exception/                        # Custom exception handlers
├── filter/                           # Security filters
├── repository/                       # JPA repositories
├── security/                         # Security configuration
├── service/                          # Business logic layer
└── util/                            # Utility classes
```

