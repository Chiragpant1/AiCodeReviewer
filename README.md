<h1>AI-Powered Code Reviewer using MERN Stack 🚀</h1><BR>
# AichatApp

AichatApp is a full-stack application built with a MERN stack (MongoDB, Express, React, Node.js) that allows users to create and manage projects, collaborate with other users, and utilize AI to generate content and review code.

## Features

- User authentication (register, login, logout)
- Project creation and management
- Collaborate with other users on projects
- Real-time messaging within projects
- AI-powered content generation and code review

## Technologies Used

### Backend

- Node.js
- Express
- MongoDB
- Mongoose
- JWT for authentication
- Redis for session management
- Google Generative AI for content generation

### Frontend

- React
- Vite
- Tailwind CSS
- Socket.io for real-time communication

## Installation

### Prerequisites

- Node.js
- MongoDB
- Redis

### Backend

1. Navigate to the `backend` directory:

    ```sh
    cd backend
    ```

2. Install the dependencies:

    ```sh
    npm install
    ```

3. Create a `.env` file in the [backend](http://_vscodecontentref_/1) directory and add the following environment variables:

    ```env
    PORT=3000
    MONGODB_URI=your_mongodb_uri
    JWT_SECRET=your_jwt_secret
    GOOGLE_AI_KEY=your_google_ai_key
    REDIS_HOST=your_redis_host
    REDIS_PORT=your_redis_port
    REDIS_PASSWORD=your_redis_password
    ```

4. Start the backend server:

    ```sh
    npm start
    ```

### Frontend

1. Navigate to the [frontend](http://_vscodecontentref_/2) directory:

    ```sh
    cd frontend
    ```

2. Install the dependencies:

    ```sh
    npm install
    ```

3. Create a `.env` file in the [frontend](http://_vscodecontentref_/3) directory and add the following environment variables:

    ```env
    VITE_API_URL=http://localhost:3000
    ```

4. Start the frontend development server:

    ```sh
    npm run dev
    ```

## Usage

1. Open your browser and navigate to [http://localhost:3000](http://_vscodecontentref_/4) for the backend and [http://localhost:5173](http://_vscodecontentref_/5) for the frontend.
2. Register a new user or login with an existing account.
3. Create a new project and invite collaborators.
4. Use the real-time messaging feature to communicate with your team.
5. Utilize the AI-powered content generation and code review features to enhance your project.



## License

This project is licensed under the ISC License.




