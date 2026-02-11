📚 Library Management System (Java Servlet & JDBC)

A simple Library Management System developed using Java Servlets, JDBC, HTML, and Oracle Database.
This project allows users to add books, view books, and manage author details through a web-based interface.

🚀 Features

➕ Add new books

📖 View available books

👩‍💼 Author management

✅ Input validation

🔗 JDBC database connectivity

🧱 MVC architecture (Servlets, DAO, Beans)

🛠️ Tech Stack
Layer	Technology
Backend	Java, Servlets
Frontend	HTML
Database	Oracle Database
Server	Apache Tomcat 9
IDE	Eclipse
Driver	ojdbc17.jar

## 📁 Project Structure

```
LibraryManagement/
│
├── src/
│   └── main/
│       ├── java/
│       │   └── com/wipro/book/
│       │       ├── bean/
│       │       │   ├── AuthorBean.java
│       │       │   └── BookBean.java
│       │       ├── dao/
│       │       │   ├── AuthorDAO.java
│       │       │   └── BookDAO.java
│       │       ├── service/
│       │       │   └── Administrator.java
│       │       ├── servlets/
│       │       │   ├── MainServlet.java
│       │       │   └── ViewServlet.java
│       │       └── util/
│       │           └── DBUtil.java
│
└── webapp/
    ├── AddBook.html
    ├── ViewBook.html
    ├── Menu.html
    ├── Invalid.html
    ├── Failure.html
    └── WEB-INF/
        └── lib/
            └── ojdbc17.jar
```


▶️ How to Run the Project

1️⃣ Clone the repository

git clone https://github.com/your-username/LibraryManagement.git


2️⃣ Import project into Eclipse

Import → Existing Projects → Select Folder

3️⃣ Configure Server
Add Apache Tomcat 9

4️⃣ Add JDBC Driver
Place ojdbc17.jar inside:

WEB-INF/lib


5️⃣ Setup Database
Run required SQL tables in Oracle Database

6️⃣ Start Server
Run project on Tomcat

7️⃣ Open in Browser

http://localhost:8080/LibraryManagement/Menu.html

🖼️ Screenshots

<img src="https://github.com/user-attachments/assets/f320d8fa-bea5-4800-9356-cb5a228c254b" width="800"/> <br><br>
<img src="https://github.com/user-attachments/assets/b569464a-d8fd-4ff0-b2cd-0692e3665aff" width="800"/> <br><br> 
<img src="https://github.com/user-attachments/assets/81da9559-0fc9-417b-8b90-af25663c18c9" width="800"/> <br><br> 
<img src="https://github.com/user-attachments/assets/2026a6e5-a8e9-4e0f-b506-94b7a646735a" width="800"/>



❌ Error Handling Pages

Invalid.html → shown for incorrect input

Failure.html → shown when operation fails

👩‍💻 Author

Manasha
Java | JDBC | Servlets Developer
