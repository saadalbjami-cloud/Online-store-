# 🛒 FusionStore – Premium E-Commerce Web Application

FusionStore is a fully functional **frontend e-commerce web application** built using **HTML, CSS, and Vanilla JavaScript**.  
It simulates a real online shopping experience with products, cart system, user authentication (frontend), orders, and invoice generation.

---

## 🚀 Project Features

### 🛍️ Products System
- Displays a list of featured products
- Each product includes:
  - Image
  - Name
  - Category
  - Price + old price (if available)
  - Discount badge
  - Star rating system
  - Number of reviews
  - Number of items sold
- Add to cart button for each product

---

### 🛒 Shopping Cart
- Add products to cart
- Increase / decrease product quantity
- Remove items from cart
- Automatic total calculation:
  - Subtotal
  - Tax (10%)
  - Grand total
- Empty cart handling

---

### 👤 User System (Frontend Only)
- User login system (email & password)
- User registration system
- Displays logged-in user name in navbar
- Logout functionality
- Prevents adding items or checkout without login

> Note: This is a frontend-only authentication system (no backend or database).

---

### 📦 Orders System
- Create order after checkout
- Stores order history in browser session
- Displays:
  - Order ID
  - Date
  - Number of items
  - Total price
  - Status (Processing / Cancelled)
- Track order status
- Cancel order (only if processing)

---

### 🧾 Invoice System
- Automatically generated after checkout
- Shows:
  - Invoice number
  - Date
  - Customer name
  - List of purchased items
  - Total amount paid
- Print invoice feature

---

### 💳 Checkout System
- Checkout only available when cart is not empty
- Requires user login
- Creates new order automatically
- Clears cart after purchase
- Redirects to orders page after checkout

---

## 🎨 UI Features

- Modern responsive design
- Sticky navigation bar
- Hero section with welcome message
- Gradient buttons and highlights
- Toast notifications for actions
- Hover animations on product cards
- Clean layout using CSS Grid and Flexbox
- Mobile responsive design

---

## 🧠 Technologies Used

```text
HTML5
CSS3
JavaScript (Vanilla JS)
Font Awesome Icons
Google Fonts (Inter)
```

---

## 📂 Project Structure

```text
FusionStore/
│
├── index.html   # Main file (HTML + CSS + JS combined)
│
└── Assets loaded via external image URLs
```

---

## 🎯 Project Purpose

This project was built to practice and demonstrate:

- Frontend web development skills
- JavaScript DOM manipulation
- State management using arrays (cart, users, orders)
- UI/UX design principles
- Building a full e-commerce workflow without backend

---

## 👨‍💻 Notes

- This project runs fully on the frontend only
- Data is stored temporarily in memory (no database)
- Designed for learning and portfolio purposes

---

## ⭐ Author

FusionStore Project – Built as a frontend development practice project using pure HTML, CSS, and JavaScript.
