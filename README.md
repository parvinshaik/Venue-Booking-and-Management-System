# 🎪 VenueHub – Venue Booking & Management System

**VenueHub** is a full-stack web application built using the **MERN** stack (MongoDB, Express.js, React, Node.js) that streamlines the booking and management of venues such as auditoriums, seminar halls, and classrooms — especially for educational institutions.

It features a structured and transparent **multi-level approval workflow** involving Event Coordinators, Heads of Departments (HODs), and Principals. The platform also automates communication and generates official documents to simplify event organization.



## 🔥 Key Features

- 🧑‍🎓 **Role-based User Authentication**
  - Supports Students, Event Coordinators, HODs, Principals, and Admins
- 🗓️ **Real-time Venue Booking**
  - Book venues with live availability tracking
- 🔁 **Multi-level Approval Workflow**
  - Event requests follow a structured review process
- 📧 **Email Notifications**
  - Automated email alerts at every stage of approval
- 📄 **PDF Generation**
  - Approval letters and summaries generated automatically
- 📊 **Admin Dashboard**
  - Insights on booking trends and venue usage
- 🔐 **JWT-based Secure Authentication**
- 📱 **Responsive Design**
  - Works smoothly on mobile, tablet, and desktop



## 🛠️ Tech Stack

### Frontend
- **ReactJS**
- **TailwindCSS**
- **Axios**

### Backend
- **Node.js**
- **Express.js**

### Database
- **MongoDB**
- **Mongoose**

### Other Libraries & Tools
- **JWT** – for secure user sessions
- **Nodemailer** – for sending emails
- **PDFKit** – for generating PDFs



## 📂 Folder Structure
venue-hub/
├── backend/ # Node.js & Express API
│ ├── models/
│ ├── routes/
│ ├── controllers/
│ ├── middleware/
│ └── .env
├── frontend/ # ReactJS client
│ ├── src/
│ ├── public/
│ └── .env
├── .gitignore
└── README.md
