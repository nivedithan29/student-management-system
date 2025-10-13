##  Student Management System

A simple **Spring Boot web application** for managing student records.  
You can **add**, **update**, **delete**, and **view** students using a clean web interface.

---

##  Features

- Add new student information  
- Update existing student details  
- Delete student records  
- View list of all students  
- Fully connected with MySQL database  
- User-friendly interface with Bootstrap  

---

##  Technologies Used

- Java  
- Spring Boot  
- Spring MVC  
- Spring Data JPA  
- MySQL
- Thymeleaf
- Maven
- Eclipse IDE / Spring Tool Suite (STS)

---
## Project Structure

student-management-system/
├── src/
│   ├── main/
│   │   ├── java/
│   │   │   └── net/
│   │   │       └── javaguides/
│   │   │           └── sms/
│   │   │               ├── StudentManagementSystemApplication.java   # Main Spring Boot application
│   │   │               │
│   │   │               ├── controller/
│   │   │               │   └── StudentController.java                # Handles web requests and routing
│   │   │               │
│   │   │               ├── entity/
│   │   │               │   └── Student.java                          # Student entity class
│   │   │               │
│   │   │               ├── repository/
│   │   │               │   └── StudentRepository.java                # JPA repository interface
│   │   │               │
│   │   │               └── service/
│   │   │                   ├── StudentService.java                   # Service interface
│   │   │                   └── StudentServiceImpl.java               # Service implementation class
│   │   │
│   │   ├── resources/
│   │   │   ├── static/                                               # Static resources (CSS, JS, images)
│   │   │   ├── templates/                                            # Thymeleaf HTML pages
│   │   │   │   ├── index.html                                        # Homepage – list all students
│   │   │   │   ├── new_student.html                                  # Add student page
│   │   │   │   └── update_student.html                               # Update student details page
│   │   │   ├── application.properties                                # Database configuration
│   │   │   └── banner.txt                                            # Optional Spring Boot banner
│   │
│   └── test/                                                         # Unit tests (if any)
│
├── pom.xml                                                           # Maven dependencies
└── README.md                                                         # Project documentation

---

## Setup Instructions

1️⃣ Clone the Repository 

   git clone https://github.com/nivedithan29/student-management-system.git

2️⃣ Open the Project

- Open in Eclipse or Spring Tool Suite (STS)
- Wait for Maven dependencies to download automatically

3️⃣ Configure the Database

- Create a MySQL database named sms
- Update your application.properties file as below:


```properties
spring.datasource.url=jdbc:mysql://localhost:3306/sms
spring.datasource.username=root
spring.datasource.password=your_password
spring.jpa.hibernate.ddl-auto=update
```

4️⃣ Run the Application
Run the main class: StudentManagementSystemApplication.java

Open your browser and go to:
'''👉 http://localhost:8080/students '''

---



