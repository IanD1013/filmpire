# FilmPire 🎬

A modern movie discovery platform built with React, featuring a beautiful Material-UI interface.

## Features

- 🎯 Browse and search movies
- 🎨 Modern Material-UI interface
- 📱 Responsive design
- 🔍 Advanced search and filtering
- 🎭 Detailed movie information
- 🎯 Genre-based categorization

## Tech Stack

- React 18
- Material-UI (MUI)
- Redux Toolkit
- React Router
- Axios

## Getting Started

### Prerequisites

- Node.js (v14 or higher)
- npm or yarn

### Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/filmpire.git
cd filmpire
```

2. Install dependencies:
```bash
npm install
```

3. Create a `.env` file in the root directory and add your environment variables:
```env
REACT_APP_TMDB_TOKEN=your_tmdb_token
```

4. Start the development server:
```bash
npm start
```

The app will be available at `http://localhost:3000`

## Available Scripts

- `npm start` - Runs the app in development mode
- `npm test` - Launches the test runner
- `npm run build` - Builds the app for production
- `npm run eject` - Ejects from Create React App

## Project Structure

```
src/
├── app/          # Redux store configuration
├── assets/       # Static assets (images, icons)
├── components/   # Reusable UI components
├── features/     # Feature-specific components and logic
├── services/     # API and external service integrations
└── utils/        # Utility functions and helpers
```
