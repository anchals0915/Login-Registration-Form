# Login and Registration Form with Servlet and MySQL Database

This repository provides a simple example of a login and registration form using Java Servlets and MySQL. The application allows users to register, securely store their details in a MySQL database, and subsequently log in using their credentials. This is an ideal starting point for anyone looking to learn about basic authentication in Java web applications using Servlets and MySQL.

## Features

- **User Registration**: Create a new account with username, email, and password.
- **User Login**: Authenticate with username and password.
- **MySQL Integration**: Store and retrieve user data using MySQL.

## Technologies Used

- Java Servlets
- MySQL Database
- HTML & CSS
- JDBC (Java Database Connectivity)

## Getting Started

### Prerequisites

- Java Development Kit (JDK) 8 or above
- Apache Tomcat (or any other Java EE server)
- MySQL Database Server
- MySQL Connector- J

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/LoginRegistrationServlet.git
   cd Login-Registration-Form
   ```


2. Import the project into your preferred IDE (e.g., Eclipse or IntelliJ IDEA)
3. Set up the MySQL database:
  +  Create a new database (e.g., userdb).
  +  Import the SQL file userdb.sql from this repository to create the required tables.
6. Update the database configuration in DBConnection.java:
```
String url = "jdbc:mysql://localhost:3306/userdb";
String username = "your_db_username";
String password = "your_db_password";
```
5. Deploy the application to your server and access it at
   ```
    http://localhost:8080/LoginRegistrationServlet.
   ```

## Usage

1. Open the application in your web browser.
2. Register a new account by providing a username, email, and password.
3. Log in with your registered credentials to access the secure area.

## Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request with any improvements or fixes.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.

