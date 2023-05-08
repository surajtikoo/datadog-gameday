# Spring Boot REST Microservice 

## REST APIs implemented using Spring Boot Multi Module Maven Project

### Description
This is a sample employee application which uses Spring Data JPA to interact with H2 database.

#### Used technology
* Spring boot
* Maven
* H2 Database
* 
### Getting Started
How to Run
Build the project by running mvn clean package inside todo-app-parent module
Once successfully built, run the service by using the following command:


#### Prerequisites
* AWS Account
    * Cloud9 Environment
    * Java 8 or higher version

#### REST APIs Endpoints
### Create a New Employee
```
POST /todo
Accept: application/json
Content-Type: application/json

{
"title" : "Spring Boot",
"description" : "Setup spring boot application",
}

```

| Application Properties Variables Variable | Value                               |
|-------------------------------------------|-------------------------------------|
| management.endpoints.web.exposure.include | health                              |
| logging.level.org.springframework         | DEBUG                               |
| logging.level.org.hibernate.SQL           | DEBUG                               |
| server.port                               | 8085                                |

3. Make sure the AWS Lambda Function has **access to all necessary ressources** in AWS, e.g. CloudWatch
4. The interface is good to go!


#### Swagger End point to directly test the application with all the endpoints. 
http://localhost:8085/employees/swagger-ui.html

if you don't have access to the swagger via the brower you can use the linux commands.

### Commands to execute the API's using the linux/Unix Machine

1. Get the list of ALl employees
```
curl -X GET "http://localhost:8085/employees/" -H "accept: */*"
```
2. Add an employee to the Database
```
curl -X POST "http://localhost:8085/employees/" -H "accept: */*" -H "Content-Type: application/json" -d "{\"employeeId\":0,\"employeeFirstName\":\"string\",\"employeeLastName\":\"string\",\"employeeEmailId\":\"string\"}"
```
3. Update an update to the Database
```
curl -X PUT "http://localhost:8085/employees/101" -H "accept: */*" -H "Content-Type: application/json" -d "{\"employeeId\":0,\"employeeFirstName\":\"string\",\"employeeLastName\":\"string\",\"employeeEmailId\":\"string\"}"
```
4. Delete an employee from the Database
```
curl -X DELETE "http://localhost:8085/employees/101" -H "accept: */*"

```






#### Error Code
This interface has various Error Codes
1. 200 **Created Successfully**
2. 201 **Content Created Successfully**
3. 204 **Content Updated Successfully**
3. 404 **Url not found **.
4. 500 **Internal Server Error.There must be some issue while processing**

### Contact
Developed by Suraj Tikoo
For futher questions please contact suraj.tikoo@accenture.com
