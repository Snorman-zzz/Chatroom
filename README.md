# Chat Room Application  
Implement a real-time chat room using **WebSocket** for two-way communication between clients and the server.

## Background  
**WebSocket** is a protocol that enables persistent, bi-directional communication, ideal for real-time applications like chat rooms.

## Instructions  
### 1. Implement the Message Model  
Create the `Message` class in the **chat module** to support these actions:  
- **ENTER**: User joins the chat.  
- **CHAT**: User sends a message.  
- **LEAVE**: User exits the chat.  

### 2. Complete WebSocketChatServer  
Follow the TODOs and method descriptions within `WebSocketChatServer`.

### 3. Run the Application  
Use the following commands:  
```bash
mvn build && mvn spring-boot:run
