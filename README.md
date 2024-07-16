# Draw Jam
## A Real-Time Collaborative Drawing App

Draw Jam allows you to create new jam boards, invite people to collaborate in real-time, and draw together using various tools.

## Features

- **Drawing Tools**: Use the Pen, Line, Rectangle, and Erase tools to create your jams.
- **Save to Cloud**: Save your drawings to the cloud for easy access.
- **Multi-User Collaboration**: Collaborate in real-time with multiple users on the same jam board.

## Tech Stack

- **Backend**: Node.js
- **Frontend**: React.js
- **Database**: PostgreSQL

## Getting Started

### Prerequisites

For local development environment:

- Node.js
- npm
- Docker (for running PostgreSQL locally)

### Installation

Follow these steps for running locally

#### Frontend

1. Navigate to the `client` directory:
   ```sh
   cd client
   ```

2. Install the required dependencies:
   ```sh
   npm install
   ```

3. Start the development server:
   ```sh
   npm run dev
   ```

#### Backend

1. Navigate to the `server` directory:
   ```sh
   cd server
   ```

2. Install the required dependencies:
   ```sh
   npm install
   ```

3. Start the backend server using nodemon:
   ```sh
   nodemon ./index.js
   ```

#### Database

1. Navigate to the `server/db` directory:
   ```sh
   cd server/db
   ```

2. Start the PostgreSQL server using Docker:
   ```sh
   docker-compose up -d
   ```

## Usage

Open your browser and navigate to `http://localhost:5173` to access the frontend.


