# 📝 GoodNotes - A MERN Stack Notes Application

GoodNotes is a full-stack Notes Application built using the **MERN stack (MongoDB, Express, React, Node.js)**. It provides a secure and intuitive interface for users to manage their personal notes.

## 🚀 Features

- 🔐 **User Authentication**: Secure login and registration system.
- ➕ **Create Notes**: Add notes with titles, content, and timestamps.
- ✏️ **Edit/Delete Notes**: Seamlessly update or remove notes.
- 📌 **Pin Notes**: Highlight and pin important notes to keep them at the top.
- 🔍 **Search Notes**: Easily find notes using keywords.
- ✅ **Toast Notifications**: Instant visual feedback for login and actions.

## 🛠️ Technologies Used

- **Frontend**: React.js, TailwindCSS (or custom CSS)
- **Backend**: Node.js, Express.js
- **Database**: MongoDB (with Mongoose)
- **Authentication**: JWT (JSON Web Tokens), bcrypt

## 📸 Screenshots

### 🔐 Login Page
![Login Screenshot](https://github.com/Kanav92/notes_app/blob/main/Image%2019-07-25%20at%204.17%20PM.jpg?raw=true)

### 🏠 Dashboard (Notes View)
![Dashboard Screenshot](https://github.com/Kanav92/notes_app/blob/main/Image%2019-07-25%20at%204.17%20PM%20(1).jpg?raw=true)


> To include these screenshots, place your images in a folder called `assets` inside your project root and rename them as `login.jpg` and `dashboard.jpg`.

## 👥 Who Is This For?

- **Beginners**: Great starting project to understand the MERN stack.
- **Intermediate Developers**: Solid practice for building full-stack CRUD applications.
- **Anyone**: Looking to build a practical, useful notes app with authentication.

## 📁 Folder Structure

```
goodnotes/
├── client/        # React frontend
└── server/        # Node.js + Express backend
```

## ⚙️ Installation & Setup

### 1. Clone the repository
```bash
git clone https://github.com/your-username/goodnotes.git
cd goodnotes
```

### 2. Setup Backend
```bash
cd server
npm install
# Create a .env file and configure MongoDB URI and JWT secret
npm start
```

### 3. Setup Frontend
```bash
cd client
npm install
npm run dev
```

The app will run on:
- Frontend: `http://localhost:5173`
- Backend: `http://localhost:5000`

## 🔐 Environment Variables (server/.env)

```
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
```

## 🧠 Learnings

- Building full-stack apps with MERN
- API integration between frontend and backend
- Handling authentication with JWT
- UI and state management using React
- Managing application state and alerts

## 📜 License

This project is licensed under the MIT License.

---

> Made with ❤️ using the MERN Stack.

