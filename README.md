### NAME: SURYA P <br>
### REG NO: 212224230280 <br> 
### Date: 17/03/2026

## EX. No. 5 : Build A DataBase Server

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

1. Create a Security Group for RDS
2. Create a DB Subnet Group
3. Launch an RDS MySQL DB Instance
4. Configure Connectivity and Security
5. Connect Web App to Database and Test

---

## Output Screenshots (Attach 3)

### Screenshot 1: EC2 Instance for Database Server

<img width="1256" height="552" alt="image" src="https://github.com/user-attachments/assets/01ded68c-f0f6-49cf-a0c4-974dc0ccd937" />


---

### Screenshot 2: Database Service Running

<img width="1254" height="392" alt="image" src="https://github.com/user-attachments/assets/73797216-d181-44e7-a01c-c314ea4c5cb9" />

---

### Screenshot 3: Sample Database and Table

<img width="1113" height="420" alt="image" src="https://github.com/user-attachments/assets/14891352-d8fa-476d-a085-106c93a6ca32" />


---

## Result

This experiment demonstrated how to build a database server in AWS using an EC2 instance. By installing and configuring a DBMS, creating a sample database, and testing connectivity, the fundamentals of hosting and managing a cloud-based database server were understood.
