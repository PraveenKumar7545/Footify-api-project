# 🍽️ Foodify - Food Ordering & Customization Web Application

Foodify is a modern **React.js food ordering and customization web application** where users can explore food, customize items, manage their cart, place orders, and submit feedback.

## 🌐 Live Demo 

**Live Website:** https://foodifyapi.netlify.app/

**GitHub Repository:** https://github.com/PraveenKumar7545/Footify-api-project 

---

## 📖 About

Foodify provides a simple and interactive food ordering experience.

Users can:

* Explore different food categories
* Browse popular local dishes
* Discover international dishes
* Customize food items
* Add food to cart
* Place orders
* View order details
* Submit order feedback
* Rate their experience
* Send feedback notifications through email

The application uses **TheMealDB API** to fetch additional food information and **EmailJS** for customer and admin email notifications.

---

## ✨ Features

* 🏠 Modern Home Page
* 🍔 Food Categories
* 🌎 Global Food Flavours
* 🔍 Food Exploration
* 🍱 Food Details
* ⚙️ Food Customization
* 🛒 Cart Management
* 📦 Order Management
* 📝 Order Feedback
* ⭐ Rating System
* 💰 Dynamic Pricing
* 🎁 Special Offers
* 📧 Customer Email Confirmation
* 🔔 Admin Email Notification
* 💾 Local Storage
* 🌐 TheMealDB API Integration
* 📱 Responsive Design

---

## 🛠️ Technologies Used

* React.js
* JavaScript
* HTML5
* CSS3
* React Router DOM
* TheMealDB API
* EmailJS
* Local Storage
* Git
* GitHub
* Netlify

---

## 🔌 API Integration

Foodify uses **TheMealDB API** to retrieve international food data.

Example:

```text
https://www.themealdb.com/api/json/v1/1/filter.php?c=Seafood
```

The application fetches meals from different categories and displays them dynamically.

---

## 📧 Email Notification

Foodify uses **EmailJS** to send email notifications.

### Customer

The customer can receive:

* Order ID
* Food items
* Total amount
* Rating
* Ordering experience
* Customization experience
* Suggestions

### Admin

The admin can receive:

* Customer email
* Order ID
* Ordered food items
* Total amount
* Rating
* Customer feedback
* Suggestions

### Email Flow

```text
Customer
    ↓
Submit Feedback
    ↓
Foodify
    ↓
EmailJS
    ├──→ Customer Confirmation
    │
    └──→ Admin Notification
```

---

## 💾 Local Storage

Foodify uses browser Local Storage to maintain order information and feedback.

Example:

```text
foodify_orders
```

---

## 📂 Project Structure

```text
Footify-api-project/
│
├── public/
│
├── src/
│   ├── components/
│   ├── data/
│   ├── pages/
│   ├── App.js
│   └── index.js
│
├── .gitignore
├── package.json
├── package-lock.json
└── README.md
```

---

## 🚀 Getting Started

### Clone the Repository

```bash
git clone https://github.com/PraveenKumar7545/Footify-api-project.git
```

### Navigate to the Project

```bash
cd Footify-api-project
```

### Install Dependencies

```bash
npm install
```

### Start the Application

```bash
npm start
```

The application will run on:

```text
http://localhost:3000
```

---

## 📚 Concepts Practiced

* React Components
* Props
* useState
* useEffect
* React Hooks
* React Router
* Conditional Rendering
* Event Handling
* Fetch API
* Async/Await
* API Integration
* Form Handling
* Local Storage
* EmailJS
* Responsive Design
* Git & GitHub
* Netlify Deployment

---

## 🔄 Application Flow

```text
Home
 ↓
Explore Foods
 ↓
Food Details
 ↓
Customize Food
 ↓
Add to Cart
 ↓
Place Order
 ↓
Order Details
 ↓
Order Feedback
 ↓
Email Notifications
 ├── Customer
 └── Admin
```

---

## 📸 Screenshots

Add screenshots of the application here.

```text
Home Page
Food Categories
Food Details
Customization
Cart
Orders
Feedback
```

---

## 👨‍💻 Developer

**Praveen Kumar M**

GitHub:
https://github.com/PraveenKumar7545

Repository:
https://github.com/PraveenKumar7545/Footify-api-project

---

## 🌐 Project Links

**Live Demo:**
https://foodifyapi.netlify.app/

**GitHub:**
https://github.com/PraveenKumar7545/Footify-api-project

---

## 🚀 Future Improvements

* User Authentication
* Backend Database
* Online Payment
* Admin Dashboard
* Real-Time Order Tracking
* User Profiles
* Advanced Search
* Food Filtering
* Restaurant Management
* Order Status Notifications

---

## 📄 License

This project is developed for **educational and portfolio purposes**.

---

<p align="center">

### 🍽️ Foodify

**Your Food. Your Choice. Your Way.**

Built with ❤️ using React.js

</p>
