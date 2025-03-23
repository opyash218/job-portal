# Job Portal

A job portal application built using Node.js, allowing users to register, search for jobs, and apply online. Employers can post job listings and manage applications.

## Features
- User Authentication (Register/Login)
- Job Listings
- Apply for Jobs
- Employer Dashboard (Post & Manage Jobs)
- Search & Filter Jobs
- Profile Management

## Tech Stack
- **Backend:** Node.js, Express.js
- **Database:** MongoDB/MySQL (Choose based on preference)
- **Authentication:** JWT, bcrypt
- **Frontend (Optional):** React.js, EJS, or any preferred framework
- **Deployment:** AWS, Heroku, or Vercel

## Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/opyash218/job-portal.git
   cd job-portal
   ```
2. Install dependencies:
   ```sh
   npm install
   ```
3. Set up environment variables in a `.env` file:
   ```sh
   PORT=5000
   DB_URI=your_database_url
   JWT_SECRET=your_secret_key
   ```
4. Run the application:
   ```sh
   npm start
   ```
5. Open in browser:
   ```sh
   http://localhost:5000
   ```

## API Endpoints
| Method | Endpoint | Description |
|--------|---------|-------------|
| POST | /api/auth/register | Register a new user |
| POST | /api/auth/login | User login |
| GET | /api/jobs | Fetch all jobs |
| POST | /api/jobs | Post a new job (Employer) |
| GET | /api/jobs/:id | Get job details |
| POST | /api/jobs/:id/apply | Apply for a job |

## Contributing
Feel free to fork this repository and submit pull requests with improvements.



