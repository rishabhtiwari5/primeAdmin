# Fullstack Admin Dashboard

A comprehensive admin dashboard built with MERN stack (MongoDB, Express.js, React, Node.js).

## Project Structure

```
fullstack-admin/
├── client/          # React frontend
└── server/          # Node.js backend
```

## Features

- Modern React dashboard interface
- RESTful API backend with Express.js
- MongoDB database integration
- Authentication and authorization
- Data visualization components
- Responsive design

## Getting Started

### Prerequisites

- Node.js >= 14
- MongoDB
- npm or yarn

### Installation

1. Clone the repository:
```sh
git clone https://github.com/yourusername/fullstack-admin.git
cd fullstack-admin
```

2. Install frontend dependencies:
```sh
cd client
npm install
```

3. Install backend dependencies:
```sh
cd ../server
npm install
```

### Running the Application

1. Start the backend server:
```sh
cd server
npm start
```

2. Start the frontend development server:
```sh
cd client
npm start
```

The application will be available at `http://localhost:3000`

## Environment Variables

Create `.env` files in both client and server directories:

### Server `.env`:
```
PORT=5000
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
```

## Acknowledgments

- React.js
- Express.js
- MongoDB
- Node.js
