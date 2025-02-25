AI-Powered Code Reviewer using MERN Stack 🚀
This project leverages artificial intelligence to analyze, review, and suggest improvements for code, enhancing development efficiency. It uses the MERN Stack (MongoDB, Express, React, Node.js) integrated with Google Generative AI to provide AI-powered insights. This is an excellent project for learning full-stack development with AI integration.

Table of Contents
Project Overview
Technologies Used
Features
Setup and Installation
Usage
Development Process
Contributing
License
Project Overview
The AI-Powered Code Reviewer is designed to automate the process of reviewing and improving code. By integrating artificial intelligence, the app analyzes code provided by the user, generates suggestions, and provides actionable feedback to improve code quality. This project uses the MERN stack with AI for dynamic code reviews.

Project Overview
The AI-Powered Code Reviewer is designed to automate the process of reviewing and improving code. By integrating artificial intelligence, the app analyzes code provided by the user, generates suggestions, and provides actionable feedback to improve code quality. This project uses the MERN stack with AI for dynamic code reviews.

Technologies Used
MERN Stack:
MongoDB: Database for storing user information and code reviews.
Express.js: Backend framework for building the API.
React.js: Frontend for building the user interface.
Node.js: Server-side JavaScript runtime environment.
Google Generative AI: To provide code review suggestions and feedback.
Vite: Frontend development server for faster React setup.
PrismJs: Syntax highlighting for better code visualization.
Axios: HTTP client to handle requests between frontend and backend.
CORS: For cross-origin resource sharing between frontend and backend.
Markdown: For rendering and styling code reviews.
Features
AI Code Review: Leverages Google Generative AI to analyze code and offer improvement suggestions.
Syntax Highlighting: PrismJs is integrated to display code with proper syntax highlighting for better readability.
Markdown Support: Reviews and suggestions are displayed in Markdown format for enhanced styling and readability.
CORS Support: Cross-origin resource sharing for smooth communication between the frontend and backend.
Responsive UI: Clean and modern user interface built with React and Vite.
Setup and Installation
Prerequisites
Before starting, make sure you have the following installed on your machine:

Node.js (with npm)
MongoDB (or a cloud MongoDB instance)
API Key for Google Generative AI
Steps to Setup
Clone the Repository:

bash
Copy
git clone https://github.com/yourusername/ai-powered-code-review.git
cd ai-powered-code-review
Install Backend Dependencies: Navigate to the backend folder and install dependencies:

bash
Copy
cd backend
npm install
Set up Environment Variables:

Create a .env file in the backend directory and add your Google AI API key and MongoDB connection URL.
Run the Backend: Start the backend server:

bash
Copy
npm start
Install Frontend Dependencies: Navigate to the frontend folder and install dependencies:

bash
Copy
cd frontend
npm install
Run the Frontend: Start the React app:

bash
Copy
npm run dev
Access the App: Open your browser and visit http://localhost:3000 to start using the AI-powered code review tool.

Usage
Input Code: Write or paste your code into the provided input box on the frontend.
Get Review: Submit your code to receive a review powered by Google Generative AI.
Review Suggestions: The AI will suggest improvements, which will be displayed in the UI.
Syntax Highlighting: Code is displayed with syntax highlighting using PrismJs for readability.
Markdown Rendering: Review feedback is rendered using Markdown for better styling.
