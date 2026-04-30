# 🛒 FusionStore – E-Commerce Web Application

> A frontend e-commerce system built using HTML, CSS, and JavaScript that simulates a real online shopping experience including product browsing, cart management, orders, and invoice generation.

---

## 📌 Project Overview

FusionStore is a **frontend-only e-commerce simulation system** developed for educational purposes.  
The system demonstrates how real e-commerce platforms work by implementing core features such as product display, shopping cart, checkout process, order tracking, and invoice generation.

All data is handled using JavaScript in-memory arrays without any backend or database.

---

## 🎯 Project Objectives

- Build a fully functional e-commerce frontend system
- Simulate real shopping experience (browse → cart → checkout → order)
- Practice JavaScript DOM manipulation and state management
- Implement dynamic UI updates without frameworks
- Demonstrate understanding of system design concepts (UML)

---

## 🧠 System Type

```text
Frontend Web Application (No Backend)
```

---

## 🛠️ Technologies Used

```text
HTML5      → Structure
CSS3       → Styling & UI Design
JavaScript → Logic & Interactivity
```

Additional:
- Google Fonts (Inter)
- Font Awesome Icons
- External product images (Unsplash)

---

## 🏗️ System Architecture

```text
User Interface (HTML + CSS)
        ↓
JavaScript Logic Layer
        ↓
In-Memory Data Storage
(products, cart, users, orders)
```

No database or server is used.

---

## 🧩 Core Features

### 🛍️ Product System
- Display products dynamically
- Product details:
  - Name, image, category
  - Price and old price
  - Discount badge
  - Rating system
  - Reviews count
  - Sold count
- Add to cart functionality

---

### 🛒 Shopping Cart
- Add products to cart
- Increase / decrease quantity
- Remove items
- Automatic total calculation:
  - Subtotal
  - Tax (10%)
  - Grand total

---

### 👤 User System (Frontend Only)
- User registration
- User login
- Logout functionality
- Session stored in memory
- Restriction for cart & checkout if not logged in

---

### 📦 Order System
- Create order after checkout
- Store order history
- Order details:
  - Order ID
  - Date
  - Items
  - Total price
  - Status (Processing / Cancelled)
- Track order
- Cancel order (if processing)

---

### 🧾 Invoice System
- Auto-generated invoice after checkout
- Includes:
  - Order ID
  - Customer name
  - Items list
  - Total amount
- Print invoice feature

---

## 📊 UML System Design (Corrected)

### 🧭 Use Case Diagram
**Actor: User**
- Browse Products
- Add to Cart
- Update Cart
- Remove from Cart
- Checkout
- Login / Register / Logout
- View Orders
- Track Order
- Cancel Order

---

### 🧱 Class Diagram

```text
Product
Cart
CartItem
User
Order
Invoice
```

### Relationships:
- User → Cart
- User → Order
- Cart → CartItem
- Order → CartItem
- Order → Invoice

---

### 🔄 Sequence Diagram (Checkout Process)

1. User clicks checkout  
2. System retrieves cart items  
3. Order is created  
4. Invoice is generated  
5. Cart is cleared  
6. Order is stored  
7. Confirmation shown  

---

### 🗄️ ERD (Entity Relationship Diagram)

- Customer (1) → Cart (1)
- Cart (1) → CartItem (*)
- CartItem (*) → Product (1)
- Customer (1) → Order (*)
- Order (1) → OrderItem (*)
- Order (1) → Invoice (1)

---

## 💻 JavaScript Core Functions

- `renderProducts()` → Display products
- `addToCart()` → Add item to cart
- `renderCart()` → Update cart UI
- `checkout()` → Create order
- `renderOrders()` → Show orders
- `login()` → User authentication
- `register()` → Create account
- `logout()` → End session

---

## ⚙️ Data Structure

```javascript
products = []
cart = []
users = []
orders = []
```

All data is stored temporarily in memory.

---

## ⚠️ Limitations

- No backend server
- No database storage
- Data resets on refresh
- Payment system is simulated only

---

## 🚀 Future Improvements

- Backend integration (Node.js / Firebase)
- Database (MongoDB / MySQL)
- Real authentication system
- Payment gateway integration (Stripe / PayPal)
- Admin dashboard
- Search and filtering system
- Wishlist feature

---

## 📌 Project Summary

FusionStore demonstrates a complete e-commerce workflow using only frontend technologies.  
It successfully simulates real-world shopping systems including product browsing, cart management, order processing, and invoice generation.

---

## 👨‍💻 Author

FusionStore Project – Frontend Development Practice  
Built for educational and portfolio purposes.
