# Voyage AI

Voyage AI is a modern web application that leverages artificial intelligence to provide intelligent solutions. This project features a React-based frontend and a Node.js backend with Express, offering a seamless user experience with AI-powered features.

## 🚀 Features

- **AI-Powered Features**: Leverages advanced AI models for intelligent processing
- **Modern UI/UX**: Built with React and TailwindCSS for a responsive design
- **RESTful API**: Robust backend API built with Node.js and Express
- **Environment Configuration**: Easy setup with environment variables
- **Modular Architecture**: Well-structured codebase for maintainability

## 🛠️ Tech Stack

### Frontend
- React
- Vite
- TailwindCSS
- React Router
- Axios for API calls

### Backend
- Node.js
- Express.js
- Environment-based configuration
- RESTful API architecture

## 🚀 Getting Started

### Prerequisites

- Node.js (v16 or higher)
- npm or yarn
- Git

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/JasmeetSingh16/Voyage-AI.git
   cd Voyage-AI
   ```

2. **Install dependencies**
   ```bash
   # Install backend dependencies
   cd backend
   npm install
   
   # Install frontend dependencies
   cd ../frontend
   npm install
   ```

3. **Environment Setup**
   - Create a `.env` file in the `backend` directory based on `.env.example`
   - Configure your environment variables

4. **Running the Application**
   ```bash
   # Start backend server
   cd backend
   npm start
   
   # In a new terminal, start frontend development server
   cd frontend
   npm run dev
   ```

5. **Access the Application**
   - Frontend: `http://localhost:3000`
   - Backend API: `http://localhost:5000` (or your configured port)

## 📂 Project Structure

```
voyage-ai/
├── backend/               # Backend server code
│   ├── src/              # Source files
│   ├── server.js         # Main server file
│   └── package.json      # Backend dependencies
├── frontend/             # Frontend React application
│   ├── public/           # Static files
│   ├── src/              # React components and pages
│   └── package.json      # Frontend dependencies
└── README.md             # This file
```

## 🔧 Configuration

Update the following environment variables in your `.env` file:

```env
# Backend
PORT=5000
NODE_ENV=development

# Add other environment variables as needed
```

## 🤝 Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👏 Acknowledgments

- [React](https://reactjs.org/)
- [Node.js](https://nodejs.org/)
- [Express](https://expressjs.com/)
- [TailwindCSS](https://tailwindcss.com/)
- [Vite](https://vitejs.dev/)


