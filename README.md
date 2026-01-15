![Real time chat image](https://github.com/user-attachments/assets/743b26ef-768d-4b48-8408-f3ef274d86d6)

.

**💬 Real-Time Chat Application**

.A modern real-time chat application built using Spring Boot WebSockets (STOMP + SockJS) on the backend and pure HTML, CSS, and JavaScript on the frontend.

**Features**

.Real-time messaging using WebSockets
.STOMP protocol with SockJS fallback
.Modern, attractive UI (Glassmorphism style)
Chat bubbles for sender & receiver
Multiple users supported
Responsive & mobile-friendly
HTML, CSS, and JavaScript frontend
No page refresh required

***Tech Stack***
 **Backend**
  Java
  Spring Boot
  Spring WebSocket
  STOMP Protocol
  SockJS

**Frontend**
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

