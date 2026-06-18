# System Architecture

Client
|
v
Socket.IO Connection
|
v
Node.js Server
|
v
Chat Rooms

Workflow:

1. User connects to server.
2. User joins a chat room.
3. User sends a message.
4. Server broadcasts message to room members.
5. Users receive messages in real time.

The architecture supports multiple chat rooms and concurrent users using WebSocket communication.
