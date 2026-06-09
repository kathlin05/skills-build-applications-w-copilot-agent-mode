# OctoFit Tracker

A modern multi-tier fitness tracking application built with React 19, Node.js/Express, and MongoDB.

## Architecture

### Frontend
- **Framework**: React 19
- **Build Tool**: Vite
- **Port**: 5173

### Backend
- **Runtime**: Node.js
- **Framework**: Express
- **Language**: TypeScript
- **Port**: 8000
- **Database**: MongoDB (Port: 27017)

### Database
- **Database**: MongoDB
- **Port**: 27017
- **ODM**: Mongoose

## Setup Instructions

### Prerequisites
- Node.js 18+
- MongoDB running locally on port 27017

### Frontend Setup

```bash
cd octofit-tracker/frontend
npm install
npm run dev
```

The frontend will be available at `http://localhost:5173`

### Backend Setup

```bash
cd octofit-tracker/backend
npm install
npm run dev
```

The backend API will be available at `http://localhost:8000`

### API Endpoints

- `GET /api/health` - Health check endpoint

## Development

To develop both frontend and backend simultaneously:

1. Start MongoDB
2. Open Terminal 1 and run backend: `cd octofit-tracker/backend && npm run dev`
3. Open Terminal 2 and run frontend: `cd octofit-tracker/frontend && npm run dev`

## Build for Production

### Frontend
```bash
cd octofit-tracker/frontend
npm run build
npm run preview
```

### Backend
```bash
cd octofit-tracker/backend
npm run build
npm start
```
