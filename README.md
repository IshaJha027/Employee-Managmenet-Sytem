# Employee-Managmenet-Sytem
Employee Management System
This project is an Employee Management System built using Spring, Hibernate, and Java. It provides functionalities for employee registration, login, and a welcome page with personalized messages.

Technologies Used
Spring Framework
Hibernate
Java (Java 11 or Java 7)
MySQL
Tomcat
JSP (JavaServer Pages)
JDBC (Java Database Connectivity)
Development Tools
You can use either IntelliJ IDEA or Eclipse IDE for development.

Setup Instructions
Clone the repository to your local machine.

bash
Copy code
git clone https://github.com/your-username/employee-management-system.git
Import the project into your preferred IDE (IntelliJ IDEA or Eclipse).

Configure MySQL database:

Install MySQL if not already installed.
Create a new database named employee_management.
Update the database configurations in application.properties located at src/main/resources.
Ensure you have Tomcat installed on your system. If not, download and install it.

Run the project on the Tomcat server.

Access the application through your web browser at http://localhost:8080.

Project Structure
src/main/java: Contains Java source files.
com.example.controller: Contains controller classes for handling HTTP requests.
com.example.model: Contains entity classes representing database tables.
com.example.repository: Contains repository classes for database operations.
com.example.service: Contains service classes for business logic.
src/main/resources: Contains application properties, Hibernate configurations, and SQL scripts.
src/main/webapp: Contains JSP files and static resources (CSS, JavaScript).
Functionality
Employee Registration Page:

Allows users to register with fields such as Name, Date of Birth, Gender, Address, City, State, Login ID, and Password.
Login Page:

Allows registered users to log in to their accounts.
Welcome Page:

Displays a welcome message to the logged-in user with their name.
