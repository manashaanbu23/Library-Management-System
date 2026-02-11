📚 Library Management System (Java Servlet & JDBC)
A simple Library Management System developed using Java Servlets, JDBC, HTML, and Oracle Database. This project allows users to add books, view books, and manage author details through a web-based interface.

🚀 Features
Add new books
View available books
Author management
Input validation
JDBC database connectivity
MVC architecture (Servlets, DAO, Beans)
🛠️ Tech Stack
Layer	Technology
Backend	Java, Servlets
Frontend	HTML
Database	Oracle Database
Server	Apache Tomcat 9
IDE	Eclipse
Driver	ojdbc17.jar
📁 Project Structure
LibraryManagement/
│
├── src/
│   └── main/
│       ├── java/
│       │   └── com/
│       │       └── wipro/
│       │           └── book/
│       │               ├── bean/
│       │               │   ├── AuthorBean.java
│       │               │   └── BookBean.java
│       │               ├── dao/
│       │               │   ├── AuthorDAO.java
│       │               │   └── BookDAO.java
│       │               ├── service/
│       │               │   └── Administrator.java
│       │               ├── servlets/
│       │               │   ├── MainServlet.java
│       │               │   └── ViewServlet.java
│       │               └── util/
│       │                   └── DBUtil.java
│       └── webapp/
│           ├── AddBook.html
│           ├── ViewBook.html
│           ├── Menu.html
│           ├── Invalid.html
│           ├── Failure.html
│           └── WEB-INF/
│               └── lib/
│                   └── ojdbc17.jar
▶️ How to Run the Project
Clone the repository

git clone https://github.com/your-username/LibraryManagement.git
Import the project into Eclipse as a Dynamic Web Project

Add Apache Tomcat 9 server

Add ojdbc17.jar inside WEB-INF/lib

Execute SQL queries in Oracle Database

Start the Tomcat server

Open the browser and navigate to:

http://localhost:8080/LibraryManagement/Menu.html
🖼️ Project Screenshots
<img width="1257" height="522" alt="image" src="https://github.com/user-attachments/assets/f320d8fa-bea5-4800-9356-cb5a228c254b" />
<img width="1281" height="696" alt="image" src="https://github.com/user-attachments/assets/b569464a-d8fd-4ff0-b2cd-0692e3665aff" />
<img width="1413" height="603" alt="image" src="https://github.com/user-attachments/assets/81da9559-0fc9-417b-8b90-af25663c18c9" />
<img width="1310" height="537" alt="image" src="https://github.com/user-attachments/assets/2026a6e5-a8e9-4e0f-b506-94b7a646735a" />

Screenshot 1 Screenshot 2 Screenshot 3 Screenshot 4
❌ Error Handling Pages
Invalid.html – Incorrect input
Failure.html – Operation failure
👩‍💻 Author
MANASHA A Java | JDBC | Servlets
