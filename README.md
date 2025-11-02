# Streamify

Streamify is a modern real-time chat and video calling application built with React and Node.js. It provides a seamless communication platform with features like instant messaging, video calls, friend requests, and theme customization.

## 🚀 Features

- **Real-time Chat:** Instant messaging with friends
- **Video Calls:** High-quality video communication
- **Authentication:** Secure user authentication system
- **Friend System:** Send and manage friend requests
- **Theme Customization:** Choose between different UI themes
- **Responsive Design:** Works seamlessly on desktop and mobile devices

## 🛠️ Tech Stack

### Frontend
- React 19
- Vite
- TailwindCSS with DaisyUI
- React Query for state management
- React Router for navigation
- Axios for API requests
- React Hot Toast for notifications

### Backend
- Node.js with Express
- MongoDB with Mongoose
- Stream Chat SDK
- JWT for authentication
- bcryptjs for password hashing
- CORS enabled

## 🏗️ Project Structure

```
streamify/
├── frontend/                # React frontend application
│   ├── src/
│   │   ├── components/     # Reusable UI components
│   │   ├── pages/         # Application pages/routes
│   │   ├── hooks/         # Custom React hooks
│   │   ├── lib/           # Utility functions and API setup
│   │   └── store/         # State management
│   └── public/            # Static assets
│
└── backend/                # Node.js backend server
    └── src/
        ├── controllers/   # Route controllers
        ├── models/       # Database models
        ├── routes/       # API routes
        ├── middleware/   # Custom middleware
        └── lib/         # Utility functions
```

## 🚦 Getting Started

### Prerequisites
- Node.js (v16 or higher)
- MongoDB
- Stream account for chat functionality

### Installation

1. Clone the repository:
```bash
git clone https://github.com/rahulapjs/streamify.git
cd streamify
```

2. Install backend dependencies:
```bash
cd backend
npm install
```

3. Install frontend dependencies:
```bash
cd ../frontend
npm install
```

4. Create a `.env` file in the backend directory with the following variables:
```env
MONGODB_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret
STREAM_API_KEY=your_stream_api_key
STREAM_API_SECRET=your_stream_api_secret
```

### Running the Application

1. Start the backend server:
```bash
cd backend
npm run dev
```

2. Start the frontend development server:
```bash
cd frontend
npm run dev
```

The application will be available at `http://localhost:5173`

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📝 License

This project is licensed under the ISC License.

## ✨ Author

[rahulapjs](https://github.com/rahulapjs)