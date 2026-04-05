**COMPANY**: CODTECH IT SOLUTIONS PVT.LTD

**NAME**: Tanushree K A

**INTERN ID**: CTIS6658

**DOMAIN**: FULL STACK WEB DEVELOPMENT

**DURATION**: 4 WEEKS

**MENTOR**: NEELA SANTHOSH

# Chat Application

# Overview

The Real-Time Chat Application is a web-based messaging platform developed using Node.js, Express.js, and Socket.IO. The primary purpose of this project is to demonstrate how modern web technologies can be used to enable instant communication between multiple users through a browser-based interface. The application allows users to send and receive messages in real time without the need to refresh the web page.

Real-time communication has become a fundamental part of many modern web applications such as messaging platforms, collaboration tools, customer support systems, and social media platforms. This project provides a simplified implementation of such a system by utilizing WebSocket technology through the Socket.IO library. Unlike traditional HTTP-based communication where the client repeatedly requests updates from the server, WebSockets allow a continuous connection between the client and the server. This persistent connection enables messages to be transmitted instantly between users.

The application consists of both frontend and backend components that work together to deliver the chat functionality. The frontend is responsible for presenting the chat interface, capturing user input, and displaying messages received from the server. It is developed using HTML for structure, CSS for styling, and JavaScript for handling user interactions and communication with the server.

The backend is built using Node.js with Express.js, which acts as the server responsible for managing connections and handling communication between users. Socket.IO is integrated into the server to establish real-time communication channels. When a user sends a message, the server receives the message and broadcasts it to all other connected users instantly. This ensures that everyone in the chat sees the message at the same time.

The application also supports multiple users interacting simultaneously. Each user joins the chat using a username, and all messages are displayed with the sender’s name for clear identification. The interface updates dynamically whenever a new message is received, providing a smooth and interactive chat experience.

This project is a practical demonstration of full-stack web development, showing how frontend and backend technologies integrate to build real-time applications. It also helps developers understand concepts such as event-driven communication, WebSocket connections, and live data synchronization between multiple clients.

# Features
Real-time messaging using Socket.IO
Instant communication between multiple connected users
Username-based chat messages for easy identification
Automatic broadcasting of messages to all users
Dynamic message updates without refreshing the page
Simple and responsive user interface
Efficient client-server communication
Lightweight and easy-to-understand project structure
Demonstrates real-time event-based programming
Supports multiple browser sessions simultaneously

# Technologies Used

**Node.js**
Node.js is a server-side JavaScript runtime environment used to build scalable network applications. It allows JavaScript to run outside the browser and is commonly used for backend development.

**Express.js**
Express.js is a lightweight web framework for Node.js that simplifies the process of creating servers and handling HTTP requests. It is used in this project to manage the server and routing functionality.

**Socket.IO**
Socket.IO is a powerful library that enables real-time bidirectional communication between clients and servers. It uses WebSocket technology to allow instant data exchange without requiring page reloads.

**HTML**
HTML is used to structure the chat interface, including the message display area, input fields, and buttons.

**CSS**
CSS is used to style the chat application and make the interface visually appealing and responsive.

**JavaScript**
JavaScript handles the client-side logic, including capturing user messages, sending them to the server, and displaying messages received from other users.

# Project Structure
CHAT APPLICATION
│
├── server.js
├── package.json
├── package-lock.json
├── README.md
│
└── public
    ├── index.html
    ├── style.css
    └── script.js

**server.js**
Contains the backend server code responsible for managing connections and handling real-time communication.

**package.json**
Stores project metadata and dependency information required for the application.

**package-lock.json**
Ensures consistent dependency installation across different environments.

**public/index.html**
Defines the layout and structure of the chat interface.

**public/style.css**
Contains styling rules that control the visual appearance of the application.

**public/script.js**
Handles client-side logic, user interaction, and Socket.IO communication with the server.

# Usage

Users can join the chat by entering a username and sending messages through the chat interface. When a message is sent, it is transmitted to the server and immediately broadcast to all connected users. Every user in the chat can see the message appear instantly in their interface.

Multiple users can participate in the chat simultaneously by opening the application in different browser tabs or devices. The system ensures that messages from all users are synchronized and displayed in real time.

# Conclusion

This project demonstrates how real-time communication systems can be built using Node.js and Socket.IO. By integrating frontend technologies with a Node.js backend server, the application provides a practical example of a live chat system where users can exchange messages instantly. The project highlights the power of WebSocket-based communication and showcases how event-driven architectures enable interactive and dynamic web applications.

# Output 

Server 1:

<img width="685" height="665" alt="Image" src="https://github.com/user-attachments/assets/b095c15d-dcb9-4fd8-a714-4af0cc701613" />

Server 2:

<img width="744" height="671" alt="Image" src="https://github.com/user-attachments/assets/e8584884-3fdc-4fc6-9f25-9e44f5796864" />

