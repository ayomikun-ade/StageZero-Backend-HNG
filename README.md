# HNG API Task with Express.js

This is a simple public API built with Express.js that returns:
- My email address
- The current datetime in ISO 8601 format.
- The GitHub URL of the project's codebase.

## Setup Instructions

### Prerequisites
- Node.js (>= 16.x)
- npm (Node Package Manager)

### Steps to Run Locally
1. Clone the repository:
   ```sh
   git clone https://github.com/ayomikun-ade/StageZero-Backend-HNG.git
   cd StageZero-Backend-HNG
   ```
2. Install dependencies:
   ```sh
   npm install
   ```
3. Start the server:
   ```sh
   node app.js
   ```
4. The API will run on `http://localhost:3000/`

## API Documentation

### Endpoint
`GET /`

### Response Format
- **Status Code**: `200 OK`
- **Response Body**:
```json
{
  "email": "ayoadeosun10@example.com",
  "current_datetime": "2025-01-30T09:30:00Z",
  "github_url": "https://github.com/ayomikun-ade/StageZero-Backend-HNG"
}
```

### Example Usage
Using `curl`:
```sh
curl -X GET http://localhost:3000/
```

### Live Deployment
Live URL: [https://stage-zero-backend-hng.vercel.app/](https://stage-zero-backend-hng.vercel.app/)

## Link
Looking for Node.js developers? [Hire Node.js Developers](https://hng.tech/hire/nodejs-developers)
