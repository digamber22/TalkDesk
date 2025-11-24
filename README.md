# Zoom Clone

This is a full-stack web application that replicates the core functionalities of Zoom, a popular video conferencing tool. It includes real-time video and audio communication, screen sharing, and meeting management features.

## Features

*   **Real-time Video and Audio:** High-quality, low-latency video and audio streaming.
*   **Meeting Rooms:** Create and join password-protected meeting rooms.
*   **User Authentication:** Secure user registration and login.
*   **Screen Sharing:** Share your screen with other participants in the meeting.

## Tech Stack

**Frontend:**

*   React
*   Socket.IO Client
*   Material UI

**Backend:**

*   Node.js
*   Express.js
*   Socket.IO
*   MongoDB

## Getting Started

### Prerequisites

*   Node.js
*   MongoDB

### Installation

1.  **Clone the repository:**
    ```
    git clone <your-new-repo-url>
    ```
2.  **Install backend dependencies:**
    ```
    cd backend
    npm install
    ```
3.  **Install frontend dependencies:**
    ```
    cd ../frontend
    npm install
    ```
4.  **Set up environment variables:**
    *   Create a `.env` file in the `backend` directory and add the following:
        ```
        MONGO_URI=<your_mongodb_connection_string>
        PORT=8000
        CORS_ORIGIN=http://localhost:3000
        ```
    *   Create a `.env` file in the `frontend` directory and add the following:
        ```
        REACT_APP_BACKEND_URL=http://localhost:8000
        ```
5.  **Run the application:**
    *   **Backend:**
        ```
        cd backend
        npm start
        ```
    *   **Frontend:**
        ```
        cd frontend
        npm start
