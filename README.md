# AI Chat Frontend

An Angular web application that provides a chat interface for interacting with an assistant API.

## Features

- Angular-based chat user interface.
- Communication with a backend REST API.
- TypeScript-based application logic.
- Component styling and responsive UI structure.
- Automated tests using the configured Angular test tooling.

## Technology Stack

- Angular
- TypeScript
- HTML and CSS
- Node.js and npm
- REST API integration

## Prerequisites

- Node.js version compatible with the project.
- npm.
- The companion backend API running and correctly configured.

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/vamsimylu-debug/ai-chat-frontend.git
cd ai-chat-frontend
```

### 2. Install dependencies

```bash
npm ci
```

### 3. Configure the backend URL

The frontend currently uses the local backend endpoint:

```text
http://localhost:5163/api/assistant/ask
```

Make sure the backend is running at this address. If the backend uses another port, update the API URL in the frontend configuration accordingly.

### 4. Start the development server

```bash
npm start
```

Open the application at:

```text
http://localhost:4200
```

## Development

To build the application:

```bash
npm run build
```

Run the configured tests using the script defined in `package.json`.

## Project Structure

```text
.
├── public/
├── src/
│   ├── app/
│   └── index.html
├── angular.json
├── package.json
├── package-lock.json
└── tsconfig.json
```

