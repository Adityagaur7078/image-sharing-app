# 📸 Image Sharing App

A full-stack image sharing application built with **React**, **Node.js**, **Express.js**, **MongoDB Atlas**, **MongoDB Compass**, and **ImageKit**.

This project allows users to upload images with captions from the frontend. The backend uploads images to ImageKit, stores the generated image URL and caption in MongoDB Atlas, and displays all uploaded posts in a responsive feed.

---

## ✨ Features

- Upload images from the frontend
- Add captions to uploaded images
- Store images securely using ImageKit
- Save image URL and caption in MongoDB Atlas
- View all uploaded posts
- RESTful API architecture
- Responsive user interface

---

## 🛠️ Tech Stack

### Frontend

- React
- Vite
- Axios
- CSS

### Backend

- Node.js
- Express.js
- Multer
- CORS
- dotenv

### Database

- MongoDB Atlas
- MongoDB Compass
- Mongoose

### Cloud Storage

- ImageKit

---

## 📁 Project Structure

```
image-sharing-app
│
├── Backend
│   ├── src
│   │   ├── db
│   │   ├── models
│   │   ├── services
│   │   └── app.js
│   │
│   ├── server.js
│   ├── package.json
│   └── .env
│
└── Frontend
    ├── src
    │   ├── pages
    │   ├── App.jsx
    │   ├── main.jsx
    │   └── index.css
    │
    ├── public
    ├── package.json
    └── vite.config.js
```

---

## 🚀 Getting Started

### Clone Repository

```bash
git clone https://github.com/Adityagaur7078/image-sharing-app.git
```

```bash
cd image-sharing-app
```

---

## Backend Setup

```bash
cd Backend
npm install
npm start
```

Backend runs on

```
http://localhost:3000
```

---

## Frontend Setup

```bash
cd Frontend
npm install
npm run dev
```

Frontend runs on

```
http://localhost:5173
```

---

## 🔐 Environment Variables

Create a `.env` file inside the Backend folder.

```env
Mongo_URI=your_mongodb_connection_string

IMAGEKIT_PRIVATE_KEY=your_private_key
```

---

## 🗄️ Database

This project uses **MongoDB Atlas** as the cloud database.

During development, **MongoDB Compass** is connected to the MongoDB Atlas cluster to view, manage, and inspect the stored data.

### Database Flow

```
Application
      │
      ▼
MongoDB Atlas Cluster
      ▲
      │
MongoDB Compass
```

- **MongoDB Atlas** stores the application data.
- **MongoDB Compass** is used as a graphical interface (GUI) to connect to the Atlas cluster and manage the database.
- **Mongoose** connects the backend application to MongoDB Atlas.

---

## 📡 API Endpoints

### Create Post

```
POST /create-post
```

Uploads an image to ImageKit and creates a new post.

---

### Get All Posts

```
GET /posts
```

Returns all uploaded posts.

---

## 🔄 Application Workflow

```
Frontend (React)
        │
        ▼
Express.js Backend
        │
        ▼
Multer
        │
        ▼
ImageKit
        │
        ▼
Image URL
        │
        ▼
MongoDB Atlas
        ▲
        │
MongoDB Compass
        │
        ▼
React Feed
```

---

## 📌 Current Status

- ✅ Backend Completed
- ✅ Frontend Completed
- ⏳ Deployment Planned

---

## 📚 What I Learned

- Building REST APIs using Express.js
- Connecting React with Express.js
- Uploading files using Multer
- Uploading images to ImageKit
- Working with MongoDB Atlas
- Managing databases using MongoDB Compass
- Using Mongoose ODM
- Environment variable management with dotenv
- Handling API requests with Axios
- Building a complete full-stack application

---

## 📷 Screenshots

Screenshots will be added after deployment.

---

## 👨‍💻 Author

**Aditya Gaur**

- GitHub: https://github.com/Adityagaur7078
- LinkedIn: https://www.linkedin.com/in/aditya-gaur-b484412bb

---

## 📄 License

This project is created for learning and portfolio purposes.