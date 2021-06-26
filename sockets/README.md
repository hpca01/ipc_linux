# Socket IPC

## Sockets(assuming Linux)

General mechanism to implement communication between different "entities"(aka processes)

### Interface

Provided by Linux OS, to implement socket based communication.

### Types

- Unix Domain
  - Used for IPC for processes in host
- Network Sockets
  - Used for communication for DIFFERENT physical machines.

### How they work in Linux

Steps:
1. Remove socket if already exists
2. Create socket
3. Specify socket name
4. BIND socket
5. Listen
6. Accept
7. Read data
8. Send data
9. Close socket
10. Close connection
11. Remove Socket
12. Exit

