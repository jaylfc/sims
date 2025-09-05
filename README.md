![Video Thumbnail](https://img.youtube.com/vi/73XOJlLhhZg/maxresdefault.jpg)

[Video tutorial](https://youtu.be/73XOJlLhhZg)

## Getting Started

This is a full-stack 3D room simulation app with real-time multiplayer functionality. The client is built with React and React Three Fiber for 3D rendering, while the server uses Node.js and Socket.IO for real-time communication.

### Prerequisites

- Node.js (version 16 or higher)
- npm or yarn

### Installation

1. Clone the repository
2. Install dependencies for both client and server:

   ```bash
   cd client
   npm install

   cd ../server
   npm install
   ```

### Running the Application

1. Start the server:

   ```bash
   cd server
   npm run dev
   ```

   The server will run on http://localhost:3000

2. Start the client:

   ```bash
   cd client
   npm run dev
   ```

   The client will run on http://localhost:5173

3. Open your browser and navigate to http://localhost:5173

### Features

- 3D room simulation using React Three Fiber
- Real-time multiplayer with Socket.IO
- Pathfinding for character movement
- Customizable rooms and items
- Avatar creation with Ready Player Me
