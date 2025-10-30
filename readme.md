# 🌐 Vybe — A Modern Social Media Platform

Vybe is a full-stack **social media platform** built using the **MERN (MongoDB, Express.js, React.js, Node.js)** stack.  
It allows users to connect, share posts, like, comment, and interact in real time — providing a smooth and modern social networking experience.

---

## 🚀 Features

### 👥 User Features
- 🔐 **Authentication System** — Secure signup/signin using JWT & bcrypt.
- 👤 **User Profiles** — Customizable user profiles with bio, avatar, and cover photo.
- 📝 **Post Creation** — Create, edit, and delete posts with text, images, or videos.
- ❤️ **Like & Comment System** — Engage with posts using likes and comments.
- 🔎 **Search & Discover** — Find users and explore trending posts.
- 💬 **Real-Time Chat** — One-on-one and group chat powered by **Socket.IO**.
- 🌙 **Dark/Light Mode** — Personalize your experience.

### 🧠 Admin Features (optional)
- 🧾 Manage users and posts.
- 🚫 Remove inappropriate content.
- 📊 Dashboard with platform insights.

---

## 🧰 Tech Stack

| Category | Technology |
|-----------|-------------|
| **Frontend** | React.js, Redux / Context API, Tailwind CSS |
| **Backend** | Node.js, Express.js |
| **Database** | MongoDB, Mongoose |
| **Authentication** | JWT, bcrypt.js |
| **Real-time Communication** | Socket.IO |
| **File Uploads** | Multer / Cloudinary |
| **Deployment** | Render / Vercel / MongoDB Atlas |

---

## ⚙️ Installation & Setup

Follow these steps to set up Vybe locally on your machine.

### 1. Clone the Repository
```bash
git clone https://github.com/yash96644/vybe.git
cd vybe

### 2. Backend Setup
cd server
npm install

### Create a .env file inside /server and add:

MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
CLOUDINARY_NAME=your_cloudinary_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_api_secret

### Run the backend:

npm start

### 3. Frontend Setup

cd ../client
npm install
npm run dev

🧩 Folder Structure

vybe/
├── client/              # React frontend
│   ├── src/
│   │   ├── components/  # Reusable UI components
│   │   ├── pages/       # Main pages (Home, Profile, etc.)
│   │   ├── context/     # Global state management
│   │   ├── assets/      # Images, icons
│   │   └── App.js
│   └── package.json
│
├── server/              # Node.js backend
│   ├── models/          # Mongoose schemas
│   ├── routes/          # Express routes
│   ├── controllers/     # API logic
│   ├── middleware/      # Auth and error handling
│   ├── utils/           # Helper functions
│   ├── server.js        # Entry point
│   └── package.json
│
└── README.md


-->  🧑‍💻 Author

Yash Kumar Gupta
📍 Frontend Developer | MERN Stack Developer


-> Made with ❤️ by Yash Gupta


---

Would you like me to make it **more aesthetic with emojis, badges, and live demo sections** (like top open-source GitHub projects)?



