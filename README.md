# Whiteboard Sharing App

Welcome to the **Whiteboard Sharing App**, a collaborative drawing and chat application built with React and Socket.IO. This application allows users to create or join rooms where they can draw together in real-time, making it perfect for brainstorming sessions, online classes, or just having fun with friends.

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Features

- **Real-time Collaboration**: Draw on a shared canvas with multiple users.
- **Chat Functionality**: Communicate with other users in the room via a chat interface.
- **User Management**: Create or join rooms easily and see who is online.
- **Undo/Redo Options**: Manage your drawing history effortlessly.
- **Color Picker & Tools**: Choose different colors and tools (pencil, line, rectangle) for your drawings.

## Technologies Used

This project utilizes the following technologies:

- **Frontend**:
  - React
  - Socket.IO Client
  - Bootstrap for styling
  - Rough.js for sketching effects
  - React Toastify for notifications

- **Backend**:
  - Node.js
  - Express.js
  - Socket.IO Server
  - CORS middleware for handling cross-origin requests

## Installation

To get started with the Whiteboard Sharing App, follow these steps:

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/whiteboard-sharing-app.git
   ```

2. Navigate into the frontend directory and install dependencies:
   ```bash
   cd whiteboard-sharing-app/frontEnd
   npm install
   ```

3. Navigate into the backend directory and install dependencies:
   ```bash
   cd ../server
   npm install
   ```

4. Start the server:
   ```bash
   npm run dev 
   ```
   
5. In another terminal window, start the frontend app:
   ```bash
   cd frontEnd 
   npm start 
   ```

6. Open your browser and go to `http://localhost:3000` to access the app.

## Usage

1. Upon opening the app, you can either create a new room or join an existing one by entering a room ID.
2. Once in a room, you can use the drawing tools provided to collaborate with others in real time.
3. Use the chat feature to communicate while drawing.

## Contributing

We welcome contributions! If you'd like to contribute to this project:

1. Fork this repository.
2. Create a new branch (`git checkout -b feature/YourFeature`).
3. Make your changes and commit them (`git commit -m 'Add some feature'`).
4. Push to your branch (`git push origin feature/YourFeature`).
5. Open a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

---

Thank you for checking out our Whiteboard Sharing App! We hope you enjoy using it as much as we enjoyed building it! If you have any questions or feedback, feel free to reach out!
