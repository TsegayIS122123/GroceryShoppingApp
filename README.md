🛒 Grocery Shopping and Door-to-Door Delivery System 
A comprehensive Java-based application designed to simplify grocery shopping and delivery, empowering customers with digital payments and efficient doorstep service for urban and rural communities alike. 🌟 This system revolutionizes access to groceries, ensuring convenience and reliability for all. 🚚

🌟 Overview
In today’s fast-paced world, convenience is essential. This platform eliminates the need for physical store visits by integrating customer interfaces, supermarket inventory management, agent coordination, and digital wallet payments. Ideal for busy professionals, elderly individuals, and remote areas, it’s a practical solution inspired by services like Jumia Food and Glovo. 🌍

🎯 Objectives

Enable online grocery ordering with doorstep delivery. 🛍️
Provide secure digital wallet payments and real-time delivery tracking. 💳
Allow supermarkets to manage product catalogs and orders efficiently. 🏪
Facilitate agent pickup and delivery operations. 🚚
Ensure data security with robust authentication. 🔒
Practice database concepts like stored procedures and triggers. 💾


🚀 Features
Customer Features

Registration and login with name, phone, address, and pickup location. 📝
Digital wallet creation with manual balance input. 💰
Browse products, add to cart, and place orders from multiple supermarkets. 🛒
Pay via digital wallet with dynamic delivery fees. 💸
Track orders in real-time with status updates. 📍
View and confirm invoices upon delivery. 📋

Agent Features

View and manage assigned orders. 📦
Communicate with supermarkets for pickup. 📞
Deliver orders and upload invoices. 🚚

Supermarket Owner Features

Manage products (add, edit, delete, update availability). 🛠️
Process and track incoming orders. 📊
Coordinate with agents. 🤝

System-Wide Features

Secure user authentication with username and password. 🔐
Real-time updates for orders and wallets. ⏰
Automated invoice generation and storage. 📂


🛠️ Technologies

Java (Swing GUI for user interface) 🖥️
SQL Server (for database management) 💾


📊 Database Design

Customer: ID, Name, Phone, Address, Wallet Balance
Supermarket: ID, Name, Location, Product Catalog
Product: ID, Name, Category, Price, Stock, Supermarket ID
Agent: ID, Name, Phone, Current Orders
Order: ID, Customer ID, Product List, Supermarkets Visited, Total Price, Delivery Fee, Status
Invoice: Order ID, Agent ID, Supermarket IDs, Items, Total, Timestamp


📦 Installation

Clone the repository:  git clone https://github.com/TsegayIS122123/GroceryShoppingApp.git


Set up SQL Server and create the database with the provided schema.
Import the project into a Java IDE (e.g., IntelliJ or Eclipse).
Configure the database connection in the source code.
Run the main .java file to launch the application.


🚦 Usage

Register as a customer, agent, or supermarket owner.
Navigate the Swing GUI to explore features like ordering, payment, and tracking.
Follow on-screen prompts for a smooth experience.


📑 API Documentation

N/A (This is a desktop application; refer to the GUI for functionality details).


📜 License

This project is licensed under the MIT License – see the LICENSE file for details. 📝


🤝 Contributing

Contributions are welcome! Fork the repository, submit issues, or create pull requests to improve the project.
Let’s enhance this solution together! 🌱


📬 Contact

GitHub: TsegayIS122123
Email: tsegayassefa27@gmail.com
LinkedIn: linkedin.com/in/tsegay-assefa-95a397336
Portfolio: tsegayassefa.github.io
