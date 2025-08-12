# MULTITHREADED-CHAT-APPLICATION

COMPANY: CODTECH IT SOLUTIONS

NAME : A.BRITTO RAJ

INTERN ID : CT04DZ331

DOMAIN : JAVA

DURATION : 4 WEEKS

MENTOR : NEELA SANTHOSH KUMAR




# Java Client-Server Chat Application

## Overview

This is a simple Java console-based chat application that enables multiple clients to communicate with each other through a central server.  

It demonstrates the use of *Java Sockets, **multithreading*, and basic networking concepts to handle multiple simultaneous client connections.

The project is aimed at beginners who want to learn how to build network applications in Java and manage multiple clients using threads.

## Features

- Real-time messaging between multiple clients
- Multi-threaded server to handle multiple connections simultaneously
- Broadcasts messages from one client to all connected clients
- Console-based interface for simplicity
- Runs locally without the need for an internet connection

## Technologies Used

- Java (Core Java)
- java.net.ServerSocket and java.net.Socket for networking
- Multithreading using Thread class
- Standard I/O streams (BufferedReader, PrintWriter)

## How It Works

1. *Start Server* – The server listens on a specified port for incoming client connections.
2. *Client Connection* – Each client connects to the server using its IP address and port.
3. *Thread Handling* – The server creates a separate thread for each connected client.
4. *Message Broadcasting* – Messages sent by a client are received by the server and broadcast to all other clients.
5. *Disconnection Handling* – When a client disconnects, the server removes it from the active client list.

## Running the Project in IntelliJ IDEA

1. Create a new Java project in IntelliJ IDEA.
2. Inside the src folder, create two Java files: Server.java and Client.java.
3. Copy the provided server and client code into their respective files.
4. *Run the Server:*
   - Right-click Server.java → *Run 'Server.main()'*
5. *Run Multiple Clients:*
   - Right-click Client.java → *Run 'Client.main()'*  
   - Repeat in multiple tabs or windows to simulate multiple users.
6. Start chatting — messages from one client will appear on all others.

## Output

<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/5ca5b9e6-4c1c-4775-a189-e0a0ee04595e" />

<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/a9012939-45c0-4def-97a8-579881896483" />

<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/4eb7091f-5f7b-49fd-9ac3-6b8f6c0150f0" />

https://github.com/user-attachments/assets/86cafd33-3d72-4b5c-b05d-96ed2ba4cd62
