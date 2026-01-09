# finalproject
Spring Boot REST API Application
Project Description
This project is Task 2 for the Spring Framework Apps assignment. The goal of this task is to create
a fully functional REST API using Spring Boot. The application supports CRUD operations,
exception handling, Swagger documentation, and an in-memory H2 database.
Technologies Used
• Java
• Spring Boot
• Spring Web (REST)
• Spring Data JPA
• H2 Database
• Swagger / OpenAPI
• Maven
How to Run the Application
1. Open the project in IntelliJ IDEA
2. Reload Maven dependencies
3. Run Project2Application.java
4. Application runs on port 8080
API Endpoints
POST /api/v1/products – create product
GET /api/v1/products/{id} – get product by id
GET /api/v1/products – get all products
PUT /api/v1/products/{id} – update product
DELETE /api/v1/products/{id} – delete product
H2 Database
URL: http://localhost:8080/console
JDBC URL: jdbc:h2:mem:testdb
User: sa
Password: (empty)
Swagger UI
URL: http://localhost:8080/swagger-ui/index.html
Application Architecture
Controller – handles HTTP requests
Service – business logic
Repository – database access using JPA
Mapper – maps request and response objects
Exception Handling
Custom exception handling is implemented using @ControllerAdvice. When a product is not found,
the API returns HTTP 404 with a descriptive error messag<img width="2263" height="1421" alt="Screenshot 2025-12-22 172737" src="https://github.com/user-attachments/assets/6065cd72-f575-4599-834b-9c49d1b57570" />
<img width="2188" height="1333" alt="Screenshot 2025-12-22 172819" src="https://github.com/user-attachments/assets/cf6da5b2-b785-4447-9f7c-7e6c86b88813" />  <img width="1278" height="924" alt="Screenshot 2026-01-06 220941" src="https://github.com/user-attachments/assets/aa64d9b6-8eca-4968-967a-d85f3e0cb5cf" />
/>
<img width="1245" height="878" alt="Screenshot 2026-01-06 220956" src="https://github.com/user-attachments/assets/bcb10717-225d-4082-8d10-c211fa68acc6" />
<img width="1239" height="891" alt="Screenshot 2026-01-06 221036" src="https://github.com/user-attachments/assets/22577691-b2ee-455a-90d9-4965083cf2a7" />
<img width="1377" height="782" alt="Screenshot 2026-01-06 221051" src="https://github.com/user-attachments/assets/c2927194-de04-4611-bb19-35afdd0f213b" />
<img width="999" height="514" alt="Screenshot 2026-01-06 221125" src="https://github.com/user-attachments/assets/a262e631-8909-4ec1-bd98-e934b36cdb12" />
<img width="1212" height="724" alt="Screenshot 2026-01-06 221145" src="https://github.com/user-attachments/assets/50e16b34-e5a3-4b2a-8afd-a47e3cc9fdb1" />
