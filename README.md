# 💬 Real-Time Chat Application

A full-stack real-time chat application built with the MERN stack, featuring instant messaging, user authentication, and cloud-based image storage.

![MERN Stack](https://img.shields.io/badge/Stack-MERN-green)
![Node.js](https://img.shields.io/badge/Node.js-18+-green)
![React](https://img.shields.io/badge/React-18+-blue)
![MongoDB](https://img.shields.io/badge/MongoDB-Atlas-green)

## 🚀 Features

### Authentication & User Management
- **Secure Authentication**: JWT-based authentication with HTTP-only cookies
- **User Registration & Login**: Complete signup and login flow with validation
- **Profile Management**: Update user profiles with image uploads
- **Session Management**: Persistent sessions with automatic authentication checks

### Real-Time Messaging
- **Instant Messaging**: Real-time bidirectional communication using WebSockets
- **Text & Image Messages**: Send both text messages and image attachments
- **Online Status**: See which users are currently online
- **Message History**: Persistent message storage with timestamps
- **Auto-scroll**: Automatic scrolling to latest messages

### User Experience
- **Responsive Design**: Fully responsive UI that works on all devices
- **Dark/Light Theme**: Multiple theme options with persistent theme selection
- **Loading States**: Skeleton loaders for better perceived performance
- **Toast Notifications**: User-friendly feedback for all actions
- **Protected Routes**: Route protection based on authentication status

### Backend Architecture
- **RESTful API**: Clean REST API design with proper HTTP methods
- **Middleware Protection**: Custom authentication middleware for route protection
- **Cloud Storage**: Integration with cloud storage service for image handling
- **Database Modeling**: Efficient NoSQL schema design with relationships
- **Error Handling**: Comprehensive error handling throughout the application

## 🛠️ Tech Stack

### Frontend
- **React** - UI library
- **React Router** - Client-side routing
- **State Management** - Global state management library
- **HTTP Client** - Promise-based HTTP client
- **WebSocket Client** - Real-time communication
- **CSS Framework** - Utility-first CSS framework
- **UI Components** - Component library
- **Toast Notifications** - User feedback system

### Backend
- **Node.js** - Runtime environment
- **Express.js** - Web framework
- **MongoDB** - NoSQL database
- **Mongoose** - ODM for MongoDB
- **Socket.io** - WebSocket library
- **JWT** - Authentication tokens
- **bcryptjs** - Password hashing
- **Cloudinary** - Cloud image storage
- **Cookie Parser** - Cookie handling
- **CORS** - Cross-origin resource sharing
