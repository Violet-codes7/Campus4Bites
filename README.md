# 🍽️ Campus4Bites

Campus4Bites is a web-based Multi-Canteen Token & Queue Management System designed for college campuses. It enables students and faculty to browse canteen menus, place food orders online, make digital payments, receive token numbers, and track their orders in real time—eliminating long queues and improving the overall canteen experience.

---

# ✨ Features

### 👨‍🎓 Student & Faculty

- 🔐 Secure login using college email (Google Authentication)
- 🍔 Browse menus from multiple canteens
- 🔍 Search and filter food items
- 🛒 Add items to cart
- 💳 Digital payments (UPI & Cash on Delivery)
- 🎟️ Automatic token generation
- 📦 Real-time order tracking
- 🔔 Email and push notifications
- ⭐ Rate and review completed orders

### 👨‍🍳 Canteen Staff

- 📋 Live order dashboard
- 🔄 Update order status
- ❌ Mark items as out of stock
- 🎯 Manage token queues

### 🧑‍💼 Manager

- ➕ Add menu items
- ✏️ Edit menu
- 🗑️ Delete menu items
- 📊 View sales reports
- ⭐ Respond to customer reviews

### 👑 Admin

- 👥 Manage users
- 🏫 Manage multiple canteens
- ⚙️ Configure system settings
- 📈 View analytics and reports
- 🛡️ Assign user roles

---

# 🛠️ Tech Stack

| Layer | Technology |
|--------|------------|
| Frontend | React.js, Next.js |
| Backend | Node.js |
| Database | MongoDB |
| Authentication | Google OAuth 2.0 |
| APIs | REST API |
| Communication | HTTPS + JSON |

---

# 📂 Project Structure

```text
Campus4Bites/
│
├── frontend/
│   ├── components/
│   ├── pages/
│   ├── styles/
│   └── public/
│
├── backend/
│   ├── routes/
│   ├── controllers/
│   ├── models/
│   ├── middleware/
│   └── server.js
│
├── database/
│
├── README.md
└── package.json
```

---

# 🧠 How It Works

## 1️⃣ User Authentication

- Users log in using their college email via Google Authentication.
- New users are registered automatically.
- Existing users are redirected to their dashboard.

## 2️⃣ Food Ordering

- Browse menus from different canteens.
- Search and filter items.
- Add food to cart.
- Proceed to checkout.

## 3️⃣ Queue & Token Management

- Every canteen maintains an independent queue.
- Users receive a unique token number.
- Estimated waiting time is shown.
- Staff updates order status in real time.

## 4️⃣ Payment

- Supports UPI and Cash on Delivery.
- Digital payment receipts are sent via email.

## 5️⃣ Order Tracking

Orders progress through:

```
Placed
   ↓
Confirmed
   ↓
Preparing
   ↓
Ready
   ↓
Collected
```
---

# 🚀 Getting Started

## 🔹 Prerequisites

- Node.js
- MongoDB
- npm

---

## 🔹 Installation

```bash
git clone https://github.com/your-username/Campus4Bites.git

cd Campus4Bites

npm install
```

---

## 🔹 Configure Environment

Create a `.env` file.

```env
MONGODB_URI=your_mongodb_uri

GOOGLE_CLIENT_ID=your_google_client_id

GOOGLE_CLIENT_SECRET=your_google_client_secret

JWT_SECRET=your_secret_key
```

---

## 🔹 Run the Project

Backend

```bash
npm run server
```

Frontend

```bash
npm run dev
```

Open

```
http://localhost:3000
```

---

# 🗄️ Database

The system stores information about:

- Users
- Canteens
- Menu Items
- Orders
- Tokens
- Payments
- Reviews
- Queue Status

MongoDB is used as the primary database. 

---

# 📱 UI Highlights

- 📱 Fully Responsive
- 🌙 Modern UI
- 🍔 Multi-Canteen Support
- ⚡ Live Queue Updates
- 🔔 Notifications
- 🎟️ Token Display
- 📊 Admin Dashboard

---

# 🔒 Security Features

- Google OAuth Authentication
- HTTPS Communication
- Encrypted Credentials
- Secure Session Management
- Verified College Email Login

---

# 🤝 Contributors

- Sumit Yadav
- Vaishali Yadav
- Vansh Tanwar
- Vinay

National Institute of Technology Delhi 

---

# 🙌 Acknowledgements

- React.js
- Next.js
- Node.js
- MongoDB
- Google OAuth
- IEEE 830-1998 SRS Standard
