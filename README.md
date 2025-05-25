# Follow-Up Reminder System

## Project Overview
The Follow-Up Reminder System is a web application designed to facilitate scheduling and managing medical appointments between patients and doctors. The system enables patients to book appointments, and doctors to keep track of follow-ups efficiently, improving healthcare communication and reducing missed consultations.

---

## Team Members
- **Stella Murithi** — kathuremurithi20@gmail.com  
- **Joseph Murithi** — joejuryme@gmail.com  
- **Rency Jeptanui** — jeptanuirency313@gmail.com  

---

## Frontend
- Built with **React.js** using **Vite** as the build tool.
- Uses **React Router** (HashRouter) for client-side routing.
- Implements forms with validation to book appointments.
- Fetches and displays appointments data from the backend API.
- Styled with **Bootstrap** for responsiveness and clean UI.
- Hosted separately, with continuous deployment setup.

**Frontend Demo:** [https://follow-upreminder-system-frontend.onrender.com](https://follow-upreminder-system-frontend.onrender.com)

---

## Backend
- Developed with **Node.js** and **Express.js**.
- Provides REST API endpoints for:
  - Fetching all appointments (`GET /appointments`)
  - Creating a new appointment (`POST /appointments`)
- Connects to a database (e.g., Supabase or PostgreSQL) to persist appointments.
- Hosted separately with a live API URL.
- CORS configured to allow frontend requests.

**Backend Demo:** [https://follow-up-reminder-system-backend.onrender.com](https://follow-up-reminder-system-backend.onrender.com)

---

## How to Run Locally
1. Clone the frontend and backend repositories separately.
2. For **Backend**:
   ```bash
   cd backend
   npm install
   npm start
For Frontend:

bash
Copy
Edit
cd frontend
npm install
npm run dev
Make sure the backend URL is correctly set in the frontend API calls.

Deployment
The frontend is deployed on Render

The backend is deployed on Render

Pitch Deck
You can view our project pitch deck here:
[Canva Pitch Deck Link ](https://www.canva.com/design/DAGocdKvjCo/qsjtSBNWRxKnJkKBuVIihw/view?utm_content=DAGocdKvjCo&utm_campaign=designshare&utm_medium=link2&utm_source=uniquelinks&utlId=h455f9a9d8a)

Notes
The frontend uses HashRouter to avoid routing issues on static hosts.

Ensure the backend API routes match the URLs used in the frontend.

All sensitive credentials (API keys, DB passwords) are stored securely in environment variables.
