# Mployee Backend

This is the backend for the Mployee application, built with Node.js, Express, and MongoDB. The backend provides APIs for managing job data.

---

## Features
- Retrieve all job listings
- Search jobs by location

---

## Steps to Run the Project Locally

### Prerequisites
- Node.js and npm installed on your system
- MongoDB database setup and running
- Git installed

### 1. Clone the Repository
```bash
git clone <repository-url>
cd MployeeBackend
```

### 2. Install Dependencies
```bash
npm install
```

### 3. Set Up Environment Variables
Create a `.env` file in the root directory and add the following variables:
```env
MONGO_URI=<your-mongo-database-uri>
PORT=5000
```
Replace `<your-mongo-database-uri>` with the connection string of your MongoDB instance.

### 4. Start the Server
```bash
node index.js
```
The server will run on `http://localhost:5000` by default.

---

## API Endpoints

### Base URL
- Local: `http://localhost:5000`
- Deployed: `<deployed-backend-url>`

### Endpoints

#### **1. Get All Jobs**
- **URL:** `/`
- **Method:** `GET`
- **Description:** Fetches all available job listings.

#### **2. Search Jobs by Location**
- **URL:** `/search?location=<location>`
- **Method:** `GET`
- **Description:** Searches for jobs based on the provided location.

---

## Links to Deployed Backend
- Deployed Backend URL: `<deployed-backend-url>`

Replace `<deployed-backend-url>` with the actual URL of your deployed backend on Vercel or any other platform.

---

## Troubleshooting

If you encounter any issues, ensure the following:
1. MongoDB is running and accessible.
2. All dependencies are installed correctly.
3. The environment variables are correctly set.

For additional help, feel free to raise an issue in the repository.
