Vigenère Cipher Application
An interactive Vigenère Cipher tool using C++ for encryption/decryption, a Node.js server, and a web frontend (HTML, CSS, JS). Users enter text and a keyword to encrypt or decrypt messages. Works on Windows with MinGW. Features include a user-friendly interface, error handling, and cross-platform compatibility.

Project Overview
This project implements an interactive Vigenère Cipher encryption and decryption tool using a C++ backend, a Node.js server, and a web-based frontend (HTML, CSS, JavaScript). Users can enter text and a key to encrypt or decrypt messages securely using the Vigenère Cipher, a method of encrypting alphabetic text by using a keyword to shift characters in a cyclical manner.

Features
User-Friendly Interface: A clean, responsive UI that allows users to easily enter the text and key, choose between encryption and decryption, and view the output instantly.
Vigenère Cipher Algorithm: The backend C++ code handles the encryption and decryption logic, extending the keyword cyclically and processing each character shift.
Cross-Platform Compatibility: Designed to run on Windows with MinGW, leveraging a Node.js server to handle HTTP requests and communicate with the C++ executable.
Error Handling and Logging: The Node.js server provides detailed error messages and logs to aid in debugging and ensure a smooth user experience.
Technologies Used
Frontend: HTML, CSS, JavaScript

HTML/CSS: For structure and styling of the user interface.
JavaScript: Handles user inputs, communicates with the backend, and displays the results.
Backend:

C++: Implements the Vigenère Cipher algorithm for encryption and decryption.
Node.js: Acts as an intermediary, compiling and executing the C++ code upon receiving user requests.
MinGW: A minimalist development environment for compiling and running the C++ code on Windows.
Setup Instructions
Prerequisites
Node.js: Required to run the server. Download from https://nodejs.org/.
MinGW: Required for compiling C++ code on Windows. Download from http://mingw-w64.org/.
Installation
Clone the Repository: Clone the repository by running the following command in your terminal:

git clone https://github.com/yourusername/vigenere-cipher-app.git

Change into the directory:

cd vigenere-cipher-app

Install Node.js Dependencies: Install necessary Node.js packages:

npm install

Compile C++ Code and Start the Server: Run the Node.js server, which will compile cipher.cpp and start the application:

node server.js

Access the Application: Open your web browser and go to http://localhost:3000.

Usage
Enter the text you wish to encrypt or decrypt.
Enter a keyword.
Choose Encrypt or Decrypt from the dropdown menu.
Click Process to view the result.

Project Structure

.
├── backend/
│   └── cipher.cpp            # C++ code for Vigenère Cipher
├── frontend/
│   ├── index.html            # HTML UI
│   ├── style.css             # CSS for styling
│   └── script.js             # JavaScript for UI interaction
├── server.js                 # Node.js server to handle API requests
└── package.json              # Node.js project dependencies
