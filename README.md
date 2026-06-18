# REAL-TIME-CHAT-SERVER

# Real-Time Chat Server

## Project Overview

This project implements a real-time chat backend using Node.js, Express.js, and Socket.IO. The server enables instant communication between connected users and supports multiple chat rooms for organized conversations.

## Objective

To develop a backend system capable of handling real-time communication using WebSockets and Socket.IO, allowing users to join chat rooms and exchange messages instantly.

## Features

* Real-Time Messaging
* Multiple Chat Room Support
* User Connection Management
* Socket.IO Integration
* WebSocket-Based Communication
* Event-Driven Architecture

## Technologies Used

* Node.js
* Express.js
* Socket.IO
* JavaScript

## System Functionality

### User Connection

Users can connect to the chat server through Socket.IO.

### Chat Rooms

Users can join specific chat rooms for group communication.

### Real-Time Messaging

Messages are delivered instantly to all users within the selected chat room.

### User Disconnection

The server detects and handles user disconnections automatically.

## Socket Events

### connect

Triggered when a user establishes a connection with the server.

### joinRoom

Allows users to join a specific chat room.

### chatMessage

Enables users to send and receive messages in real time.

### disconnect

Triggered when a user leaves the server.

## Deliverable

A Node.js-based server capable of supporting real-time communication and multiple chat rooms using Socket.IO.

## Result

The chat server successfully handles user connections, room management, and real-time message broadcasting through WebSocket communication.

## Conclusion

This project demonstrates the implementation of a scalable real-time communication backend using Node.js and Socket.IO. The system supports multiple chat rooms and provides efficient event-driven messaging between connected users.
