🛒 E-Commerce Console Application
Java + Hibernate + Maven + MySQL
<p align="center"> <img src="https://img.shields.io/badge/Java-17-orange?logo=openjdk" /> <img src="https://img.shields.io/badge/Hibernate-5.6-59666C?logo=hibernate" /> <img src="https://img.shields.io/badge/Maven-Build%20Tool-C71A36?logo=apachemaven" /> <img src="https://img.shields.io/badge/MySQL-Database-00618A?logo=mysql&logoColor=white" /> <img src="https://img.shields.io/badge/Status-Active-success" /> </p>
✨ Overview

A complete console-based E-Commerce backend system built with:

✔ Java
✔ Hibernate ORM
✔ MySQL
✔ Maven
✔ DAO + Service Layered Architecture

This project supports real-world workflows: user registration → add products → add to cart → place order → complete payment.

🚀 Features
👤 User Module

Register user

View user

📦 Product Module

Add product

View all products

🛒 Cart Module

Add to cart

View cart items

🧾 Order Module

Place order

Auto-calculate amount

💳 Payment Module

UPI / Card / COD

Save payment record

Timestamp tracking

🛠️ Tech Stack
Component	Technology
Language	Java
ORM	Hibernate
Database	MySQL
Build Tool	Maven
Architecture	DAO + Service Pattern

📚 ER Diagram

<img width="488" height="537" alt="Screenshot 2025-11-18 230422" src="https://github.com/user-attachments/assets/105ef33d-affc-4170-8767-c54dcfef7c56" />

📁 Project Structure

<img width="223" height="524" alt="image" src="https://github.com/user-attachments/assets/5ba61cd3-ee6d-4d40-905b-eef38de3e988" />

🖼️ Screenshots Section

📸 Main Menu

<img width="791" height="573" alt="image" src="https://github.com/user-attachments/assets/4b904a9c-f08b-4ef2-9eb0-9884e151ee32" />

<img width="778" height="442" alt="image" src="https://github.com/user-attachments/assets/c32ef0f9-0a4c-424b-b85b-a394822cd254" />

Adding product and viewing Product to the website

<img width="490" height="499" alt="image" src="https://github.com/user-attachments/assets/e813df7e-56aa-4897-880a-b3954c6a41a9" />

🛒 Cart Output

<img width="385" height="238" alt="image" src="https://github.com/user-attachments/assets/674bd9f0-37d5-489d-8c7e-ec718e4204db" />

🛒 Order Output

<img width="246" height="275" alt="image" src="https://github.com/user-attachments/assets/ea6aaec8-c150-4119-ae09-92e58e0864af" />

💳 Payment Success

<img width="367" height="265" alt="image" src="https://github.com/user-attachments/assets/b5d1d4a3-3396-4fb6-9618-a081dde83590" />

After Successful Payment stock is reduced in the Product

<img width="294" height="125" alt="image" src="https://github.com/user-attachments/assets/f499fa03-646b-434f-b1f2-a3616f67a2e1" />

When the product is sold out and it shows out of stock while ordering

 <img width="327" height="244" alt="image" src="https://github.com/user-attachments/assets/db20581e-ba26-4066-a936-cc2990b2d678" />

 <img width="422" height="451" alt="image" src="https://github.com/user-attachments/assets/1a5e3307-96a2-4d5d-b2a2-07ba79910d79" />
 

🛢️ MySQL Configuration
CREATE DATABASE ecommerce_db;


Update hibernate.cfg.xml:

<property name="connection.url">jdbc:mysql://localhost:3306/ecommerce_db</property>
<property name="connection.username">root</property>
<property name="connection.password">your_password</property>

▶️ How to Run
1️⃣ Clone
git clone https://github.com/your-username/ecommerce-hibernate.git
cd ecommerce-hibernate

2️⃣ Build
mvn clean install

3️⃣ Run
java -cp target/ecommerce-hibernate.jar com.ecommerce.Main

🔥 Highlights

CRUD operations across all modules

Many-to-Many & One-to-Many Hibernate relationships

Lazy loading, cascading

Realistic e-commerce workflow

Great portfolio project for Java developers

🙌 Contribution Guidelines

Fork the repository

Create a feature branch

Commit your changes

Open a pull request

Wait for review


💬 Contact

Your Name
Java Developer | Backend Engineer
📧 Email — lalithasiva0301@gmail.com
 
🐙 GitHub — https://github.com/Lalithas03/

⭐ Show Your Support

If you like this project, please ⭐ star the repository — it motivates me to create more projects!

<p align="center"> Thank you for using this project ❤️ </p>





