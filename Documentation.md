Here is a brief documentation for the `Multithreaded/Client.java` file:

---

# Client Class Documentation

## Overview
The `Client` class simulates 100 concurrent clients connecting to a server at `localhost` on port `8010`. Each client runs in its own thread, sends a greeting message, and prints the server's response.

## Key Features
- Uses Java sockets for network communication.
- Employs try-with-resources for safe management of streams and sockets.
- Demonstrates multithreading by launching 100 client threads.

## Usage
- Run the `main` method to start 100 client threads.
- Each thread connects to the server, sends a message, and prints the server's reply.

## Important Notes
- There is a duplicate `Client` class in `SingleThreaded/Client.java`, which may cause compilation issues. Only one public class named `Client` should exist per package.

## Dependencies
- Java Standard Library (`java.net`, `java.io`)

---
