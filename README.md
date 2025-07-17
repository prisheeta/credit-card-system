# credit-card-system
Credit Card Application using SpringBoot

## Overview
This is a microservices-based Credit Card Platform. Features include:
- Browse credit cards
- Apply for a credit card
- Approval by back-office team
- Notify customers on approval
- Track application status
- 
---

## Architecture
- **API Gateway** (Spring Cloud Gateway)
- **Microservices**:
   - Catalog Service (Browse credit cards)
   - Application Service (Apply for credit card)
   - Approval Service (Approval & Verification)
   - Notification Service (Send notifications)
- **Database**: H2 (In-memory)
- 
---

## Tech Stack
- **Java** (JDK 17)
- **Spring Boot** 3.x
- **Spring Web**, **Spring Data JPA**
- **H2 Database** (for local testing)
- **springdoc-openapi** (Swagger UI)

---


## How to Run Locally
1. **Clone the repo**
   git clone https://github.com/prisheeta/credit-card-system.git
   cd credit-card-system

2. **Run with Maven**
   mvn spring-boot:run -Dspring-boot.run.profiles=local



