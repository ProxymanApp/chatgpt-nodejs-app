# ChatGPT Node.js Chat Application

A simple chat application that uses Express.js to create a server that communicates with OpenAI's API to provide AI-powered responses.

## Features

- Simple and clean chat interface
- Real-time communication with OpenAI's GPT-3.5 Turbo model
- Express.js backend server
- Hot reloading during development with Nodemon

## Prerequisites

- Node.js (v14 or newer)
- An OpenAI API key

## Installation

1. Clone this repository or download the files
2. Install dependencies:
   ```
   npm install
   ```
3. Configure your environment variables:
   - Rename or copy `.env.example` to `.env` (if not already done)
   - Add your OpenAI API key to the `.env` file:
     ```
     OPENAI_API_KEY=your-api-key-here
     PORT=3000
     ```

## Running the Application

### Development Mode (with hot reloading)

```
npm run dev
```

This starts the server with Nodemon, which automatically restarts when you make changes to the code.

### Production Mode

```
npm start
```

## Using the Chat Interface

1. After starting the server, open your browser and navigate to:
   ```
   http://localhost:3000
   ```
2. Type your message in the input field and press Enter or click the Send button
3. Wait for the AI to respond

## Project Structure

- `server.js` - The Express.js server that handles API requests
- `index.html` - The frontend chat interface
- `.env` - Environment variables (API keys, port settings)
- `package.json` - Project dependencies and scripts

## Dependencies

- Express.js - Web server framework
- Axios - HTTP client for API requests
- CORS - Cross-origin resource sharing middleware
- dotenv - Environment variable management
- Nodemon (dev) - Hot reloading during development

## License

ISC 