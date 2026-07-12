# 📚 LearnRush

**A modern, full-stack e-learning platform built with the MERN stack — free courses, seamless video streaming, and role-based learning for everyone.**

[![Live Demo](https://img.shields.io/badge/Live%20Demo-Visit%20Site-brightgreen?style=for-the-badge)](https://learnrush-e-learning.onrender.com/)
[![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white)](https://www.mongodb.com/)
[![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)](https://reactjs.org/)
[![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)](https://nodejs.org/)
[![Express.js](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)](https://expressjs.com/)

---

## 🚀 Introduction

**LearnRush** is a modern full-stack e-learning platform built using the **MERN stack**, designed to provide free access to courses and lectures through a clean and intuitive user experience.

The platform supports **role-based access control** — admins can manage courses and lectures, while learners can explore, study, and stream educational content seamlessly. It features secure authentication, a responsive UI, video-based learning, and a scalable architecture, making it suitable for real-world deployment and future expansion (such as paid courses or subscriptions).

---

## ✨ Features

- 🔐 **Secure Authentication** — Sign up, log in, and manage your session safely
- 🎭 **Role-Based Access Control** — Separate experiences for Admins and Learners
- 🎥 **Video-Based Learning** — Stream lectures directly in the browser
- 🗂️ **Course Management** — Admins can create, update, and organize courses and lectures
- 📱 **Responsive UI** — Clean, intuitive design that works across devices
- ⚡ **Scalable Architecture** — Built to grow toward paid courses and subscriptions

---

## 🖥️ Try It Out

👉 **[Live Demo](https://learnrush-e-learning.onrender.com/)**

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| **Frontend** | React.js, CSS |
| **Backend** | Node.js, Express.js |
| **Database** | MongoDB |
| **Deployment** | Render / Vercel |

---

## 📁 Project Structure

```
LearnRush/
├── frontend/     # React client application
├── server/       # Node.js + Express backend API
└── README.md
```

---

## ⚙️ Getting Started

### Prerequisites
- Node.js and npm installed
- A MongoDB instance (local or Atlas)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/goyalmuskan2212/LearnRush.git
   cd LearnRush
   ```

2. **Set up the backend**
   ```bash
   cd server
   npm install
   ```
   Create a `.env` file in the `server` directory with the required environment variables (e.g. `MONGO_URI`, `JWT_SECRET`, `PORT`).
   ```bash
   npm start
   ```

3. **Set up the frontend**
   ```bash
   cd ../frontend
   npm install
   npm run dev
   ```

4. **Open the app**
   Visit `http://localhost:5173` (or your configured port) in your browser.

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!
Feel free to check the [issues page](https://github.com/goyalmuskan2212/LearnRush/issues) or submit a pull request.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📄 License

This project is open source and available for learning and educational purposes.

---

## 👩‍💻 Author

**Muskan Goyal**
[GitHub](https://github.com/goyalmuskan2212)

---

<p align="center">Made with ❤️ using the MERN Stack</p>
