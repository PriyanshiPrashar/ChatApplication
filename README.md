# Real-Time Chat Application

A real-time chat application built using **Spring Boot**, **WebSocket**, **STOMP Protocol**, and **Thymeleaf** that enables users to communicate instantly through a simple web interface.

This project demonstrates real-time messaging using WebSocket communication between server and clients.

---

## Features

- Real-Time Messaging
- WebSocket Communication
- STOMP Messaging Protocol
- Interactive Chat Interface
- Spring Boot Backend
- Thymeleaf Frontend
- Message Broadcasting
- Lightweight and Fast

---

## Technologies Used

- Java
- Spring Boot
- WebSocket
- STOMP
- Thymeleaf
- Maven
- HTML/CSS/JavaScript

---

## Project Structure

```text
Real-Time-Chat-Application/
│
├── src/
│   ├── main/
│   │   ├── java/
│   │   │   └── com.chat.app/
│   │   │       ├── config/
│   │   │       │   └── webSocketConfig.java
│   │   │       │
│   │   │       ├── Controller/
│   │   │       │   ├── ChatController.java
│   │   │       │   └── HomeController.java
│   │   │       │
│   │   │       ├── Model/
│   │   │       │   └── ChatMessage.java
│   │   │       │
│   │   │       ├── Repository/
│   │   │       │   └── ChatRepository.java
│   │   │       │
│   │   │       └── AppApplication.java
│   │   │
│   │   └── resources/
│   │       ├── static/
│   │       ├── templates/
│   │       │   └── chat.html
│   │       └── application.properties
│   │
│   └── test/
│
├── pom.xml
├── .gitignore
└── README.md
```

---

## Functionalities

- Multiple users can chat in real time
- Instant message delivery
- Dynamic frontend updates
- WebSocket-based communication
- Broadcast messages to connected users

---

## Installation & Setup

### Clone Repository

```bash
git clone https://github.com/PriyanshiPrashar/RealTimeChatApplication.git
```

---

### Open Project

Open the project in:
- IntelliJ IDEA
- VS Code
- Eclipse

---

### Run Application

Using Maven:

```bash
mvn spring-boot:run
```

Or run:

```text
AppApplication.java
```

---

## Access Application

Open browser:

```text
http://localhost:8080
```

---

## WebSocket Endpoint

Example WebSocket endpoint:

```text
/ws
```

Message Broker:

```text
/topic
```

Application Destination Prefix:

```text
/app
```

---

## Future Improvements

- User Authentication
- Private Chat Rooms
- Online User Status
- Message Persistence
- Emoji Support
- File Sharing
- Chat Notifications

---

## Learning Concepts

This project demonstrates:

- Spring Boot Development
- WebSocket Integration
- STOMP Messaging
- MVC Architecture
- Real-Time Communication
- Frontend-Backend Integration

---

## Screenshots

Add screenshots of:
- Chat Interface
- Real-Time Messaging
- WebSocket Communication

---

## Author

Priyanshi Prashar

GitHub:
https://github.com/PriyanshiPrashar

---

## License

This project is developed for educational and learning purposes.