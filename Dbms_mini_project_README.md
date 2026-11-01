# 📚 Library Management System

### DBMS Mini Project | MySQL Workbench

A simple Library Management System built using **MySQL Workbench** to demonstrate the practical implementation of Database Management System concepts through SQL.

## 📌 About the Project

The Library Management System is designed to store and manage basic library information. It maintains student records, book details, and information about books issued and returned by students.

The project uses SQL queries to organize data, check book availability, and retrieve information from multiple related tables.

## 🎯 Project Objectives

- Maintain student records in a database.
- Store and organize information about library books.
- Record book issuing and returning activities.
- Check the availability of books.
- Establish relationships between database tables.
- Practice SQL queries and database operations.

## 🛠️ Tools and Technologies

- **MySQL** – Database management system.
- **MySQL Workbench** – Database development and query execution.
- **SQL** – Used to create, modify, and retrieve database records.
- **GitHub** – Used to store and manage project files.

## 🗄️ Database Design

**Database Name:** `LibraryDB`

The database consists of three main tables:

| Table Name | Description                                                  |
| ---------- | ------------------------------------------------------------ |
| Students   | Contains student details and contact information.            |
| Books      | Maintains book names, authors, publishers, and availability. |
| Book_Issue | Records book issue dates, return dates, and status.          |

## 💻 DBMS Concepts Practiced

The following concepts are implemented in this project:

- Creating databases and tables.
- Primary Key and Foreign Key relationships.
- SQL constraints.
- INSERT and UPDATE operations.
- SELECT queries for retrieving records.
- INNER JOIN and LEFT JOIN.
- Aggregate functions such as COUNT() and SUM().
- Transaction management.

## 📂 Repository Structure

```text
Library-Management-System/
│
├── LibraryDB.sql
│
├── Screenshots/
│   ├── Database_Creation.png
│   ├── Table_Creation.png
│   ├── Student_Records.png
│   ├── Book_Records.png
│   └── Query_Outputs.png
│
├── Library_Project_Report
│
└── README.md
```

## ▶️ Steps to Run the Project

Follow these steps to execute the project on your system:

1. Install MySQL Server and MySQL Workbench.
2. Open MySQL Workbench and establish a connection to your MySQL Server.
3. Download or clone this GitHub repository.
4. Locate and open the `LibraryDB.sql` file in MySQL Workbench.
5. Execute the SQL commands in the given sequence.
6. Run the SELECT queries to check the inserted records and database outputs.

**Note:** The SQL script creates the database and inserts sample data. If the database already exists, reset it appropriately before executing the script again.

## 📸 Project Screenshots

The repository includes screenshots showing different stages of the project, such as:

- Database creation.
- Table structure and relationships.
- Student records.
- Book information.
- SQL query execution and results.

These screenshots provide a visual representation of the database implementation.

## 🚀 Future Improvements

The project can be extended by introducing additional features, including:

- A web-based library management interface.
- Separate login facilities for students and librarians.
- Online book reservation functionality.
- Automatic notifications for book return dates.
- Fine calculation for overdue books.
- Database support for multiple campus libraries.

## 📝 Conclusion

This mini project provides practical experience in designing and working with a relational database using MySQL Workbench.

It demonstrates how SQL can be used to store, organize, update, and retrieve library information. It also helps in understanding database relationships, constraints, joins, and other important DBMS concepts.

## 👨‍💻 Project Information

| Detail           | Information                |
| ---------------- | -------------------------- |
| Project Title    | Library Management System  |
| Subject          | Database Management System |
| Project Type     | Individual Mini Project    |
| Database         | MySQL                      |
| Academic Session | 2026–2027                  |
| Student Name     | Akshit Kohli               |
| Roll Number      | 2419171                    |
| Class            | CSE A                      |

---
