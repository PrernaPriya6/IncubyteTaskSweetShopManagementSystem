# IncubyteTaskSweetShopManagementSystem
# Sweet Shop Management System

## Overview

The **Sweet Shop Management System** is a full-stack web application designed to manage sweets inventory and sales operations in a simple and efficient way. The backend is developed using **Java with Spring Boot**, while the frontend is built using **ReactJS**. The project strictly follows a **Test-Driven Development (TDD)** methodology, where all business logic was implemented only after writing test cases using **JUnit 5**.

This application was created as part of the **Incubyte TDD Kata Assessment**, with a strong focus on clean architecture, test coverage, and clear separation of concerns.

---

## Key Features

* Add, view, and delete sweets
* Search sweets by name, category, or price range
* Sort sweets by price or quantity (both ascending and descending)
* Purchase sweets with stock validation
* Restock sweets with quantity checks
* Centralized exception handling using custom exceptions
* Responsive and user-friendly UI using Bootstrap
* In-memory data storage (no external database used)

---

## Project Structure

### Backend

```
/Backend
 ├── src
 │   ├── main
 │   │   └── java
 │   │       └── com.incubyte.sweetshop
 │   │            ├── controller
 │   │            ├── service
 │   │            ├── model
 │   │            └── customExceptions
 │   └── test
 │       └── java
 │           └── com.incubyte.sweetshop.service
 └── pom.xml
```

### Frontend

```
/Frontend
 ├── src
 └── package.json
```

---

## TDD Journey Highlights

* Followed the Red-Green-Refactor cycle consistently
* Started by writing failing test cases before implementation
* Implemented only the minimum code required to pass tests
* Refactored code after tests passed to improve readability and design
* Achieved complete test coverage for service-layer logic
* Included edge case testing and validation scenarios
* Used meaningful and incremental Git commits throughout development

---

## API Overview

* **Add Sweet**: `POST /sweetshop/api/sweet/add`
* **Get All Sweets**: `GET /sweetshop/api/sweet/getAllSweets`
* **Search, Sort, Purchase, Restock**: Fully implemented REST APIs following clean service-based architecture

---

## Technologies Used

### Backend

* Java 21
* Spring Boot 3.5.3
* JUnit 5
* Maven
* Custom Exception Handling

### Frontend

* ReactJS
* Axios (API communication)
* Bootstrap 5
* React Hot Toast (notifications)

---

## How to Run the Project Locally

### Backend Setup

```bash
cd Backend
mvn clean install
mvn spring-boot:run
```

Backend will start at: `http://localhost:8080`

### Frontend Setup

```bash
cd Frontend
npm install
npm run dev
```

Frontend will run at: `http://localhost:5173`

---

## Application Screenshots

* Home Page
* Add Sweet Modal
* Sorting by Quantity (Ascending)
* Searching by Name
* Searching by Category
* Sorting by Price Range (Min & Max)
* Deleting a Sweet (Gajar Halwa)
* Purchasing a Sweet (Rabdi)
* Restocking a Sweet (Kaju Katli)

Additional screenshots are available in the **screenshots** folder.

---




## Test Report

* All service-layer test cases executed successfully
* 100% pass rate for implemented test scenarios
* Tests include positive flows, edge cases, and exception conditions

---

## Author

**Prerna Priya**

This project was developed as part of the **Incubyte Assessment**.

---

## Notes

* No external database was used; all data is managed in memory
* Plagiarism-free implementation
* AI assistance was used responsibly and transparently, as described above


## Screenshots Of Frontend

### Application Home Page  
![Home Page](screenshots/HomePage.jpeg)

### Add Sweet Modal  
![Add Sweet](screenshots/AddSweet.jpeg)

### Sort Sweet By Quantity in Ascending Order  
![Sort Sweet](screenshots/SortByQuantityAscending.jpeg)

### Search Sweet By Name  
![Search Sweet](screenshots/SearchByName.jpeg)

### Search Sweet By Category  
![Search Sweet](screenshots/SearchByCategory.jpeg)

### Sort Sweet By Price Range(Min,Max)  
![Sort Sweet](screenshots/SearchByPriceRange.jpeg)

### Delete Sweet Gajar Halwa
![Delete Sweet](screenshots/DeleteSweet.jpeg)

### Purchase Sweet Rabdi - Quantity(10)
![Purchase Sweet](screenshots/PurchaseSweetRabdi.jpeg)

### Restock Sweet Kaju Katli - Quantity(10)
![Restock Sweet](screenshots/RestockKajuKatli.jpeg)

- Rest of the Screenshots are attached in screenshots folder
## Author

Prerna Priya
This project is built as part of the Incubyte Assessment.
