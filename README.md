# 🚀 Centralized City Problem Reporting Platform

The **Centralized City Problem Reporting Platform** is a Full-Stack Municipal Complaint Management System developed to streamline the process of reporting, managing, and resolving civic issues. The platform connects citizens, municipal administrators, and field workers through dedicated role-based dashboards, enabling efficient communication and transparent complaint resolution.

Built using **React.js, Node.js, Express.js, and MySQL**, the application demonstrates practical implementation of full-stack development concepts, including authentication, RESTful API development, image uploads, role-based authorization, database management, and seamless frontend-backend integration.

---

## ✨ Features

### 👤 Citizen Module

- Secure User Registration & Login
- Raise Public and Private Complaints
- Upload Complaint Images
- Track Complaint Status
- View Municipal Announcements
- Submit Feedback & Ratings

### 🛡️ Administrator Module

- Secure Administrator Login
- View and Manage Complaints
- Assign Complaints to Workers
- Update Complaint Status
- Publish Public Announcements
- Monitor Citizen Feedback & Ratings

### 👷 Worker Module

- Secure Worker Login
- View Assigned Complaints
- Update Complaint Progress
- Mark Complaints as Resolved

---

## 🛠️ Tech Stack

### Frontend

- React.js
- JavaScript (ES6+)
- HTML5
- CSS3
- Axios
- React Router
- Vite

### Backend

- Node.js
- Express.js
- RESTful APIs
- Multer (Image Upload)

### Database

- MySQL

### Tools & Technologies

- Git
- GitHub
- VS Code
- Postman
- npm

---

## 🏗️ System Architecture

```text
Citizen / Administrator / Worker
              │
              ▼
        React.js Frontend
              │
        Axios API Requests
              │
              ▼
     Node.js + Express.js
              │
              ▼
         MySQL Database
```

---

## 📂 Project Structure

```text
Centralized-City-Problem-Reporting-Platform
│
├── frontend
│   ├── public
│   ├── src
│   │   ├── assets
│   │   ├── context
│   │   ├── pages
│   │   ├── App.jsx
│   │   └── main.jsx
│   ├── package.json
│   └── vite.config.js
│
├── backend
│   ├── server.js
│   ├── init.sql
│   ├── uploads
│   └── package.json
│
└── README.md
```

---

## 🔄 Application Workflow

1. Citizens register and log in to the platform.
2. Submit complaints with category, description, and optional image evidence.
3. Administrators review and assign complaints to workers.
4. Workers update complaint progress and resolution status.
5. Citizens track complaint status in real time.
6. After resolution, citizens submit feedback and ratings.
7. Administrators monitor complaint analytics and overall service quality.

---

## 🗄️ Database Design

The application uses **MySQL** as its relational database for secure and efficient data management.

### Major Entities

- Users
- Complaints
- Workers
- Announcements
- Feedback
- Ratings

The database follows a relational schema with foreign key relationships to maintain data consistency and support efficient CRUD operations.

---

## 🔐 Role-Based Access Control

The platform implements secure role-based authentication with dedicated dashboards for:

- 👤 Citizen
- 🛡️ Administrator
- 👷 Worker

Each user can access only the functionalities assigned to their respective role.

---

## 🌐 REST API Features

The backend exposes RESTful APIs for:

- User Authentication
- Complaint Registration
- Complaint Assignment
- Complaint Tracking
- Complaint Status Updates
- Image Upload Handling
- Announcement Management
- Feedback & Ratings

---

## ⚙️ Getting Started

### Clone the Repository

```bash
git clone https://github.com/AiswaryaVutla/Centralized-City-Problem-Reporting-Platform.git
```

### Navigate to the Project

```bash
cd Centralized-City-Problem-Reporting-Platform
```

### Install Backend Dependencies

```bash
cd backend
npm install
```

### Install Frontend Dependencies

```bash
cd ../frontend
npm install
```

### Configure the Database

- Create a MySQL database.
- Import the provided `init.sql` file.
- Update database credentials in the backend `.env` file.

### Start the Backend

```bash
cd backend
npm start
```

### Start the Frontend

```bash
cd frontend
npm run dev
```

---

# 📸 Screenshots

## 🏠 Home Page

<img width="1102" height="610" alt="Home Page" src="https://github.com/user-attachments/assets/8764bc95-3ed7-43a0-9530-fcc1c2e28e45" />

---

## 👤 Citizen Dashboard

<img width="915" height="524" alt="Citizen Dashboard" src="https://github.com/user-attachments/assets/100cac46-960f-4f8f-81a0-e5bc9a78ea13" />

---

## 🛡️ Administrator Dashboard

<img width="912" height="484" alt="Administrator Dashboard" src="https://github.com/user-attachments/assets/d91d97c2-f2a4-424e-aba7-3dfc8f564832" />

---

## 👷 Worker Dashboard

<img width="926" height="490" alt="Worker Dashboard" src="https://github.com/user-attachments/assets/fd15ed8d-4af7-4c75-97a6-1d948344f110" />

---

## ⭐ Feedback & Rating Module

<img width="963" height="524" alt="Feedback & Rating Module" src="https://github.com/user-attachments/assets/54f51dc1-5713-4c76-90e8-b42dc9555a5b" />

---

## 🎯 Key Highlights

- Developed a complete municipal complaint management system with secure role-based access control.
- Designed and implemented RESTful APIs for complaint management and user authentication.
- Integrated MySQL for efficient relational database management.
- Implemented secure image uploads using Multer.
- Enabled seamless frontend-backend communication using Axios.
- Built responsive dashboards for citizens, administrators, and workers.
- Tested backend APIs using Postman.
- Managed version control using Git and GitHub.

---

## 📖 Learning Outcomes

This project strengthened my understanding of:

- Full-Stack Web Development
- React.js
- Node.js
- Express.js
- MySQL Database Design
- RESTful API Development
- CRUD Operations
- Authentication & Authorization
- Image Upload Handling
- Client–Server Architecture
- Git & GitHub Workflow

---

## 🔮 Future Enhancements

- Email & SMS Notifications
- Real-Time Complaint Tracking
- Interactive GIS Map Integration
- AI-Based Complaint Categorization
- Complaint Priority Prediction
- Mobile Application
- Analytics Dashboard
- Multi-Language Support

---

## 👩‍💻 Author

**Aiswarya Vutla**

B.Tech – Artificial Intelligence & Machine Learning

📧 **Email:** appuvutla18@gmail.com

🔗 **GitHub:** https://github.com/AiswaryaVutla

💼 **LinkedIn:** https://www.linkedin.com/in/aiswarya-vutla1808/

---

## ⭐ Support

If you found this project useful or interesting, consider giving it a **⭐ Star** on GitHub. Your support motivates me to continue building impactful software solutions.

---

## 📄 License

This project is developed for educational and portfolio purposes.
