# First-Java-CRUD

CRUD application for managing customers, written in Java with Spring Boot, Spring Data JPA, H2 database and Vaadin.
Made with the help of the guide [Creating CRUD UI with Vaadin](https://spring.io/guides/gs/crud-with-vaadin/).

Each customer has a first name, last name and email.

## How to run

Java 21 is required.

```
mvnw.cmd spring-boot:run
```

On Linux or macOS use `./mvnw spring-boot:run`.

The application starts on http://localhost:8080.

## What it can do

- show all customers in a table
- search customers by last name
- create, edit and delete customers (use the "Add customer" button to create a new one)

## Files

- `Customer.java` - entity stored in the database
- `CustomerRepository.java` - data access
- `MainView.java` - main page
- `CustomerEditor.java` - form for editing a customer
- `CrudwithvaadinApplication.java` - starts the application and adds test data

Screenshots: [doc](doc)
