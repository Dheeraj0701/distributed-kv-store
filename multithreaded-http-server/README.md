# Multithreaded HTTP Server

A multithreaded HTTP server built in C/C++ for handling concurrent client connections.

## Features

- Multithreaded request handling
- TCP/IP socket-based communication
- Concurrent connection support

## Build

**Note:** Uses POSIX APIs (pthreads, sockets). Build on Linux/Unix or Windows (WSL/MinGW).

```bash
# Using Make
make

# Or compile manually (GCC)
gcc -Wall -pthread -o server src/server.c
```

## Run

```bash
./server [port]
# Default port: 8080
```

## Project Structure

```
multithreaded-http-server/
├── src/
│   └── server.c
├── Makefile
└── README.md
```
