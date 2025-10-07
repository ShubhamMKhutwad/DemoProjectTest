
Spring Boot REST API project performing CRUD operations on a Person entity with name and age. Uses Spring Data JPA with MySql Database . Supports create, read, update, delete operations via REST endpoints and is easily testable with Postman.
http://localhost:8080/api/person/update/1  //update API endpoint(PUT)
http://localhost:8080/api/person/delete/1  //delete API endpoint (POST)
http://localhost:8080/api/person/all  //get All (GET)
http://localhost:8080/api/person/save  { "name"  :"shubham" , "age":"20" } //(BODY) (POST)  --raw select JSON
