# Lab 5 – Build a Database Server (AWS)

## Author

* **Name**: SANTHABABU  G
* **Register Number**: 212224040292
* **Date of Submission**: 12-03-2026

---

## Objective

The objective of this experiment is to understand how to deploy and configure a database server in AWS. This lab focuses on launching an EC2 instance, installing a database management system (DBMS), configuring basic database settings, creating a sample database, and validating connectivity to the database server.

---

## Prerequisites

* Basic understanding of cloud computing concepts
* AWS account or AWS Academy Lab access
* An existing VPC and EC2 knowledge (from previous labs)
* Basic knowledge of Linux commands and SQL

---

## Tools Used

* AWS Management Console
* Amazon EC2
* Security Groups
* SSH Client (Terminal / PuTTY)
* MySQL / MariaDB / PostgreSQL (any one)

---

## Tasks Performed

### Task 1: Launch EC2 Instance for Database Server

Launch a new EC2 instance using Amazon Linux 2 AMI. Select an appropriate instance type and configure key pair and security group.

---

### Task 2: Configure Security Group for Database Access

Modify the security group to allow:

* SSH (Port 22) for remote access
* Database port (e.g., MySQL – 3306 or PostgreSQL – 5432)

---

### Task 3: Connect to EC2 Instance

Connect to the EC2 instance using SSH from your local machine.

---

### Task 4: Install Database Server

Install a database server software such as MySQL, MariaDB, or PostgreSQL on the EC2 instance using package manager commands.

---

### Task 5: Start and Configure Database Service

Start the database service and configure basic settings such as root password and user privileges.

---

### Task 6: Create a Sample Database

Create a sample database and a table inside it. Insert a few records into the table.

---

### Task 7: Test Database Connectivity

Test the database server by connecting to it locally or remotely and performing basic SQL queries.

---

## Workflow (Student Explanation)


1.Logged in to AWS and opened Amazon EC2.

2.Launched a new EC2 instance using Amazon Linux 2.

3.Configured the security group to allow SSH (22) and MySQL (3306).

4.Connected to the EC2 instance using SSH.

5.Installed the MySQL database server.

6.Started the MySQL service and set the root password.

7.Created a sample database and table.

8.Tested the database using SQL queries.

---

## Output Screenshots (Attach 3)

### Screenshot 1: EC2 Instance for Database Server

<img width="1919" height="998" alt="Screenshot 2026-03-11 170313" src="https://github.com/user-attachments/assets/90c89fb8-9a59-4614-9f81-6427b43e95b8" />




---

### Screenshot 2: Database Service Running


<img width="1919" height="1021" alt="Screenshot 2026-03-11 172051" src="https://github.com/user-attachments/assets/5faff695-cacd-4070-8307-851c0a60cf23" />


---

### Screenshot 3: Sample Database and Table

<img width="1907" height="1095" alt="Screenshot 2026-03-11 173246" src="https://github.com/user-attachments/assets/f1f91001-09c0-4f82-af65-5c7f755971e1" />



---

## Result

This experiment demonstrated how to build a database server in AWS using an EC2 instance. By installing and configuring a DBMS, creating a sample database, and testing connectivity, the fundamentals of hosting and managing a cloud-based database server were underst
