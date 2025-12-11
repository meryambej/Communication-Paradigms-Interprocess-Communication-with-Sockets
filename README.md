# Multi-User Chat System with Java Sockets

## But first What is a Socket?
A **socket** is basically an endpoint or a plugin that allows communication between devices over a network. It is uniquely identified by an **IP address** and a **port number**.

---

## Project Overview
I implemented a **server/client chat system** in Java using sockets : Multi-Threaded Groupchat 

### Server
1. Binds a socket to a chosen IP address and port.  
2. Listens for incoming client connections.  
3. Accepts a connection and creates a dedicated socket for that client.  
4. Receives messages from the client and echoes them back until the client disconnects.  

### Client
1. Connects to the server using its IP address and port.  
2. Sends a message to the server.  
3. Receives the server’s reply.  
4. Prints the reply, then closes the connection.  

---

## How to Run

### Server
- Run the `ServerClass` in your IDE (exp, IntelliJ IDEA).  

### Client
- Open multiple terminals (PowerShell or similar).  
- Run the client class with:  
```bash
java -cp bin client.SocketClient

