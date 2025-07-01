# 💬 Realtime Chat Application using Spring Boot & WebSocket

A **real-time group chat application** built using **Spring Boot**, **WebSocket**, **STOMP**, and **SockJS**. Users can join chat rooms, send/receive messages live, and leave — all in a seamless, interactive UI.

---

## 🚀 Features

✅ Real-time messaging via WebSocket  
✅ Join/Leave chat room notifications  
✅ Clean frontend UI with user color-coded messages  
✅ Password-protected login  
✅ STOMP protocol support for message routing  
✅ SockJS fallback for non-WebSocket browsers  
✅ Fully built with Spring Boot (Java)

---

## 🛠️ Tech Stack

| Technology       | Description                            |
|------------------|----------------------------------------|
| Spring Boot      | Backend framework (Java)               |
| WebSocket        | Real-time bidirectional communication  |
| STOMP            | Messaging protocol over WebSocket      |
| SockJS           | WebSocket fallback support             |
| JavaScript       | Frontend interactivity                 |
| HTML + CSS       | Frontend layout & styling              |
| Lombok           | Boilerplate reduction in models        |
| Maven            | Dependency management & build tool     |

---

## 📁 Project Structure
spring-boot-websocket/
│
├── config/
│   ├── WebSocketConfig.java              # Configures WebSocket, STOMP, SockJS
│   └── WebSocketEventListener.java       # Listens to connect/disconnect events
│
├── controller/
│   └── ChatController.java               # Handles register and send endpoints
│
├── model/
│   └── ChatMessage.java                  # Message model with JOIN, CHAT, LEAVE
│
├── resources/
│   ├── static/
│   │   ├── js/
│   │   │   └── main.js                   # Handles frontend connection & chat logic
│   │   └── css/                          # Custom styles (if any)
│   └── templates/
│       └── index.html                    # Main chat page UI
│
├── application.properties                # Spring Boot app settings
├── pom.xml                               # Maven configuration
└── README.md                             # Project documentation
