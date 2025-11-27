# Online Electronic Store  
A simple Java-based eCommerce web application built using Servlets, JSP, and JDBC, designed to simulate an online store where users can browse electronic products, add items to the cart, and place orders.
This project demonstrates core concepts of Java Web Development, MVC architecture, and database integration.

**Features**
  **User Features**
-Browse available electronic products
-View product details
-Add items to shopping cart
-Update/remove items from cart
-Checkout and place an order 

 **Admin Features**
- Add new products    
- View all orders
- manage inventory

 **Technical Features**
- Java Servlets + JSP  
- JDBC for database operations  
- MySQL/PostgreSQL backend  
- MVC-based project structure  
- Session handling for cart management  
- Clean HTML/CSS UI

 **Tech Stack**
| Layer | Technology |
|-------|------------|
| Frontend | HTML, CSS, JSP |
| Backend | Java, Servlets |
| Database | MySQL / PostgreSQL |
| Build Tool | Maven (optional) |
| Server | Apache Tomcat |



 **Project Structure**

Online_Electronic_Store/
│
├── src/
│   └── main/
│       ├── java/
│       │   └── (Servlet files, controllers, DAO, models)
│       └── webapp/
│           ├── index.jsp
│           ├── cart.jsp
│           ├── product.jsp
│           ├── checkout.jsp
│           └── assets/
│               ├── css/
│               └── images/
│
├── build/
├── .classpath
├── .project
└── README.md


## 🔧 **How to Run the Project**
### 1️⃣ Clone the repository  

git clone https://github.com/yourusername/Online-electronic-store.git

### 2️⃣ Import project  
- Open in IntelliJ / Eclipse  
- Configure Tomcat server  

### 3️⃣ Create database  
Run SQL in your DB:

CREATE DATABASE electronic_store;

Import the provided tables (products, users, orders, etc).

### 4️⃣ Update DB credentials in code  

DB_URL  
USERNAME  
PASSWORD


### 5️⃣ Run the server  
- Start Tomcat  
- Open in browser  

http://localhost:8080/Online-electronic-store

---

## 📸 Screenshots  
(Add screenshots here such as homepage, product list, cart page.)

---

## 🚀 Future Enhancements
- Add authentication (Login/Signup)  
- Search & filter products  
- Online payment integration  
- Admin dashboard (React/Chart.js)  
- REST API version of the project  

---

## 👨‍💻 Author  
**Shivam Yadav**  
Full Stack Developer  
