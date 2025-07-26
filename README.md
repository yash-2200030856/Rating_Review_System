# 📝 Ratings Review System


**Empowering Trust Through Seamless User Feedback**

A full-stack web application for collecting, managing, and displaying user reviews and product ratings. Built with Node.js, Express.js, MySQL, and a static HTML frontend, it ensures secure user access and guarantees one review per user per product.

---

## 🚀 Tech Stack

- 🔧 **Backend**: Node.js, Express.js, MySQL
- 🌐 **Frontend**: HTML, CSS, JavaScript
- 🛡️ **Authentication**: Email/ID login, password encryption
- 📦 **Environment**: `.env` for secure credentials

---

## 📂 Folder Structure
```bash
ratings-review-system/
├── backend/
│ ├── server.js
│ ├── db.js
│ └── models/
├── frontend/
│ └── index.html
└── README.md
```
---

## 📦 Getting Started

### ✅ Prerequisites

- Node.js & npm
- MySQL Server
- Git (optional, for cloning)

---

### 🛠️ Installation

#### 1. Clone the repository
```bash
git clone https://github.com/yourusername/ratings-review-system.git
cd ratings-review-system
```
#### 2. Backend Setup
```bash
cd backend
npm install
```
#### 3. Environmental Variables
```bash
DB_HOST=localhost
DB_USER=root
DB_PASSWORD=yourpassword
DB_NAME=ratings_db
PORT=3000
```
#### 4. Start the backend server
```bash
node server.js
```
