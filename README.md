# cs565

# Distributed Systems Projects by Austin Malmin, Purnabhishek Sripathi, and Mounika Maddi.

This repository contains a set of distributed systems projects developed in Java. Each project is designed to demonstrate various distributed systems concepts.

## Table of Contents
1. [Chat Central Server and Client Application](#chat-central-server-and-client-application)
2. [Ring Topology Chat Client](#ring-topology-chat-client)
3. [Transaction Server with Locking](#transaction-server-with-locking)

---

## Chat Central Server and Client Application
[GitHub Link](https://github.com/austinmalmin/cs565)

### Overview
A chat application where multiple clients can connect to a central server and communicate in real-time.

### Features
- `JOIN`: Allows a client to join the chat server.
- `LEAVE`: A client can leave the server.
- `SHUTDOWN`: Shuts down a specific client.
- `SHUTDOWN_ALL`: Terminates all client sessions and shuts down the server.
- `NOTE`: Sends a message or note to the server or specific clients.

### Instructions
To set up and run the project, navigate to the project directory and follow the instructions provided within.

---

## Ring Topology Chat Client
[GitHub Link](https://github.com/austinmalmin/cs565/tree/main/project2%20-%20Ring)

### Overview
A Java-based distributed chat application that operates using a ring topology, enabling participant joining, messaging between clients, participant leaving, shutdowns, and client terminations.

### Features
- Participant joining and leaving.
- Messaging between clients.
- Participant shutdown.
- Terminating client sessions.

### Instructions
To set up and run this project, navigate to the specific directory provided in the GitHub link and follow the detailed instructions there.

---

## Transaction Server with Locking
[GitHub Link](https://github.com/austinmalmin/cs565/tree/main/project3-Transactoin_Server_Locking/Project3Client)

### Overview
A comprehensive transaction server equipped with locking mechanisms to ensure safe and consistent operations.

### Client-Side Features
- **TransactionClient**: Initializes a Transaction Server Proxy and then, using the proxy, runs any number of transactions.
- **TransactionServerProxy**: Represents the server on the client side. It implements and advertises the four operations of the transactional API.

### Server-Side Features
- **TransactionServer**: Initializes the server by reading properties. All managers are created/initialized accordingly, and then the multi-threaded server loop runs.
- **TransactionManager**: Oversees all transactions and spawns TransactionManagerWorkers to handle incoming transactions.
- **AccountManager**: Initializes accounts and implements read/write operations. The operations involve locking mechanisms if they are active.
- **LockManager**: Handles all locks and lock/unlock requests.

### Instructions
To get started with this project, visit the GitHub link provided, and follow the step-by-step guide available within.

## License
[MIT License](LICENSE)

---

This `README.md` provides a general overview of each project. For detailed instructions, configurations, and other specifics, it's good to have a more detailed `README.md` within each project's directory.
