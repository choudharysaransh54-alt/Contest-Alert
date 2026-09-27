# Contest Alert 🏆

A full-stack web application designed to help competitive programmers track upcoming coding contests across platforms like **Codeforces** and **LeetCode**. Never miss a contest again!

![Node](https://img.shields.io/badge/Node.js-18%2B-339933?logo=node.js&logoColor=white)
![React](https://img.shields.io/badge/React-18-61DAFB?logo=react&logoColor=black)
![Express](https://img.shields.io/badge/Express-4-000000?logo=express&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-Atlas-47A248?logo=mongodb&logoColor=white)

## Features ✨
- **Automated Tracking:** Automatically fetches upcoming rounds and contests.
- **Google OAuth 2.0:** Secure and seamless 1-click login using Google.
- **Custom Filters:** Track only the types of contests you care about (e.g., LeetCode Weekly, Codeforces Div 2).
- **Email Reminders:** Get notified 20 minutes before a contest starts via Gmail integration.
- **Calendar Sync:** One-click push to add contests directly to your Google Calendar.
- **Dark/Light Mode:** Full theme support with persisted user preferences.

## Tech Stack 🛠️
- **Frontend:** React 18, React Router, Tailwind CSS, Axios
- **Backend:** Node.js, Express, Passport.js (Google OAuth)
- **Database:** MongoDB Atlas, Mongoose
- **Services:** Nodemailer (Email), Google Calendar API, node-cron (Scheduling)

## Running Locally 🚀

1. **Clone the repository**
   ```bash
   git clone https://github.com/choudharysaransh54-alt/Contest-Alert.git
   cd Contest-Alert
   ```

2. **Install dependencies**
   ```bash
   cd frontend && npm install
   cd ../backend && npm install
   ```

3. **Configure Environment Variables**
   Create a `.env` file in both the `frontend` and `backend` directories and add your credentials (MongoDB URI, Google OAuth keys, and Gmail App Password).

4. **Start the servers**
   ```bash
   # In the backend directory
   npm start
   
   # In the frontend directory
   npm start
   ```
