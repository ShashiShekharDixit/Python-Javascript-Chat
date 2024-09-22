# Python-JavaScript Chat Application

This project is a real-time chat application built using Python for the backend and JavaScript (React.js) for the frontend. It supports features like user authentication, real-time messaging via WebSockets, group chats, and file attachments.

## Features

- User authentication (login/signup)
- Real-time messaging with WebSockets
- Group chat functionality
- Share attachments (images, files, etc.)
- Responsive UI

## Tech Stack

### Backend
- **Python**: Core language for backend.
- **FastAPI/Flask**: Web framework to handle API requests and real-time communication.
- **API**: For real-time messaging between users.

### Frontend
- **React.js**: Library for building dynamic user interfaces.
- **API**: For real-time communication in the browser.
- **HTML5/CSS3**: For layout and styling.

## Installation

### Backend Setup

1. Clone the repository:
    ```bash
    git clone <repository-url>
    cd chat-app-backend
    ```

2. Create and activate a virtual environment:
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows: venv\Scripts\activate
    ```

3. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

4. Run the backend server:
    ```bash
    uvicorn main:app --reload
    ```

### Frontend Setup

1. Navigate to the frontend folder:
    ```bash
    cd chat-app-frontend
    ```

2. Install dependencies:
    ```bash
    npm install
    ```

3. Run the frontend server:
    ```bash
    npm start
    ```

## Usage

1. Start both the backend and frontend servers.
2. Open your browser and go to `http://localhost:3000` to access the chat application.
3. Register a new account or log in with existing credentials.
4. Start messaging!

## Contributing

Feel free to contribute to the project by creating issues, suggesting features, or submitting pull requests. Follow the standard [GitHub flow](https://guides.github.com/introduction/flow/) for contributions.
