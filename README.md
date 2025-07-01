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
│ ├── WebSocketConfig.java # WebSocket setup with STOMP & SockJS
│ └── WebSocketEventListener.java # Handles user disconnect events
│
├── controller/
│ └── ChatController.java # Chat endpoints for join/send
│
├── model/
│ └── ChatMessage.java # Message model (JOIN, CHAT, LEAVE)
│
├── resources/
│ ├── static/
│ │ ├── js/main.js # Handles frontend connection logic
│ │ └── css/ # Add CSS styling as needed
│ └── templates/index.html # Main UI page
│
├── pom.xml # Maven config file
└── application.properties # Spring Boot config
