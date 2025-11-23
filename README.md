# MERN Ecommerce - TiendaSol

This project is a full-stack e-commerce application developed as part of the Group Practical Work for the "Desarrollo de Software" subject at **UTN FRBA** (Universidad Tecnológica Nacional - Facultad Regional Buenos Aires).

## 🚀 Live Demo

- **Frontend (Vercel):** [https://mern-ecommerce-tienda-sol.vercel.app/](https://mern-ecommerce-tienda-sol.vercel.app/)
- **Backend (Render):** Deployed on Render

## 🛠️ Technologies Used

### Frontend
The frontend is built with **React** and utilizes a modern ecosystem of libraries for a dynamic and responsive user experience.

- **Core:** React, Vite
- **Styling:** Tailwind CSS
- **Routing:** React Router DOM
- **State & Effects:** React Hooks
- **Animations:** Framer Motion
- **Icons:** Lucide React
- **Notifications:** React Toastify
- **Data Visualization:** Recharts
- **PDF Generation:** jsPDF
- **Loading States:** React Spinners

### Backend
The backend is a robust RESTful API built with **Node.js** and **Express**, ensuring secure and efficient data handling.

- **Runtime:** Node.js
- **Framework:** Express.js
- **Database:** MongoDB with Mongoose ODM
- **Authentication:** JSON Web Tokens (JWT) & Bcryptjs
- **Validation:** Zod
- **Documentation:** Swagger (Swagger UI Express)
- **Utilities:** Dotenv, Cors, Axios

## ✨ Features

- **User Authentication:** Secure login and registration using JWT.
- **Product Management:** Browse, search, and filter products.
- **Shopping Cart:** Add items, manage quantities, and checkout.
- **Dashboard:** Admin dashboard with data visualization using Recharts.
- **Order Generation:** Generate PDF receipts for orders.
- **Responsive Design:** Fully responsive layout powered by Tailwind CSS.

## 📦 Installation & Run Locally

1. **Clone the repository**
   ```bash
   git clone https://github.com/gianbolocco/MERN-ecommerce-TiendaSol.git
   cd MERN-ecommerce-TiendaSol
   ```

2. **Backend Setup**
   ```bash
   cd tiendaSolBackend
   npm install
   # Create a .env file with your variables (PORT, MONGODB_URI, JWT_SECRET, etc.)
   npm start
   ```

3. **Frontend Setup**
   ```bash
   cd tiendaSolFrontend
   npm install
   # Create a .env file if necessary
   npm run dev
   ```

## 📝 License

This project is for educational purposes as part of the UTN FRBA curriculum.