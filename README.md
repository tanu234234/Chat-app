# Real-Time Chat Application

## Overview

This project is a **Real-Time Chat Application** built using **Node.js, Express, and Socket.IO**.
It enables multiple users to communicate instantly through a web interface. Messages sent by one user are broadcast to all connected users in real time.

## Features

* Real-time messaging using **Socket.IO**
* Multiple users can chat simultaneously
* Username-based messages
* Simple and responsive chat interface
* Frontend and backend integration

## Technologies Used

* Node.js
* Express.js
* Socket.IO
* HTML
* CSS
* JavaScript

## Project Structure

```
chat-app
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
```

## Installation and Setup

1. Clone the repository

```
git clone https://github.com/tanu234234/Chat-app.git
```

2. Navigate to the project folder

```
cd Chat-app
```

3. Install dependencies

```
npm install
```

4. Start the server

```
node server.js
```

5. Open the application in your browser

```
http://localhost:3000
```

## Usage

1. Enter your username.
2. Type a message in the chat box.
3. Messages will appear instantly for all connected users.

## Conclusion

This project demonstrates how **WebSocket communication using Socket.IO** enables real-time interaction between multiple users through a simple web-based chat system.
