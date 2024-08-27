# Hello, Namaste 🙏, Welcome to My AI Chat Application Project!

Thank you for checking out this project! I hope you find it interesting and useful. Feel free to explore the code, give feedback, or contribute. 🚀

---



# AI Chat Application using Google Gemini

## Overview

This is a full-stack AI-powered chat application built using Google Gemini API. The application allows users to interact with an AI chatbot, simulating intelligent responses. The project uses a combination of modern web technologies for both frontend and backend.

## Features

- **Real-time AI Chatting:** Users can have a conversation with the AI powered by Google Gemini.
- **Responsive Frontend:** Built using modern frontend libraries to ensure a seamless user experience across devices.
- **Backend Integration:** Handles API requests, user sessions, and data management.

## Tech Stack

**Frontend:**
- React.js
- Tailwind CSS (or other styling libraries if used)
- Axios (for API requests)

**Backend:**
- Node.js
- Express.js
- MongoDB (for storing chat history)
- Google Gemini API (for AI responses)

## Installation and Setup

1. **Clone the Repository:**
    ```bash
    git clone <repository-url>
    cd ai-chat-application
    ```

2. **Backend Setup:**
    - Navigate to the `backend` directory:
      ```bash
      cd backend
      ```
    - Install dependencies:
      ```bash
      npm install
      ```
    - Set up environment variables:
      - Create a `.env` file in the `backend` directory and configure the following:
        ```
        PORT=5000
        MONGO_URI=your-mongodb-connection-string
        GOOGLE_GEMINI_API_KEY=your-google-gemini-api-key
        ```
    - Start the backend server:
      ```bash
      npm start
      ```

3. **Frontend Setup:**
    - Navigate back to the root directory and move to the frontend folder:
      ```bash
      cd frontend
      ```
    - Install frontend dependencies:
      ```bash
      npm install
      ```
    - Run the frontend development server:
      ```bash
      npm start
      ```

4. **Access the Application:**
    - Open your browser and go to `http://localhost:3000`.

## Usage

- Open the app and start chatting with the AI.
- The chat history is stored, and users can revisit previous interactions.

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create your feature branch (`git checkout -b feature/AmazingFeature`).
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`).
4. Push to the branch (`git push origin feature/AmazingFeature`).
5. Open a pull request.

## License

This project is licensed under the MIT License.
