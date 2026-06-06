# Bayelsa Real Estate Platform

A full-stack real estate web application built with React, Vite, Node.js, Express, and MongoDB.

## Features

- Property and land listings
- Property pricing information
- Interactive map locations
- Nearby landmarks and communities
- Responsive design
- Contact and inquiry system
- Admin property management

## Tech Stack

### Frontend
- React
- Vite
- JavaScript
- CSS

### Backend
- Node.js
- Express.js

### Database
- MongoDB Atlas

## Project Structure

```text
project/
├── client/
│   ├── src/
│   └── public/
│
└── server/
    ├── routes/
    ├── models/
    ├── controllers/
    └── server.js
```

## Installation

### Clone Repository

```bash
git clone https://github.com/yourusername/bayelsa-real-estate.git
```

### Frontend Setup

```bash
cd client
npm install
npm run dev
```

### Backend Setup

```bash
cd server
npm install
npm start
```

## Environment Variables

Create a `.env` file inside the server directory:

```env
MONGO_URI=your_mongodb_connection_string
PORT=5000
```

## API Endpoint

```http
GET /
```

Response:

```json
{
  "message": "Server is running"
}
```

## Future Improvements

- User authentication
- Property search and filtering
- Image uploads
- Payment integration
- Agent dashboard
- Property reviews

## Author

Your Name Emiakpo 

## License

MIT License