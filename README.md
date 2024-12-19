# Real-Time Chat Application - ChatterBox

## Overview
ChatterBox is a real-time chat application designed for seamless communication between users. Built with modern web technologies, it supports live messaging, user authentication, and a user-friendly interface. This application demonstrates the integration of both frontend and backend systems for real-time data exchange.

## Features
- **Real-Time Messaging**: Instant communication powered by WebSockets.
- **User Authentication**: Secure login and signup functionality.
- **Responsive Design**: Optimized for desktop and mobile devices.
- **Message History**: Stores chat history for reference.

## Technologies Used
### Frontend
- **React.js**: For building the user interface.
- **Redux**: For state management.
- **Tailwind CSS**: For custom styling.

### Backend
- **Node.js**: Backend runtime environment.
- **Express.js**: Web framework for API development.
- **Socket.IO**: For real-time communication.
- **MongoDB**: Database for storing user data and messages.

### Others
- **GitHub Actions**: For continuous deployment.


## Installation
### Prerequisites
Ensure you have the following installed:
- Node.js
- MongoDB
- Git

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/HritamBrahmachari/Real-Time-Chat-Application-ChatterBox-.git
   cd Real-Time-Chat-Application-ChatterBox-
   ```

2. Install dependencies:
   ```bash
   # Install backend dependencies
   cd backend
   npm install

   # Install frontend dependencies
   cd ../frontend
   npm install
   ```

3. Configure environment variables:
   - Create a `.env` file in the `backend` directory with the following:
     ```env
     PORT=5000
     MONGO_URI=your_mongo_connection_string
     JWT_SECRET=your_jwt_secret
     ```

4. Start the application:
   ```bash
   # Start the backend
   cd backend
   npm run start

   # Start the frontend
   cd ../frontend
   npm run start
   ```

5. Open your browser and navigate to `http://localhost:3000`.



## API Endpoints
### Authentication
- `POST /api/auth/register`: Register a new user.
- `POST /api/auth/login`: Log in an existing user.

### Messaging
- `GET /api/messages/:roomId`: Fetch chat history for a specific room.
- `POST /api/messages`: Send a new message.

## Usage
1. Register or log in with valid credentials.
2. Join an existing chat room or create a new one.
3. Start sending messages in real time.

## Contributing
Contributions are welcome! Follow these steps:
1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add feature-name"
   ```
4. Push to your branch:
   ```bash
   git push origin feature-name
   ```
5. Create a pull request.

