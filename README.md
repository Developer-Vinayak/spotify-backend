echo "# 🎵 Spotify Backend API

A complete RESTful API for Spotify-like music streaming platform with JWT authentication, MongoDB, and Express.js.

## 🚀 Tech Stack
- Node.js + Express.js
- MongoDB + Mongoose
- JWT Authentication
- Bcrypt for password hashing
- Cookie-parser
- CORS

## ✨ Features
- User Signup/Login with JWT
- Protected Routes with Middleware
- CRUD for Songs
- Playlist Management
- User Profile Management

## 🛠️ Installation
\`\`\`bash
npm install
\`\`\`

## 🔧 Environment Variables
Create .env file:
\`\`\`
PORT=5000
MONGODB_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret
\`\`\`

## 🚀 Run Server
\`\`\`bash
npm start
\`\`\`

## 📁 Project Structure
- src/config/ - Database config
- src/models/ - MongoDB schemas
- src/controllers/ - Business logic
- src/routes/ - API endpoints
- src/middleware/ - Auth middleware

## 📝 API Endpoints
- POST /api/auth/signup - Register
- POST /api/auth/login - Login
- GET /api/user/profile - Get profile
- POST /api/songs - Add song
- GET /api/songs - Get all songs
- POST /api/playlists - Create playlist

## 📄 License
MIT" > README.md
