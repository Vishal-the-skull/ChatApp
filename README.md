# ChatApp
💬 Mini Chat Application (Python)

A simple client-server chat application built using Python sockets and multithreading.
This project demonstrates basic computer networking concepts such as socket programming, TCP connections, message broadcasting, and concurrency.

🚀 Features

Real-time communication between multiple clients

Nickname-based identification for users

Server broadcasts messages to all connected clients

Handles client join/leave notifications

Multithreaded — supports multiple simultaneous users

Easy to run and extend

🧠 Concepts Used

This project demonstrates the following computer network concepts:

Socket Programming – For establishing TCP connections between clients and server.

IP Address & Port Binding – Server binds to a specific IP and port using bind().

TCP Communication – Reliable, ordered data delivery using socket.SOCK_STREAM.

Concurrency (Threads) – Each client runs on a separate thread to handle multiple users.

Message Broadcasting – Server sends each message to all active clients.

Client-Server Model – One centralized server manages all chat communication.

🧩 How It Works

Server starts first and listens on a chosen IP and port.

Clients connect to the server using the same IP and port.

Each client chooses a nickname.

Messages sent by one client are broadcast to all others through the server.

When a client disconnects, others are notified.
