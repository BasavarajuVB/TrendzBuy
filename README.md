# 🛍️ TrendyBuy - Your One-Stop Online Shopping Experience!

Welcome to **TrendyBuy**, a beautifully crafted e-commerce React application where users can explore, filter, and shop their favorite products seamlessly. With a user-friendly interface and real-time cart functionalities, TrendyBuy ensures a premium shopping experience — now enhanced with a sleek payment popup integration. 💳✨

## 🚀 Features

### ✅ Authentication

* 🔐 Secure login with username and password (JWT Token-based authentication).
* 🔄 Redirection to login if the user is not authenticated.

### 🔎 Product Exploration

* 🛒 View a wide range of products with details.
* 🔍 Real-time search by product title.
* 🔃 Sort products by price: Low to High / High to Low.
* 🧲 Filter by categories and ratings.

### 🧺 Cart Management

* ➕ Add products to cart.
* ➖ Increment/Decrement quantity.
* ❌ Remove items.
* ♻️ Auto-delete when quantity hits 0.
* 🧾 View cart summary: total items & total cost.

### 💰 Interactive Payment Popup (Newly Integrated)

* 🧾 Click “Checkout” on the Cart Page to launch a stylish popup.
* 💳 Select from payment options:

  * Card ❌ (Disabled)
  * Net Banking ❌
  * UPI ❌
  * Wallet ❌
  * ✅ **Cash on Delivery**
* 🧾 Payment Summary inside popup:

  * 🧮 Number of items
  * 💵 Total price
* 🔒 Confirm Order button is enabled only for Cash on Delivery.
* ✅ Upon confirmation: *“Your order has been placed successfully!”* message shown.

### 🌈 Modern UI

* 🎨 Clean, mobile-responsive layout using CSS Flexbox & Grid.
* 💡 Interactive feedback and intuitive flows.
* 📦 Popup created using `reactjs-popup` with `modal` support.

---

## 🛠️ Tech Stack

* **Frontend:** React JS ⚛️
* **State Management:** Component-level state & Props
* **Routing:** `react-router-dom`
* **Popup:** `reactjs-popup`
* **Authentication:** JWT Tokens
* **Styling:** Custom CSS

---

## 🧪 Testing Ready

This project is fully compatible with CCBP IDE test cases. Tests include:

* Product List
* Search, Sort, and Filter Logic
* Cart Functionality
* Payment Modal Logic and Display
* Order Confirmation Flow

---

## 📁 Project Setup

### Clone the Project

```bash
git clone https://github.com/YourUsername/TrendyBuy.git
cd TrendyBuy
```

### Install Dependencies

```bash
npm install
```

### Start the Application

```bash
npm start
```

---

## 🤝 Contributing

Found a bug or want to improve the UI? Feel free to raise issues or PRs!

---

## 👨‍💻 Developed By

**Basavaraju VB**
Full Stack Developer | React | Firebase | Solidity


