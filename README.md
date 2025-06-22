# BlinkCart - Online Retail Store Management System

## 📌 Project Overview
**BlinkCart** is an end-to-end **Online Retail Store Management System** designed for managing the backend operations and customer interface of an e-commerce platform. It was developed as a course project for **CSE202: Fundamentals of Database Management Systems** and emphasizes strong database design, data consistency, and functional integration between stakeholders.

## 💡 Concept & Purpose
BlinkCart bridges the gap between a traditional e-commerce frontend and robust database-driven backend. The platform ensures secure transactions, seamless user interactions, and scalable backend logic while simulating a real-world online retail environment. It caters to **customers**, **admins**, **suppliers**, and **delivery agents**, making it a multi-role management system.

## 🎯 Objectives
- Provide a user-friendly platform for shopping and order placement.
- Empower administrators to manage inventory, products, and analytics.
- Enable suppliers to monitor product listings and availability.
- Allow delivery agents to manage orders and update statuses.
- Maintain data integrity, security, and high system performance.

## 🧠 Core Features
### 👥 Customer Features
- Signup/Login with password encryption
- Product browsing and search
- Add to cart, update quantities
- Order placement and payment
- View past orders, order tracking
- Submit product reviews
- Chat support and account management

### 🛠️ Admin Features
- Add/Modify/Delete Products
- Inventory management
- Order processing
- Customer analytics
- Apply discounts
- Manage users and view transaction history

### 📦 Supplier Features
- Manage product details and inventory
- Apply special deals/combos
- View real-time sales statistics

### 🚚 Delivery Agent Features
- View assigned deliveries
- Mark availability
- Access customer feedback

## 🧱 Entities and Schema Overview
- **Admin:** AdminID, Name, Email, Password
- **Customer:** Username, Password, Name, Email, Address, Mobile
- **Supplier:** SupplierID, Name, Contact, Address, Email
- **Product:** ProductID, Name, Description, Price, Quantity, SupplierID
- **Order:** OrderID, CustomerID, DeliveryAgentID, OrderDate, Status, TotalAmount
- **Payment:** CustomerID, OrderID, Method, Amount, Date
- **Review:** Product and Delivery reviews with ratings/comments
- **Cart, Order Details, Login Attempts, etc.**

## 🔐 Security & Constraints
- Password encryption for all users
- Account lockout after 3 failed login attempts
- Referential and entity integrity across all relationships
- Price/Quantity range validations
- Realistic delivery timelines

## ⚙️ Tech Stack
- **Frontend:** HTML, CSS, JavaScript, React (planned)
- **Backend:** Python with Flask or Django
- **Database:** MySQL
- **Deployment:** (Planned) AWS

## 🧪 Implementation Milestones
- ✅ Conceptual & Relational DB Design
- ✅ Database creation with constraints and sample data
- ✅ SQL queries and Triggers
- ✅ Transaction design (with conflict scenarios)
- 🛠️ Future: Full-stack integration and deployment

## 🔁 Sample SQL Components
- Tables: Customers, Suppliers, Products, Orders, Payments, Admins
- Triggers:
  - Lock user after 3 failed logins
  - Auto-create cart for new user
  - Default payment entry for new users
- Transaction examples:
  - Handling price/quantity updates
  - Simultaneous product ordering
  - Admin/customer analytics

## 🧭 Future Plans
- Convert to a production-ready full-stack web app
- Host on cloud (AWS, Vercel, etc.)
- Add ML for recommendation system
- Improve UI/UX using React + Tailwind


## 🧑‍💻 Authors
- **Syed Yasir Ali** (2022530)
- **Sahil** (2022427)

## 🏫 Course
**CSE202: Fundamentals of Database Management Systems**

## 📅 Timeline
- Jan 2024 to April 2024

---
> "BlinkCart: Making online retail simpler, smarter, and secure."
