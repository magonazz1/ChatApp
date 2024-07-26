# ChatApp

Welcome to the **Realtime ChatApp** project! This application allows users to engage in real-time conversations, either one-on-one or in group chats, with the ability to send media content to one another.

## Table of Contents

1. [Overview](#overview)
2. [Technologies Used](#technologies-used)
3. [Setup Instructions](#setup-instructions)
4. [Development Workflow](#development-workflow)
5. [Features](#features)
6. [Troubleshooting](#troubleshooting)
7. [License](#license)

## Overview

The **ChatApp** is designed to offer a seamless and interactive chat experience. Users can communicate with each other through private messages or group chats. Media sharing is supported, making the communication more vibrant and engaging.

## Technologies Used

![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=node.js&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat&logo=express&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat&logo=vite&logoColor=white)
![Axios](https://img.shields.io/badge/Axios-5A29E3?style=flat&logo=axios&logoColor=white)
![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=flat&logo=visual-studio-code&logoColor=white)
![Nodemon](https://img.shields.io/badge/Nodemon-76D04B?style=flat&logo=nodemon&logoColor=white)

- **Backend:** Node.js, Express, CORS, Axios
- **Frontend:** React, Vite
- **Development Tools:** VS Code, Nodemon
- **API Service:** ChatEngine.io

## Setup Instructions

### Prerequisites

- [Node.js](https://nodejs.org/) (includes npm)
- [VS Code](https://code.visualstudio.com/)

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/ChatApp.git
cd ChatApp
```

### 2. Install Backend Dependencies

1. Navigate to the backend directory:

    ```bash
    cd backend
    ```

2. Initialize the project and install dependencies:

    ```bash
    npm init -y
    npm install express cors axios
    npm install --save-dev nodemon
    ```

### 3. Set Up PowerShell Execution Policy (if needed)

If you encounter an error related to PowerShell execution policy:

```bash
Set-ExecutionPolicy -Scope CurrentUser -ExecutionPolicy RemoteSigned
```

### 4. Install Frontend Dependencies

1. Navigate to the frontend directory:

    ```bash
    cd ../frontend
    ```

2. Create a React project with Vite:

    ```bash
    npm create vite@latest
    ```

3. Install additional dependencies:

    ```bash
    npm install
    ```

## Development Workflow

### Running the Backend Server

1. Start the backend server using Nodemon:

    ```bash
    cd backend
    npx nodemon index.js
    ```

2. Your server will be available at `http://localhost:3001`.

### Running the Frontend

1. Start the React development server:

    ```bash
    cd frontend
    npm run dev
    ```

2. Your React application will be available at `http://localhost:5173`.

## Features

- **Real-time Messaging:** Engage in one-on-one or group conversations.
- **Media Sharing:** Send and receive images, videos, and other media content.
- **Cross-Platform Compatibility:** Communicate from anywhere in the world.

## Troubleshooting

### Common Issues

- **PowerShell Execution Policy Issue:**
  If you face issues with running npm commands due to execution policy restrictions, use the command:

  ```bash
  Set-ExecutionPolicy -Scope CurrentUser -ExecutionPolicy RemoteSigned
  ```

- **403 Forbidden Error:**
  Ensure that you have the correct API keys and permissions set up. Check your [ChatEngine.io](https://chatengine.io) account and make sure your requests are authenticated.

### Additional Help

For further assistance, you can consult the following resources:

- [React Documentation](https://reactjs.org/docs/getting-started.html)
- [Node.js Documentation](https://nodejs.org/en/docs/)
- [ChatEngine.io API Documentation](https://chatengine.io/docs/)

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.