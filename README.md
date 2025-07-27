# ✨ Full Stack Real-time Chat App ✨

A modern, full-featured chat application built with the MERN stack, featuring real-time messaging, user authentication, and a beautiful responsive UI.

## 🚀 Features

- 🌟 **Tech stack**: MERN (MongoDB, Express.js, React, Node.js) + Socket.io + TailwindCSS + Daisy UI
- 🔐 **Authentication & Authorization** with JWT tokens
- 💬 **Real-time messaging** with Socket.io
- 👥 **Online user status** tracking
- 🎨 **Beautiful responsive UI** with TailwindCSS and Daisy UI
- 📱 **Mobile-friendly** design
- 🌙 **Dark/Light theme** support
- 📷 **Image sharing** with Cloudinary integration
- 🔔 **Message notifications**
- 👌 **Global state management** with Zustand
- 🐞 **Comprehensive error handling** on both client and server
- ⚡ **Fast and optimized** performance

## 🛠️ Installation & Setup

### Prerequisites

- Node.js (v14 or higher)
- MongoDB (local or cloud)
- Cloudinary account (for image uploads)

### 1. Clone the repository

```bash
git clone https://github.com/MayurHirpara1/real-time-chat-app.git
cd real-time-chat-app
```

### 2. Install dependencies

```bash
# Install dependencies for both frontend and backend
npm run install-deps

# Or manually:
# npm install --prefix backend
# npm install --prefix frontend
```

### 3. Environment Variables

Create a `.env` file in the `backend` directory with the following variables:

```env
MONGODB_URI=your_mongodb_connection_string
PORT=5001
JWT_SECRET=your_jwt_secret_key

CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_api_secret

NODE_ENV=development
```

### 4. Run the application

```bash
# Build the app
npm run build

# Start the production server
npm start

# Or run in development mode (requires concurrently)
npm run dev
```

## 🏗️ Project Structure

```
chat-app/
├── backend/
│   ├── src/
│   │   ├── controllers/
│   │   ├── middleware/
│   │   ├── models/
│   │   ├── routes/
│   │   ├── lib/
│   │   └── seeds/
│   └── package.json
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── store/
│   │   ├── lib/
│   │   └── constants/
│   └── package.json
└── package.json
```

## 🎯 Usage

1. **Sign up** for a new account or **log in** with existing credentials
2. **Browse online users** in the sidebar
3. **Click on a user** to start a conversation
4. **Send messages** in real-time
5. **Share images** by clicking the image icon
6. **Toggle themes** using the theme switcher

## 🚀 Deployment

This app is ready for deployment on platforms like:
- **Heroku**
- **Vercel** (Frontend) + **Railway** (Backend)
- **Netlify** (Frontend) + **Render** (Backend)
- **DigitalOcean**

Make sure to:
1. Set up environment variables on your hosting platform
2. Update CORS settings in the backend for your frontend URL
3. Set `NODE_ENV=production`

<!-- ## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request -->


⭐ **Star this repository if you found it helpful!**
