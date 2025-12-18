# 🛒 Ecommerce Microservices Architecture


This project is a fully modular **Ecommerce Backend** built using a complete **Microservices Architecture**.  
Each service is independently deployable, scalable, and communicates through **REST APIs**, **Kafka**, and **API Gateway**.

📁 Project Repositories (Microservices)

Service	Repository Link

User Service	https://github.com/PranavX500/User-Service-UrbanMart-.git

Product Service	https://github.com/PranavX500/Product-Service-UrbanMart-.git

Order Service	https://github.com/PranavX500/Order-service-UrbanMart-.git

Payment Service	https://github.com/PranavX500/Payment-Service-Urban-Mart-.git

Cart Service	https://github.com/PranavX500/Cart-Service-Urban-Mart-.git

OTP Service	https://github.com/PranavX500/Otp-Service-UrbanMart-.git

Notification Service	https://github.com/PranavX500/Notification-Serivice-Urban-Mart-.git

API Gateway	https://github.com/PranavX500/Api-Gatway-UrbanMart-.git

Eureka Server	https://github.com/PranavX500/Eureka-Server-UrbanMart-.git

---


# 🧱 Microservices Included
| Service | Description |
|--------|-------------|
| **User Service** | Handles user registration, login, authentication data, and profile management
| **Product Service** | Manages product CRUD operations |
| **Order Service** | Handles order creation, validation, status updates |
| **Payment Service** | Processes payments and updates order status |
| **OTP Service** | Sends OTP for login/verification using Redis + Kafka |
| **Notification service** | Sends Notification To user in many things |
| **Inventory service** | Have the information of all stocks |
| **API Gateway** | Single entry point for all microservices |
| **Eureka Server** | Service registry and discovery |

---



# 🧰 Tech Stack

### **Backend Framework**
- Spring Boot  
- Spring MVC  
- Spring Cloud (Eureka, Gateway)

---


### **Databases**
- MySQL 
- Redis 

---


### **Message Broker**
- Apache Kafka

---


### **APIs**
- REST APIs  
- Inter-service communication through Gateway + Kafka

---

### **Other**
- Lombok  
- Maven  
- Postman / Thunder Client for testing

---


# 🧪 Testing Endpoints

### Access through API Gateway:(THE PROJECT IS NOT YET DEPLOYED SO GIVING LOCAL HOST LINK IN CASE YOU WANT TO TEST IN YOUR SYSTEM)
- User:`http://localhost:8080/product-service/...`
- Product: `http://localhost:8080/product-service/...`
- Order: `http://localhost:8080/order-service/...`
- Payment: `http://localhost:8080/payment-service/...`
- OTP: `http://localhost:8080/otp-service/...`
- Notification:`http://localhost:8080/Notification-service/...`
- Inventory:`http://localhost:8080/Inventory-service/...`

# 🎯 Features Implemented

✔ Microservices independently deployed  
✔ Service registry with Eureka  
✔ API Gateway routing  
✔ Distributed communication using Kafka  
✔ OTP generation + Redis caching  
✔ CRUD operations for products  
✔ Order creation & status flow  
✔ Payment processing workflow  
✔ Clean repo structure  
✔ Scalable backend architecture  
(Many more to be come)

# 👤 Author

**Pranav Sharma**  
Microservices | Spring Boot | Kafka | SQL | React 
