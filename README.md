<h1>AI-Powered Code Reviewer using MERN Stack 🚀</h1><BR>

AI Code Reviewer

This project is an AI-powered code reviewer application. It consists of a backend service that uses Google Generative AI to review code and a frontend interface built with React to interact with the AI reviewer.


## Backend

The backend is built with Node.js and Express. It uses the Google Generative AI API to provide code reviews.

### Installation

1. Navigate to the `BackEnd` directory:
    ```sh
    cd BackEnd
    ```

2. Install the dependencies:
    ```sh
    npm install
    ```

3. Create a `.env` file in the [BackEnd](http://_vscodecontentref_/15) directory and add your Google Generative AI API key:
    ```
    GOOGLE_GEMINI_KEY=your_api_key_here
    ```

4. Start the server:
    ```sh
    node [server.js](http://_vscodecontentref_/16)
    ```

The backend server will run on `http://localhost:3000`.

## Frontend

The frontend is built with React and Vite. It allows users to input code, send it to the backend for review, and display the review.

### Installation

1. Navigate to the `Frontend` directory:
    ```sh
    cd Frontend
    ```

2. Install the dependencies:
    ```sh
    npm install
    ```

3. Start the development server:
    ```sh
    npm run dev
    ```

The frontend application will run on `http://localhost:5173`.

## Usage

1. Start both the backend and frontend servers.
2. Open the frontend application in your browser.
3. Input your code in the editor and click the "Review" button.
4. The AI-generated review will be displayed on the right side of the screen.

## License

This project is licensed under the ISC License.
