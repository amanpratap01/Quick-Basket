# 🛒 QuickBasket

QuickBasket is a full-stack grocery e-commerce web application built using the MERN stack. It allows users to browse products, add items to a cart, and place orders seamlessly — all through an intuitive and responsive interface.

---

## 🚀 Features

* 🛍️ Browse products with categories
* ➕ Add / remove items from cart
* 🧾 Smooth checkout experience
* 🔐 User authentication (login/signup)
* 📦 Order placement and history
* 🧑‍💼 Admin product management (add/update/delete)

---

## 🧩 Tech Stack

**Frontend:**

* React.js
* Axios
* Tailwind CSS / CSS

**Backend:**

* Node.js
* Express.js

**Database:**

* MongoDB

---

## 📁 Project Structure

```
QuickBasket/
 ├── client/   # Frontend (React)
 └── server/   # Backend (Node + Express)
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the repository

```
git clone https://github.com/your-username/QuickBasket.git
cd QuickBasket
```

### 2️⃣ Setup Backend

```
cd server
npm install
npm start
```

### 3️⃣ Setup Frontend

```
cd client
npm install
npm run dev
```

---

## 🔐 Environment Variables

Create a `.env` file in the **server** folder and add:

```
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
PORT=5000
```

---

## 🌐 API Endpoints (Sample)

* `POST /api/users/register` → Register user
* `POST /api/users/login` → Login user
* `GET /api/products` → Get all products
* `POST /api/orders` → Place order

---

## 🎯 Future Improvements

* 💳 Payment gateway integration
* 📊 Admin dashboard
* 🔍 Advanced search & filters
* 📱 Mobile responsiveness improvements

---

## 🤝 Contributing

Contributions are welcome! Feel free to fork this repo and submit a pull request.

---

## 📜 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

**Aman Pratap**

* GitHub: https://github.com/amanpratap01

---

⭐ If you like this project, don’t forget to star the repo!
