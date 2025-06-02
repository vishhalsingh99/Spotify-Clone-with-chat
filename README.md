# Realtime Spotify Clone 🎵

A full-stack music streaming app that mimics Spotify functionality with real-time updates, live user presence, and integrated chat.

## 🛠 Tech Stack

- **Frontend**: React, Tailwind CSS, Vite
- **Backend**: Node.js, Express
- **Database**: MongoDB
- **Authentication**: Clerk
- **Real-Time**: WebSockets (Socket.io)
- **Media Storage**: Cloudinary

## ✨ Features

- Play music, skip tracks, and control volume
- Real-time chat and online user presence
- Admin dashboard for uploading albums/songs
- View what others are listening to in real time
- Realtime analytics and usage tracking

## 🚀 Getting Started

```bash
# Backend
cd backend
npm install
npm run dev

# Frontend
cd ../frontend
npm install
npm run dev
```

## 📂 Environment Variables

Backend `.env`:
```
PORT=...
MONGODB_URI=...
ADMIN_EMAIL=...
NODE_ENV=...
CLOUDINARY_API_KEY=...
CLOUDINARY_API_SECRET=...
CLOUDINARY_CLOUD_NAME=...
CLERK_PUBLISHABLE_KEY=...
CLERK_SECRET_KEY=...
```

Frontend `.env`:
```
VITE_CLERK_PUBLISHABLE_KEY=...
```
