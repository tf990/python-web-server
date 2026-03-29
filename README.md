# Python Web Server

A simple HTTP web server built using Python sockets that handles client requests and serves files. This project demonstrates core networking concepts including TCP connections, request parsing, and HTTP response handling.

---

## Features
- Listens for incoming client connections on port 6789
- Processes HTTP GET requests from a web browser
- Serves requested files from the local directory
- Returns a 404 error if the requested file is not found
- Uses low-level socket programming for direct client-server communication

---

## Technologies Used
- Python (socket programming)
- HTML

---

## How to Run

1. Open a terminal in the project folder

2. Run the server:
   python server.py

3. Open your browser and go to:
   http://localhost:6789/filename.html

(Replace `filename.html` with any file in the directory, e.g. index.html)

---

## Project Overview

This project implements a basic web server using Python's socket module. The server listens for incoming connections, receives HTTP requests, and responds by serving the requested file.

When a client sends a request:
- The server extracts the requested file name from the HTTP message
- Reads the file from the local directory
- Sends an HTTP 200 OK response if the file exists
- Sends a 404 Not Found response if the file does not exist

---

## Future Improvements
- Support for additional file types (CSS, images, JavaScript)
- Handle multiple client requests concurrently
- Improve request parsing and validation
- Add logging for incoming requests

---

## Author
Tazrian Faisel
