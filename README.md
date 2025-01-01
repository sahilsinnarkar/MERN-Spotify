# MERN Spotify Clone

A full-stack Spotify clone built with the **MERN stack** (MongoDB, Express, React, Node.js), **TypeScript**, and **Socket.IO**. This project replicates Spotify-like features, including music streaming, playlist management, and real-time updates.

## Features

- **Music Streaming**: Play songs with interactive controls.
- **Playlist Management**: Create, edit, and delete playlists.
- **User Authentication**: Managed with **Clerk**.
- **Real-Time Features**: Powered by **Socket.IO**.
- **Responsive UI**: Built using **Radix UI** components and **Tailwind CSS**.
- **Media Uploads**: Handled by **Cloudinary**.
- **Interactive Player**: Slider-based song navigation.

## Tech Stack

### Backend:
- **Node.js**, **Express.js**, **Socket.IO**
- Database: **MongoDB Atlas**
- Tools: **Cloudinary**, **dotenv**, **express-fileupload**, **node-cron**

### Frontend:
- **React** with **Vite** (TypeScript)
- **Clerk** for authentication
- **Radix UI**, **Tailwind CSS**, and **ShadCN** for styling

## Prerequisites

- Node.js and npm
- MongoDB Atlas account
- Cloudinary account
- Clerk API setup

## Installation

1. **Clone the Repository**
   ```bash
   git clone https://github.com/yourusername/mern-spotify-clone.git
   cd mern-spotify-clone
2. **Install dependies**
- frontend: npm install
- backend: npm install

3. **Environment Variables** (.env)
MONGO_URI=your_mongodb_connection_string
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret
CLERK_API_KEY=your_clerk_api_key

4. **Seed Data Seed songs and albums to MongoDB:**
- npm run seed:songs --prefix backend
- npm run seed:albums --prefix backend

5. **Run the Application**
- backend: npm run dev --prefix backend
- frontend: npm run dev --prefix frontend

6. **Build for production**
npm run build

Scripts
Script	Description
npm run dev	- Start the backend/frontend in development mode.
npm run build	- Build both the backend and frontend.
npm run seed:songs - Seed song data to MongoDB.
npm run seed:albums	- Seed album data to MongoDB.

**Screenshots**
![image](https://github.com/user-attachments/assets/ea3a9002-b6a2-4152-ab05-c5c8363736b5)
![image](https://github.com/user-attachments/assets/031f5632-aa31-4616-9cb4-94e988333d47)
![image](https://github.com/user-attachments/assets/443856d8-1fbc-401f-856f-4f3d7641aa88)
![image](https://github.com/user-attachments/assets/e3b12aca-6e6a-4526-beb8-eae1b0130228)
![image](https://github.com/user-attachments/assets/c954d81b-50df-484f-bc15-d87aad044abb)
![image](https://github.com/user-attachments/assets/e7264712-1f9d-48a4-9cfb-cc5d7aaf820b)
![image](https://github.com/user-attachments/assets/cda4d91e-9d63-4640-ab0e-378f4fc4f711)






