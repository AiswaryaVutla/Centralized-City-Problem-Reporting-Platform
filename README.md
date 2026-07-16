#  CENTRALIZED CITY PROBLEM REPORTING PLATFORM

A Full-Stack Municipal Complaint Management System developed to simplify the process of reporting, managing, and resolving civic issues. The platform enables citizens to submit complaints, administrators to assign tasks, and workers to update complaint statuses through dedicated role-based dashboards.

## 📌 PROJECT OVERVIEW

The Centralized City Problem Reporting Platform is designed to bridge the communication gap between citizens and municipal authorities. Citizens can report civic issues such as potholes, drainage problems, garbage collection, water supply issues, and streetlight failures with image evidence. Administrators efficiently assign complaints to workers, monitor progress, publish announcements, and analyze citizen feedback, while workers update complaint resolution statuses in real time.

## KEY FEATURES

###  CITIZEN MODULE

- User Registration & Login
- Raise Public and Private Complaints
- Upload Complaint Images
- Track Complaint Status
- View Municipal Announcements
- Submit Feedback & Ratings

### Administrator Module:
- Secure Login
- View and Manage Complaints
- Assign Complaints to Workers
- Update Complaint Status
- Publish Public Announcements
- Monitor Citizen Feedback & Ratings

### Worker Module:
- Login Dashboard
- View Assigned Complaints
- Update Complaint Progress
- Mark Complaints as Completed

## TECH STACK
### FRONTEND:
 - React.js
 - JavaScript (ES6+)
 - HTML5
 - CSS3
 - Axios
 - React Router
 - Vite
### BACKEND:
 - Node.js
 - Express.js
 - RESTful APIs
 - Multer (Image Upload)
### DATABASE:
 - MySQL
### TOOLS & TECHONOLOGIES:
 - Git
 - GitHub
 - VS Code
 - Postman
 - npm

## SYSTEM ARCHITECTURE
Citizen / Admin / Worker
            │
            ▼
      React.js Frontend
            │
         Axios API Calls
            │
            ▼
    Node.js + Express.js
            │
            ▼
         MySQL Database

## PROJECT STRUCTURE
Centralized-City-Problem-Reporting-Platform
-│
-├── frontend
-│   ├── public
-│   ├── src
-│   │   ├── assets
-│   │   ├── context
-│   │   ├── pages
-│   │   ├── App.jsx
-│   │   └── main.jsx
-│   ├── package.json
-│   └── vite.config.js
-│
-├── backend
-│   ├── server.js
-│   ├── init.sql
-│   ├── package.json
-│   └── uploads
-│
-└── README.md

## WORKFLOW
- Citizens register and log in.
- Complaints are submitted with category, description, and optional image.
- Administrators review complaints and assign them to workers.
- Workers update complaint progress and resolution status.
- Citizens monitor complaint progress.
- After resolution, citizens provide feedback and ratings.
- Administrators monitor overall complaint performance and service quality.

## DATABASE
- The system uses MySQL as the relational database.

Major entities include:
- Users
- Complaints
- Workers
- Announcements
- Feedback
- Ratings

The database is designed using relational tables with foreign key relationships to maintain data consistency and support efficient CRUD operations.

## ROLE-BASED ACCESS CONTROL
The application implements role-based authentication with separate dashboards for:

- Citizen
- Administrator
- Worker

Each role has access only to the functionalities relevant to their responsibilities.

## REST API FEATURES
The backend exposes RESTful APIs for:

- User Authentication
- Complaint Registration
- Complaint Assignment
- Complaint Tracking
- Status Updates
- Image Upload
- Announcement Management
- Feedback & Ratings

## INSTALLATION

Clone the repository:
    git clone https://github.com/AiswaryaVutla/Centralized-City-Problem-Reporting-Platform.git

Navigate to the project:
    cd Centralized-City-Problem-Reporting-Platform

Install Backend Dependencies:
    cd backend
    npm install

Install Frontend Dependencies
    cd backend
    npm install

Configure Database:
    Create a MySQL database.
    Import the provided init.sql file.
    Update database credentials in the backend .env file.

Start Backend:
    cd backend
    npm start

Start Frontend:
    cd frontend
    npm run dev


## SCREENSHOTS

### HOME PAGE

<img width="1102" height="610" alt="image" src="https://github.com/user-attachments/assets/8764bc95-3ed7-43a0-9530-fcc1c2e28e45" />

### CITIZEN DASHBOARD

<img width="915" height="524" alt="image" src="https://github.com/user-attachments/assets/100cac46-960f-4f8f-81a0-e5bc9a78ea13" />

### ADMINISTRATOR DASHBOARD

<img width="912" height="484" alt="image" src="https://github.com/user-attachments/assets/d91d97c2-f2a4-424e-aba7-3dfc8f564832" />

### WORKER DASHBOARD

<img width="926" height="490" alt="image" src="https://github.com/user-attachments/assets/fd15ed8d-4af7-4c75-97a6-1d948344f110" />

### FEEDBACK & RATING MODULE

<img width="963" height="524" alt="image" src="https://github.com/user-attachments/assets/54f51dc1-5713-4c76-90e8-b42dc9555a5b" />


## FUTURE ENHANCEMENTS

Email & SMS Notifications
Real-Time Complaint Tracking
Interactive GIS Map Integration
AI-Based Complaint Categorization
Complaint Priority Prediction
Mobile Application Support
Analytics Dashboard for Authorities
Multi-Language Support


## LEARNING OUTCOMES

This project strengthened practical knowledge in:

Full Stack Web Development
React.js
Node.js
Express.js
MySQL
RESTful API Development
CRUD Operations
Authentication & Authorization
Image Upload Handling
Database Design
Client–Server Architecture
Git & GitHub


## AUTHOR

Aiswarya Vutla

LinkedIn: https://www.linkedin.com/in/aiswarya-vutla1808/
GitHub: https://github.com/AiswaryaVutla


## LICENSE

This project is intended for educational and learning purposes.

  
