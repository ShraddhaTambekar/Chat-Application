
# Chat Application

## Overview
The **Chat Application** is a Java-based chat application that allows users to communicate in real-time. It supports both individual and group messaging. The app features a simple user interface and handles multiple clients through server-side socket programming.

## Features
- **Real-time messaging**: Send and receive messages instantly.
- **Group chats**: Create and join group chats for multiple participants.
- **User-friendly interface**: Easy-to-navigate interface for a smooth user experience.
- **Multi-client support**: Handles multiple users using socket communication.
- **Message encryption**: Basic message encryption to ensure secure communication.
  
## Requirements
To run this application, ensure you have the following installed on your system:
- **Java Development Kit (JDK)** version 8 or above.
- Any modern **IDE** like IntelliJ IDEA, Eclipse, or NetBeans (optional but recommended).

## Installation
Follow these steps to set up and run the application:
1. Clone or download the repository.
   ```bash
   git clone https://github.com/ShraddhaTambekar/Chat-Application
   ```
2. Navigate to the project directory:
   ```bash
   cd Chat_Application
   ```
3. Compile the Java files using the terminal or your preferred IDE. If using the terminal, use:
   ```bash
   javac Chat_Application.java
   ```
4. Start the server:
   ```bash
   java Chat_Application
   ```
   *Note*: Ensure that the server is up and running before clients attempt to connect.

## Usage
1. Once the server is running, open a new terminal window for each client.
2. For each client, run:
   ```bash
   java Chat_Application
   ```
3. Follow the prompts to enter your username and start chatting.

