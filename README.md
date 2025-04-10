# MERN Authentication App

A full-stack authentication application built with the **MERN** stack — MongoDB, Express.js, React.js, and Node.js. It supports user registration, login, protected routes, and JWT-based authentication.

## 🚀 Features

- User Registration & Login
- Password Hashing with bcrypt
- JWT Authentication
- Protected Routes
- Logout Functionality
- Environment Variable Configuration
- Error Handling & Form Validation

## 🛠 Tech Stack

- **Frontend**: React.js, Axios, React Router
- **Backend**: Node.js, Express.js
- **Database**: MongoDB (Mongoose)
- **Authentication**: JWT (JSON Web Token), bcrypt

## 📂 Project Structure

```
mern-auth/
│
├── client/              # React frontend
│   ├── public/
│   └── src/
│       ├── components/
|       ├── context/
│       ├── pages/
│       └── App.js
│
├── server/              # Node.js backend
│   ├── config/
│   ├── controllers/
│   ├── middleware/
│   ├── models/
│   ├── routes/
│   └── server.js
│
├── .env
├── .gitignore
├── package.json
└── README.md
```

## 🔐 Environment Variables

Create a `.env` file in the `server/` directory and add the following:

PORT=5000
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key

## 🧑‍💻 Getting Started

### 1. Clone the Repository


git clone https://github.com/your-username/mern-auth.git
cd mern-auth


### 2. Install Dependencies


# Install backend dependencies
cd server
npm install

# Install frontend dependencies
cd ../client
npm install


### 3. Run the App


# Run backend
cd server
npm run dev

# Run frontend
cd ../client
npm start


### 4. Open in Browser

Visit `http://localhost:3000` to view the app.

## 📜 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## 🙌 Acknowledgements

- [MongoDB](https://www.mongodb.com/)
- [Express](https://expressjs.com/)
- [React](https://reactjs.org/)
- [Node.js](https://nodejs.org/)

---

### 🌟 Star the repo if you find it helpful!
```

---

Would you like to include a live demo link or deployment instructions (e.g., with Render, Vercel, or Netlify)?
