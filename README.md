# DExTER - Decentralized Exchange Trading Platform

DExTER enables users to swap tokens securely on the blockchain with a sleek, intuitive interface.

## 📋 Table of Contents

- [Features](#features)
- [Tech Stack](#tech-stack)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Project Structure](#project-structure)
- [Getting Started](#getting-started)
- [Configuration](#configuration)
- [Scripts](#scripts)
- [Contributing](#contributing)
- [License](#license)

## ✨ Features

- **Token Swap Interface** - UI for swapping cryptocurrency tokens
- **Real-time Token Data** - Dynamic token list with current market prices
- **Responsive Design** - Mobile-friendly interface

## 🛠 Tech Stack

### Frontend
- **React** 18.2.0 - UI library
- **React Router DOM** 6.6.2 - Client-side routing
- **Ant Design** 5.1.5 - UI component library
- **ethers.js** 5.7.2 - Blockchain interaction
- **wagmi** 0.10.11 - React hooks for Web3
- **Axios** 1.2.3 - HTTP client

### Backend
- **Node.js** - JavaScript runtime
- **Express.js** 4.18.2 - Web framework
- **Moralis** 2.11.1 - Data provider
- **CORS** 2.8.5 - Cross-origin resource sharing
- **dotenv** 16.0.3 - Environment variable management

## 📦 Prerequisites

Before you begin, ensure you have the following installed:
- Node.js (v14 or higher)
- npm or yarn package manager
- A modern web browser with Web3 support (MetaMask recommended)

## 🚀 Installation

### 1. Clone the Repository
```bash
git clone https://github.com/IanoNjuguna/DExTER.git
cd DExTER
```

### 2. Backend Setup
```bash
cd dexBack
npm install
```

Create a `.env` file in the `dexBack` directory and add your configuration:
```
PORT=5000
MORALIS_API_KEY=your_moralis_api_key
```

### 3. Frontend Setup
```bash
cd ../dexFront
npm install
```

## 📁 Project Structure

```
DExTER/
├── dexBack/                 # Backend application
│   ├── index.js            # Express server entry point
│   ├── package.json        # Backend dependencies
│   └── ...
├── dexFront/               # Frontend application
│   ├── public/
│   │   ├── index.html      # HTML template
│   │   └── ...
│   ├── src/
│   │   ├── App.js          # Main App component
│   │   ├── App.css         # App styles
│   │   ├── index.js        # React entry point
│   │   ├── index.css       # Global styles
│   │   ├── tokenList.json  # Token configuration
│   │   └── components/
│   │       ├── Header.js   # Header component
│   │       ├── Swap.js     # Swap interface component
│   │       └── Tokens.js   # Token list component
│   ├── package.json        # Frontend dependencies
│   └── ...
└── README.md               # Project documentation
```

## 🎯 Getting Started

### Start the Backend Server
```bash
cd dexBack
npm start
```

The backend server will run on `http://localhost:5000` by default.

### Start the Frontend Development Server
```bash
cd dexFront
npm start
```

The frontend will automatically open in your browser at `http://localhost:3000`.

## ⚙️ Configuration

### Frontend Configuration
- Update token list: `dexFront/src/tokenList.json`
- Modify API endpoints: Update axios calls in components as needed

### Backend Configuration
- Set environment variables in `dexBack/.env`
- Configure Moralis API key for blockchain data access
- Update CORS settings in `index.js` as needed

## 📝 Scripts

### Frontend Scripts
```bash
npm start       # Start development server
npm build       # Build for production
npm test        # Run tests
npm eject       # Eject from create-react-app (irreversible)
```

### Backend Scripts
```bash
npm test        # Run tests (placeholder)
```

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the ISC License - see the LICENSE file for details.

---

**Author:** Iano Njuguna

For more information or support, please open an issue on the GitHub repository.
