# Simple Node.js Web App

A basic web application built with Node.js and Express.js.

## Features

- Simple Express server
- Static file serving (HTML, CSS)
- RESTful API endpoints
- Interactive web interface with API buttons

## Getting Started

### Prerequisites

- Node.js (version 14 or higher)
- npm (comes with Node.js)

### Installation

1. Navigate to the project directory:
```bash
cd copilot_test
```

2. Install dependencies:
```bash
npm install
```

### Running the App

Start the development server:
```bash
npm start
```

The app will be available at `http://localhost:3000`

## API Endpoints

- `GET /` - Main page
- `GET /api/hello` - Returns a hello message
- `GET /api/time` - Returns the current server time

## Usage

1. Open your browser and go to `http://localhost:3000`
2. Click the buttons to test the API endpoints
3. Responses will be displayed on the page

## Project Structure

```
copilot_test/
├── server.js          # Express server setup
├── package.json       # Dependencies and scripts
├── public/
│   ├── index.html     # Main HTML page
│   └── style.css      # Styling
└── README.md          # This file
```

## License

ISC
