# Messaging Service Prototype

## Overview
This project is a prototype of a **Messaging Service** built to demonstrate core features such as user registration, text messaging, and real-time updates. Additionally, optional features such as an AI-powered chatbot and video/audio calling are implemented. The app can be built either as a **web app** (Next.js) or **mobile app** (Ionic React).

## Features

### Core Features
- **User Registration & Authentication**: Secure sign-up and login functionality.
- **Text Messaging**: Send and receive messages between users.
- **Group Chat**: Chat functionality for multiple users.
- **Real-Time Updates**: Instant message updates using web sockets or similar technology.

### Optional Features
- **AI-powered Chatbot**: A chatbot for user interaction.
- **Video/Audio Calling**: Basic functionality for video and audio calls between users.

## Design
- **User Interface**: Clean, intuitive, and easy-to-use interface designed with modern principles such as **Atomic Design**.
  
## App Type
This prototype can be built using:
- **Web App**: Developed using **Next.js** for a scalable, server-side rendered web application.
- **Mobile App**: Built using **Ionic React** for cross-platform mobile support.

## Backend
The backend REST API is developed using **best practices** in modern software development. Below are the details:
- **Programming Language**: Node.js.
- **Database**: Choose between **SQL** (e.g., PostgreSQL) or **noSQL** (e.g., MongoDB), depending on the specific use case.

### API Features:
- Secure authentication (JWT/OAuth).
- Efficient messaging endpoints for sending/receiving messages.
- WebSocket support for real-time message delivery.

## Documentation

### System Design Document
The project includes a detailed **System Design Document** which explains:
- The architecture of the messaging service.
- Design patterns and frameworks used.
- Database design (ER diagrams, collections/tables).
  
### Setup & Installation
To set up the project locally, follow these steps:

1. **Clone the repository**:
    ```bash
    git clone https://github.com/rudrapratap70/IBY_Assignment.git
    cd IBY - Chat Application
    ```

2. **Install dependencies**:
    For the frontend (Next.js/Ionic React):
    ```bash
    npm install
    ```

    For the backend (Node.js):
    ```bash
    # For Node.js
    npm install
    ```

3. **Set up environment variables**:
    Create a `.env` file in the root directory with the necessary environment variables (e.g., database URLs, API keys).

4. **Run the application**:
    ```bash
    # Frontend
    npm run dev
    
    # Backend
    npm start 
    ```

### Dependencies & Libraries Used
- **Frontend**: Next.js/Ionic React, Redux for state management, and any necessary UI libraries.
- **Backend**: Express (Node.js), JWT for authentication, and a WebSocket library for real-time updates.
- **Database**: MongoDB (NoSQL).

### Why These Tools?
- **Next.js**: For server-side rendering and optimized web performance.
- **Ionic React**: For seamless cross-platform mobile development.
- **MongoDB**: Flexible database choices depending on the scalability and structure of the data.

## Contributing
Feel free to fork this repository and create a pull request. We welcome contributions that improve the codebase or add new features!