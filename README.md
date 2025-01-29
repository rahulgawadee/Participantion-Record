# Participant Management System

## Overview
This project is a **Participant Management System** built using **React.js** for the frontend and **Node.js, Express.js, and MongoDB** for the backend. It enables users to register participants, manage participant details, and generate reports in PDF format.

## Features
- **Participant Registration**: Users can add participants with details like name, designation, email, mobile, and organization.
- **Participant List**: Displays all registered participants with an option to delete entries.
- **PDF Export**: Generates a downloadable **PDF report** of all participants.
- **Real-time API Communication**: Uses **Axios** to fetch, add, and delete participants from the backend.
- **User Notifications**: Implements **SweetAlert2** for success/error notifications.
- **Responsive UI**: Styled using **Tailwind CSS** for an optimized experience across devices.

## Tech Stack
### Frontend:
- **React.js**: Component-based architecture for UI.
- **Axios**: HTTP requests for API communication.
- **SweetAlert2**: User-friendly notifications.
- **Tailwind CSS**: Styling and responsiveness.
- **jsPDF & autoTable**: PDF generation.

### Backend:
- **Node.js & Express.js**: REST API for handling participant data.
- **MongoDB & Mongoose**: Database for storing participant information.
- **CORS & Body-Parser**: Middleware for API handling.

## Setup & Installation
1. **Clone the repository**
   ```sh
   git clone https://github.com/your-repo/participant-management.git
   cd participant-management
Install dependencies
Frontend
sh
Copy
Edit
cd frontend
npm install
npm start
Backend
sh
Copy
Edit
cd backend
npm install
node server.js
API Endpoints
Method	Endpoint	Description
POST	/create	Add a participant
GET	/participants	Fetch all participants
DELETE	/delete/:id	Remove a participant
Usage
Fill in participant details in the Add Participant Form and submit.
View registered participants in the Participants List.
Download Data as a PDF report.
Delete a participant from the list if necessary.
Future Enhancements
Add Edit functionality for participant details.
Implement Authentication for secure access.
Improve Search and Filtering options.
Contributors
Your Name
Your Team (if applicable)
License
This project is licensed under the MIT License.

vbnet
Copy
Edit

Let me know if you want any modifications! 🚀
