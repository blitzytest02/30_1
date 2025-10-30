# 30_1

## Description
A simple Express.js tutorial server demonstrating basic routing and endpoint creation.

## Prerequisites
- Node.js (v14.0.0 or higher)
- npm (comes with Node.js)

## Installation
1. Install dependencies:
   ```bash
   npm install
   ```

## Usage
Start the server using either of these commands:
```bash
npm start
```

Or:
```bash
node server.js
```

The server will run on http://localhost:3000

## Available Endpoints

### GET /
Returns "Hello world"

Example:
```bash
curl http://localhost:3000/
```

### GET /evening
Returns "Good evening"

Example:
```bash
curl http://localhost:3000/evening
```

## License
MIT