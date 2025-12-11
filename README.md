# web3-authentication-demo
A simple demo showing how to use Web3Auth as the backend service for authentication. This project explains how users can log in with normal methods (Google, email, OTP), and how Web3Auth automatically creates and manages their Web3 wallet in the background.
This backend demonstrates a simple flow for authenticating users using Web3Auth.
The client receives an ID Token from Web3Auth, and the backend verifies the token to confirm the user’s identity.

 Features

Web3Auth ID token verification
Secure session creation
Protected API routes
Example login + profile endpoints
Clean, simple Node.js backend
Easy to integrate with any frontend (React, Flutter, etc.)

Tech Stack

Node.js
Express.js
Web3Auth Backend SDK
JSON Web Tokens (JWT)
dotenv

setup instructions-
clone the repo
install dependencies (npm install)
add environmental variables (create .env file)
start backend (npm start)
