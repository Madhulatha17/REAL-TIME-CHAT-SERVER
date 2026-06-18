# Socket Events Documentation

# Connection Event

Event:
connect

Description:
Triggered when a user connects to the chat server.

---

# Join Room Event

Event:
joinRoom

Payload:

{
"room": "general"
}

Description:
Allows a user to join a specific chat room.

---

# Chat Message Event

Event:
chatMessage

Payload:

{
"room": "general",
"user": "John",
"text": "Hello Everyone"
}

Description:
Broadcasts messages to all users within the selected room.

---

# Disconnect Event

Event:
disconnect

Description:
Triggered when a user leaves the server.
