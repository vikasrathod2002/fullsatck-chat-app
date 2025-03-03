![Screenshot 2025-03-03 222022](https://github.com/user-attachments/assets/f0f44be9-2ccf-4b74-a6c7-1045beae0bf9)

🌐 Live Demo : https://fullsatck-chat-app-lwu3.onrender.com/login

# 📩 Real-Time chat-App 🚀 (MERN + Zustand + Socket.io)  

A full-stack **real-time messaging application** built with **React.js, TailwindCSS, DaisyUI, Node.js, Express.js, MongoDB, Zustand, and Socket.io**. This app enables **instant messaging, online user status tracking, and secure authentication** with JWT.  

---

## 🚀 Tech Stack  

| Technology     | Purpose                                           |
|---------------|---------------------------------------------------|
| **React.js**  | Frontend for dynamic user interface               |
| **TailwindCSS + DaisyUI** | Modern, responsive, and elegant UI styling |
| **Node.js**   | Server-side runtime for backend logic             |
| **Express.js**| Backend framework for API handling                |
| **MongoDB**   | NoSQL database for storing users & messages       |
| **Zustand**   | Lightweight state management for global state     |
| **Socket.io** | Real-time, bidirectional communication for chat   |
| **JWT Auth**  | Secure authentication & authorization             |

---

## ✨ Key Features  

✅ **Real-Time Messaging** — Instant messaging powered by **Socket.io**.  
✅ **Online User Status** — See who’s online in real time.  
✅ **Secure Authentication** — Implemented **JWT-based authentication & authorization**.  
✅ **Zustand for State Management** — Lightweight & scalable global state management.  
✅ **User Search & Direct Messages** — Find users and chat privately.   
✅ **Unread Message Count** — Notifications for unread messages.   
✅ **Responsive UI** — Built with **TailwindCSS + DaisyUI** for a sleek design.  
✅ **RESTful API** — Well-structured **Express.js** backend with clean API endpoints.  
✅ **Error Handling & Security** — Secure password hashing, CORS setup, and validation.  

---

  ## 📂 Folder Structure  
    /
    |-- client/                     # Frontend React Application
    |   |-- src/                     # Source code folder
    |   |   |-- components/          # Reusable UI components (buttons, modals, etc.)
    |   |   |-- pages/                # Application pages (Dashboard, Login, Register, etc.)
    |   |   |-- context/              # Global state management using Zustand
    |   |   |-- services/             # API service functions (Axios calls)
    |   |   |-- App.js                 # Main React application entry point
    |   |-- public/                   # Static assets (favicon, index.html)
    |   |-- package.json              # Frontend dependencies

    |-- server/                      # Backend API built with Node.js and Express.js
    |   |-- models/                   # Mongoose schema models (User, Snippet, etc.)
    |   |-- routes/                   # Route handlers (snippets, auth, etc.)
    |   |-- controllers/              # Business logic for handling requests
    |   |-- middleware/               # Authentication, error handling, etc.
    |   |-- config/                   # Database connection & environment settings
    |   |-- server.js                  # Backend entry point
    |   |-- package.json              # Backend dependencies

    |-- .env                          # Environment variables (not included in repo)
    |-- .gitignore                    # Files and directories to ignore in Git
    |-- README.md                     # Project documentation 
    
  ---
  
  📌 Explanation
    
       Folder/File	Description                                                                            
   
      client/	                     Contains the React frontend                                           
      client/src/components/	     Reusable UI components like buttons, forms, modals                   
      client/src/pages/	           Individual pages like Dashboard, Login, Register, etc.                
      client/src/context/          Global state management using Zustand (or Redux if applicable)      
      client/src/services/         API call functions (handled using Axios or Fetch)                     
      server/	                     Contains the backend Node.js + Express.js API                        
      server/models/	             MongoDB Mongoose schema models                                       
      server/routes/	             API routes (e.g., snippets.js, auth.js)                              
      server/controllers/          Contains business logic functions for handling incoming requests     
      server/middleware/	         Authentication and error-handling middleware functions               
      server/config/	             Contains database connection and environment settings                
      server/server.js	           Main entry point for the backend application                        
      .env	                       Environment variables file (should be excluded from Git using .gitignore) 
      .gitignore	                 Specifies files and folders to exclude from version control           
       README.md	                  The documentation file for your project (this file) 

  ---

## 🔐 Authentication & Security  

- **JWT-based authentication** for user login and protected routes.  
- Passwords securely **hashed with bcrypt** before storing in MongoDB.  
- **Tokens stored in HTTP-Only Cookies** to prevent XSS attacks.  
- Proper **CORS configuration** for secure cross-origin requests.  
- **Role-based access control (RBAC)** for user permissions.  

---

## ⚙️ Core Functionalities  

### 🛠 User Features  
✅ **Sign up & Log in** (JWT authentication)  
✅ **Search Users** for private messaging  
✅ **Real-Time Chat** (One-to-One & Group Chats)  
✅ **Profile Picture Upload & Customization**  
✅ **Typing Indicators** (See when the other person is typing)  
✅ **Read Receipts & Unread Message Counter**  

### 🔥 Chat Features  
✅ **Instant Delivery** using **Socket.io**  
✅ **Online & Offline Status** tracking  
✅ **Message Seen & Read Notifications**  
✅ **Group Chat with Multiple Users**  
✅ **Pinned & Starred Messages** 

---

## 📥 Installation & Setup  
    Install Dependencies
    # Install backend dependencies
    cd server
    npm install

# Install frontend dependencies
    cd client
    npm install

# Environment Variables
    MONGO_URI=your_mongodb_connection_string
    JWT_SECRET=your_jwt_secret_key
    PORT=5000

# Start the Application
# Start backend
    cd server
    npm run dev

# Start frontend
    cd  client
    npm run dev

📊 API Documentation

    Endpoint	Method	Description
    /api/auth/register	POST	Register new user
    /api/auth/login	POST	Login user
    /api/users	GET	Get list of all users
    /api/messages	GET	Fetch chat history
    /api/messages/send	POST	Send a new message
    /api/messages/seen	PATCH	Mark message as seen

🔗 Follow Me

  📧 Contact: vikassrathod2002@gmail.com   

       

