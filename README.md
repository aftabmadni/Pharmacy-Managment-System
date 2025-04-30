
# 💊 Pharmacy Management System

A full-stack web application designed to streamline pharmacy operations, including medicine inventory management, sales processing, and customer interactions.

## 🚀 Features

- 🧾 *Medicine Management*: Add, update, delete, and search medicines.
- 🛒 *Sales Processing*: Handle sales transactions and generate invoices.
- 📦 *Inventory Tracking*: Monitor stock levels and receive low-stock alerts.
- 👥 *User Management*: Manage customer and staff information.
- 📊 *Reporting*: Generate sales and inventory reports.
- 🔐 *Authentication*: Secure login for admin and staff users.

## 🛠 Tech Stack

- **Frontend**: React.js  
- **Backend**: Node.js, Express.js  
- **Database**: MongoDB  
- **Version Control**: Git & GitHub  

## 📁 Project Structure

```
Pharmacy-Management-System/
├── backend/             # Express.js server and API routes
├── frontend/            # React.js application
├── .gitignore
├── package.json
├── Procfile             # For deployment
├── README.md
└── server.js            # Entry point for the backend
```

## 🧪 Installation & Setup

### Prerequisites

- Node.js and npm installed
- MongoDB installed and running

### Steps

1. **Clone the repository**
   ```bash
   git clone https://github.com/AsifMadni118/Pharmacy-Management-System.git
   cd Pharmacy-Management-System
   ```

2. **Install backend dependencies**
   ```bash
   cd backend
   npm install
   ```

3. **Install frontend dependencies**
   ```bash
   cd ../frontend
   npm install
   ```

4. **Configure environment variables**

   Create a `.env` file in the `backend` directory with the following content:

   ```
   PORT=5000
   MONGODB_URI=your_mongodb_connection_string
   JWT_SECRET=your_jwt_secret
   ```

5. **Start the development servers**

   - **Backend**
     ```bash
     cd ../backend
     npm start
     ```

   - **Frontend**
     ```bash
     cd ../frontend
     npm start
     ```

The frontend will run on [http://localhost:3000](http://localhost:3000) and the backend API on [http://localhost:5000](http://localhost:5000).
