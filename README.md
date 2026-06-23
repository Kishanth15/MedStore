# MedStore

MedStore is a **medical store / pharmacy web application** built to provide a simple and user-friendly online platform for browsing healthcare products and managing medicine-related purchases. The project focuses on creating a clean shopping experience with essential e-commerce flows such as product browsing, login, order handling, payment flow, and user profile management.

This project was built as a hands-on full-stack web development project to strengthen my understanding of **React**, **Vite**, **Node.js**, and modern frontend application structure.

---

## Features

* Browse healthcare and medical products
* Clean and responsive home page UI
* User login page
* Orders page for managing purchases
* Payment page for checkout flow
* Profile page for user details
* Reusable React components for better structure
* Fast frontend development setup using **Vite**
* Backend server setup using **Node.js**

---

## Tech Stack

### Frontend

* **React.js**
* **Vite**
* **JavaScript**
* **CSS**

### Backend

* **Node.js**
* **Express.js** *(if used in `server.js`)*

### Tools & Configuration

* ESLint
* npm

---

## Project Structure

```bash
MedStore/
│── public/
│── src/
│   ├── assets/
│   ├── components/
│   │   └── Navbar.jsx
│   ├── pages/
│   │   ├── Home.jsx
│   │   ├── Login.jsx
│   │   ├── Orders.jsx
│   │   ├── Payment.jsx
│   │   └── Profile.jsx
│   ├── App.jsx
│   ├── App.css
│   ├── index.css
│   └── main.jsx
│
│── logo.png
│── meds.png
│── cs.png
│── gel.png
│── n95.png
│── para.png
│── profile.png
│── sani.png
│── vitc.png
│
│── server.js
│── package.json
│── vite.config.js
│── eslint.config.js
└── README.md
```

---

## Screens / Pages

* **Home** – Displays the landing page and featured medical products
* **Login** – User authentication interface
* **Orders** – View and manage placed orders
* **Payment** – Handles payment/checkout flow
* **Profile** – Displays user profile details

---

## Installation and Setup

### 1. Clone the repository

```bash
git clone https://github.com/Kishanth15/MedStore.git
cd MedStore
```

### 2. Install frontend dependencies

```bash
npm install
```

### 3. Run the frontend

```bash
npm run dev
```

The frontend will start on the Vite development server, usually at:

```bash
http://localhost:5173
```

---

## Backend Setup

If your `server.js` is used for backend/API handling, run:

```bash
node server.js
```

or if you have a custom script in `package.json`:

```bash
npm start
```

If your backend uses environment variables, create a `.env` file and add the required values there.

Example:

```env
PORT=5000
```

---

## Purpose of the Project

The goal of MedStore is to simulate an **online medical shopping experience** and practice building a structured web application with multiple pages, reusable components, and a backend connection. It helped me improve my skills in:

* React component-based development
* Routing and page structuring
* Building responsive UI layouts
* Organizing assets and reusable components
* Connecting frontend and backend workflow
* Structuring a real-world project for portfolio use

---

## Future Improvements

Some improvements planned for the project:

* Add full authentication with signup/login
* Connect product data to a database
* Add cart functionality
* Add medicine search and category filters
* Add order tracking
* Add secure payment integration
* Add admin dashboard for product management
* Add deployment for frontend and backend

---

## Learning Outcomes

Through this project, I improved my understanding of:

* Building a React application with **Vite**
* Structuring pages and reusable components
* Managing project assets and UI organization
* Creating a frontend flow for e-commerce-like applications
* Setting up a backend entry point using Node.js
* Writing cleaner and more maintainable project structure

---

## Author

**Kishanth**
B.Tech Artificial Intelligence and Data Science
KIT - Kalaignarkarunanidhi Institute of Technology

* GitHub: [Kishanth15](https://github.com/Kishanth15)

---

## License

This project is created for **learning, practice, and portfolio purposes**.
