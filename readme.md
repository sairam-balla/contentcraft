# Server

This is the backend server for the project, built with Node.js, Express, and MongoDB.

## Prerequisites

- Node.js (v16 or later recommended)
- MongoDB Atlas account or local MongoDB instance
- npm (comes with Node.js)

## Installation

1. Clone the repository.
2. Navigate to the `server` directory.
3. Run `npm install` to install dependencies.

## Running the Server

To start the server in development mode with automatic restarts on code changes:

```bash
npm run dev
```

The server listens on port 8080 by default.

## Environment Variables

The server uses environment variables managed by `dotenv`. Make sure to create a `.env` file in the `server` directory with the necessary variables, such as your MongoDB connection string.

## API Routes

- `/api/auth` - Authentication routes
- `/api/user` - User-related routes
- `/api/feed` - Feed-related routes
- `/api/admin` - Admin-related routes

## Dependencies

- express
- mongoose
- cors
- dotenv
- bcryptjs
- jsonwebtoken
- axios
- nodemon (development)

# Client

This is the frontend client for the project, built with React and Vite.

## Prerequisites

- Node.js (v16 or later recommended)
- npm (comes with Node.js)

## Installation

1. Navigate to the `client` directory.
2. Run `npm install` to install dependencies.

## Running the Client

To start the development server with hot module replacement:

```bash
npm run dev
```

The client will be available at `http://localhost:5173` by default.

## Building for Production

To build the client for production deployment:

```bash
npm run build
```

## Dependencies

- react
- react-dom
- @reduxjs/toolkit
- react-redux
- react-router-dom
- axios
- tailwindcss
- lucide-react
- react-hot-toast

## credentials

for users:
email: user123@email.com
password: user123

for admin:
email: test123@email.com
password: test123
