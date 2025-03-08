# 🛍️ Sports Club System
🚀 **A full-featured sports club eCommerce system built with React.js, Spring Boot, MySQL, and AWS.**

![Sports Club System](https://via.placeholder.com/1200x600.png?text=Sports+Club+System)

---

## **📌 Project Overview**
The **Sports Club System** is a **full-stack web application** that allows users to browse, purchase, and manage sports products while providing an **admin panel** for inventory and order management. It is deployed on **AWS Cloud** and supports **secure payments via PayPal & Cash on Delivery (COD).**

---

## **🛠️ Tech Stack**
| Technology  | Description |
|-------------|------------|
| **Frontend** | React.js, Redux, Bootstrap |
| **Backend** | Spring Boot, REST APIs |
| **Database** | MySQL |
| **Cloud** | AWS S3 (for storing images), AWS EC2 |
| **Tools** | Postman, GitHub, IntelliJ IDEA, VS Code |
| **Authentication** | JWT (JSON Web Token) |

---

## **✨ Key Features**  
### **👥 User Features**  
✅ **User Authentication:** Sign up, log in, manage profiles  
✅ **Product Browsing:** View products by category  
✅ **Shopping Cart:** Add products to cart  
✅ **Checkout & Payment:** Pay via **PayPal** or **Cash on Delivery (COD)**  
✅ **Order History:** View and track previous orders  

### **🛠️ Admin Features**  
✅ **Product Management:** Add/edit/delete products  
✅ **Category Management:** Organize products by category  
✅ **Order Management:** View & manage customer orders  
✅ **Secure Image Storage:** Uses **AWS S3** for product images  

---

## **🚀 Live Demo**
🔗 **[Deployed on AWS](#)** *(Add your live demo link here if available)*  

---

### 📽️ Project Demo
![Project Demo](https://github.com/pushpak261/sportshub/blob/main/projvideo2_hq.gif)  

---

## **⚡ Getting Started**
### **🔧 Prerequisites**
- Install **Java 17**, **Node.js (v16+)**, and **MySQL**
- Install **Maven** for managing dependencies  

### **🚀 Backend Setup (Spring Boot)**
```bash
# Clone the repository
git clone https://github.com/pushpak261/sports-club-system.git

# Navigate to the backend folder
cd backend

# Build the project
mvn clean install

# Run the application
mvn spring-boot:run
```
_Backend runs at `http://localhost:8080`_  

---

### **🎨 Frontend Setup (React.js)**
```bash
# Navigate to the frontend folder
cd frontend

# Install dependencies
npm install

# Start the React app
npm start
```
_Frontend runs at `http://localhost:3000`_  

---

## **🗄️ Database Configuration**
1️⃣ **Create a MySQL Database:**  
```sql
CREATE DATABASE sports_club_db;
```
2️⃣ **Update `application.properties` (Backend Configuration)**  
```properties
spring.datasource.url=jdbc:mysql://localhost:3306/sports_club_db
spring.datasource.username=root
spring.datasource.password=your_password
```

---

## **📚 API Endpoints (Backend)**
| Method | Endpoint | Description |
|--------|---------|-------------|
| `GET` | `/api/products` | Get all products |
| `GET` | `/api/products/{id}` | Get product by ID |
| `POST` | `/api/orders` | Place an order |
| `GET` | `/api/orders/{userId}` | Get user orders |
| `POST` | `/api/auth/login` | User login |

📌 **Use Postman to test APIs**  

---

## **📌 Deployment (AWS)**  
- **Frontend:** Hosted on AWS S3 (Static Website)  
- **Backend:** Deployed on AWS EC2 instance  
- **Database:** Hosted on AWS RDS (MySQL)  
- **Images:** Stored securely in AWS S3  

---

## **📬 Contact**
🔗 **GitHub:** [pushpak261](https://github.com/pushpak261)  
🔗 **LinkedIn:** [Pushpak Pandharpatte](https://www.linkedin.com/in/pushpak-pandharpatte/)  

---

## **🌟 Show Your Support!**  
If you like this project, please ⭐ **star** this repository and share it! 🚀  
