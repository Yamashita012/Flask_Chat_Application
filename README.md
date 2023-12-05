# Flask Chat Application

This is a simple chat application built using Flask and Flask-SocketIO. It allows users to create or join chat rooms and communicate in real-time.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Contributing](#contributing)

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/yamashita012/flask-chat-app.git
   ```

2. Change into the project directory:

   ```bash
   cd flask-chat-app
   ```

3. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Run the application:

   ```bash
   python app.py
   ```

2. Open your web browser and go to [http://localhost:5000](http://localhost:5000).

3. Enter your name and either create a new room or enter an existing room using the room code.

4. Chat in real-time with other users in the same room.

## Features

- **Real-time Communication**: Uses Flask-SocketIO for real-time bidirectional communication between the server and clients.

- **Room Creation and Joining**: Users can create a new chat room with a unique code or join an existing room by entering the code.

- **User Authentication**: Users need to provide their name when joining a room.

- **Dynamic Room Codes**: Automatically generates unique room codes to avoid conflicts.

- **User Count**: Displays the number of users currently in the room.

- **Disconnect Handling**: Notifies when a user has left the room.

## Contributing

Contributions are welcome! If you find any bugs or have suggestions for improvement, please open an issue or submit a pull request.

1. Fork the repository.
2. Create a new branch: `git checkout -b feature/your-feature`.
3. Commit your changes: `git commit -m 'Add some feature'`.
4. Push to the branch: `git push origin feature/your-feature`.
5. Open a pull request.
