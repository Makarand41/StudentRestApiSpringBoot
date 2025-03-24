#Student Management System with CRUD
This is a simple Spring Boot CRUD (Create, Read, Update, Delete) application for managing students. It provides RESTful APIs to perform operations on a student database.

##Features
-Add a new student
-Retrieve a student by ID
-Retrieve all students
-Update student details
-Delete a student by ID
-Delete all students
-Count total students
-Check if a student exists by ID

##Technologies Used
-Java 17+
-Spring Boot
 -MySQL
-Lombok
-Postman (for testing APIs)

##API Endpoints

1 Create a Student

Method: POST
URL: http://localhost:8080/api/students
```
{
  "firstName": "John",
  "lastName": "Doe"
}
```

2 Get Student by ID

Method: GET
URL: http://localhost:8080/api/students/{id}

3 Get All Students

Method: GET
URL: http://localhost:8080/api/students


4 Update Student

Method: PUT
URL: http://localhost:8080/api/students/{id}

```
{
  "firstName": "UpdatedName",
  "lastName": "UpdatedLastName"
}
```

5 Delete Student by ID

Method: DELETE
URL: http://localhost:8080/api/students/{id}

6 Delete All Students

Method: DELETE
URL: http://localhost:8080/api/students

7 Count Students

Method: GET
URL: http://localhost:8080/api/students/count

8 Check if Student Exists

Method: GET
URL: http://localhost:8080/api/students/exists/{id}
