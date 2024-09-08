
# Password Generator

This is a simple Password Generator web application that allows users to generate random, secure passwords based on selected criteria (length, uppercase, lowercase, numbers, and symbols).

## Prerequisites

Before you begin, ensure you have the following installed:

- [Node.js](https://nodejs.org/) (version 14.18.0 or higher)
- [npm](https://www.npmjs.com/) (version 6 or higher)

You can check if they are installed by running:

```bash
node -v
npm -v
```

## Installation

### Step 1: Clone the repository

Clone this repository to your local machine:

```bash
git clone <repository-url>
```

Replace `<repository-url>` with the actual URL of your repository.

### Step 2: Navigate into the project directory

Move into the project folder:

```bash
cd <project-folder>
```

### Step 3: Install dependencies

Install the necessary dependencies by running the following command:

```bash
npm install
```

### Step 4: Start the development server

Run the development server to start the app:

```bash
npm run dev
```

The app will be available at:

```bash
http://localhost:5173
```

### Step 5: Build for production (optional)

To build the project for production, run:

```bash
npm run build
```

The production build will be in the `dist/` directory.

## Features

- Generate passwords with customizable length.
- Include/exclude uppercase letters, lowercase letters, numbers, and symbols.
- Simple and easy-to-use UI.

## Project Structure

```
├── public
│   └── index.html           # Main HTML file
├── src
│   ├── components           # React components for UI
│   ├── App.jsx              # Main app component
│   └── main.jsx             # Entry point
├── package.json             # Project configuration and dependencies
└── vite.config.js           # Vite configuration
```

## Available Scripts

- `npm run dev`: Starts the development server.
- `npm run build`: Builds the app for production.
- `npm run preview`: Preview the production build locally.

## Learn More

To learn more about the tools used:

- [Vite Documentation](https://vitejs.dev/guide/)
- [React Documentation](https://reactjs.org/)
