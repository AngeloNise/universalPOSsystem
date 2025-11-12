# 💼 POS: Web-Based Point of Sales System  

**🏢 Internship Project – Inspiring PG Inc, Taguig City**  
**💻 Full Stack Web Developer (Intern)** | *February – May 2025*  

---

## 📘 Project Overview  

The **POS (Point of Sales)** System is a **full-stack web application** developed during my internship at **Inspiring PG Inc**.  
It was designed to **streamline retail operations** by managing sales transactions, inventory tracking, supplier data, and real-time business analytics.  

Developed using **React.js (frontend)** and **Spring Boot (backend)**, this project showcases the integration of **modular microservices**, **RESTful API design**, and **dynamic dashboards** for data-driven insights.  

> ⚠️ **Note:** This repository contains only the **non-sensitive components** of the project.  
> Sensitive folders (such as credentials, private APIs, configuration files, and deployment assets) have been **removed** to comply with company and data security policies.  

---

## 🎯 Key Features  

| Feature | Description |
|----------|-------------|
| 🛒 **Sales Module** | Manage customer transactions and record real-time sales data |
| 📦 **Inventory Module** | Track stock levels, product details, and automatic updates after sales |
| 🚚 **Supplier Module** | Handle supplier profiles with file upload, image preview, and Excel import/export |
| 📊 **Dashboard Module** | Display real-time metrics such as profit, capital, and inventory analytics using dynamic charts |
| 🧩 **Microservices Architecture** | Independent modules (product, sales, inventory, supplier, dashboard) for scalability and maintainability |
| 🔗 **RESTful APIs** | Enable seamless communication between frontend and backend services |
| 💾 **MySQL Integration** | Optimized database schemas for complex business queries and reporting |

---

## 🛠 Tech Stack  

| Layer | Technology |
|-------|-------------|
| 🎨 **Frontend** | React.js, HTML, CSS, JavaScript |
| ⚙️ **Backend** | Spring Boot (Java) |
| 🗄️ **Database** | MySQL |
| 🔧 **Version Control** | Git & GitHub |
| 🧱 **Architecture** | Microservices with RESTful APIs |
| ☁️ **Deployment** | Internal test server (Inspiring PG Inc) |

---

## 🧪 Project Goals  

✅ Automate sales and inventory processes to improve operational efficiency  
📈 Provide real-time analytics for informed decision-making  
💡 Demonstrate full-stack web development using modern frameworks  
🔒 Ensure scalability, modularity, and secure data handling in a corporate setup  

---

## 🎨 System Design Overview  

```plaintext
Frontend (React.js)
│
├── Login / Authentication
├── Sales Module
├── Inventory Module
├── Supplier Module
└── Dashboard (Charts & Metrics)

Backend (Spring Boot - Microservices)
│
├── Product Service
├── Sales Service
├── Inventory Service
├── Supplier Service
└── Dashboard Service

Database (MySQL)
│
└── Tables: products, sales, inventory, suppliers, users, etc
