![Real time chat image](https://github.com/user-attachments/assets/743b26ef-768d-4b48-8408-f3ef274d86d6)

.

**💬 Real-Time Chat Application**

.A modern real-time chat application built using Spring Boot WebSockets (STOMP + SockJS) on the backend and pure HTML, CSS, and JavaScript on the frontend.

🚀 Features

Real-time messaging using WebSockets

STOMP protocol with SockJS fallback for reliable connections

Modern and attractive Glassmorphism-style UI

Chat bubbles for sender and receiver

Supports multiple users

Responsive and mobile-friendly design

Built with HTML, CSS, and JavaScript

No page refresh required for message updates

🛠 Tech Stack
🔹 Backend

Java

Spring Boot

Spring WebSocket

STOMP Protocol

SockJS

🔹 Frontend

HTML5

CSS3

JavaScript

Bootstrap 5

**Structure:**
 app/
│
├── pom.xml
│
├── src/
│   ├── main/
│   │   ├── java/
│   │   │   └── com/
│   │   │       └── chat/
│   │   │           └── app/
│   │   │               ├── AppApplication.java
│   │   │               ├── config/
│   │   │               │   └── WebSocketConfig.java
│   │   │               ├── controller/
│   │   │               │   └── ChatController.java
│   │   │               └── model/
│   │   │                   └── ChatMessage.java
│   │   │
│   │   └── resources/
│   │       ├── templates/
│   │       │   └── chat.html
│   │       └── application.properties
│   │
│   └── test/
│       └── java/
│           └── com/
│               └── chat/
│                   └── app/
│                       └── AppApplicationTests.java
│
└── README.md

