# Public Service Tracker

Service Tracker is a web-based complaint management system designed to help users submit service-related issues and allow administrators to monitor, manage, and resolve those requests efficiently.

The project focuses on building a **simple, clean, and functional real-world workflow** using core web technologies without heavy frameworks, making it ideal for academic learning and beginner-level full-stack development practice.

---

## Project Overview

The system allows users to register, log in, and submit service complaints or requests.  
Each request is stored in the database and becomes visible to the administrator through a dedicated admin dashboard.

Administrators can view total users, total complaints, pending issues, and resolved requests in real time.  
They can manage reports, review feedback, and track the resolution status of every complaint.

Email functionality is integrated so that important system notifications can be sent to users when required.

---

## Core Features

- User registration and login system  
- Complaint / service request submission  
- Admin dashboard with real-time statistics  
- Pending and resolved complaint tracking  
- User management and feedback viewing  
- Email notification support using PHPMailer  
- Clean, responsive, and beginner-friendly interface  

---

## Technologies Used

### Frontend
- **HTML5** for page structure  
- **CSS3** for styling, layout, and responsiveness  
- **JavaScript** for basic interactivity  

### Backend
- **PHP** for server-side logic and authentication  
- **MySQL** for database management  

### Email Service
- **PHPMailer** for sending system emails and notifications to users  

These technologies were chosen to keep the system **lightweight, understandable, and suitable for academic projects**.

---

## How the System Works

1. A user creates an account and logs into the system.  
2. The user submits a service complaint or request through the interface.  
3. The request is stored in the MySQL database with a default **pending** status.  
4. The administrator logs into the admin dashboard and reviews submitted complaints.  
5. The admin can update the complaint status to **resolved** after action is taken.  
6. When required, an email notification can be sent to the user using **PHPMailer**.  

This workflow demonstrates a **complete request-to-resolution lifecycle** similar to real service management systems.

---

## Running the Project Locally

1. Install **XAMPP** or **WAMP**.  
2. Place the project folder inside the server directory (for example, `htdocs`).  
3. Create a **MySQL database** and import the required tables.  
4. Update database credentials inside the PHP configuration file.  
5. Start **Apache** and **MySQL** from the control panel.  
6. Open the project in a browser using:

---

## Learning Objectives

This project helps in understanding:

- Full-stack web development using PHP and MySQL  
- Session-based authentication  
- CRUD operations in real applications  
- Admin dashboard design and workflow  
- Email integration using PHPMailer  

---

## Future Improvements

- Search and filter complaints  
- AJAX-based real-time updates  
- Role-based access control  
- File upload support for complaints  
- Dashboard analytics and charts  
- Deployment on a live production server  

---

## Author

**Shahzad Khan**  
BCA Student

## License

This project is developed for **educational purposes**.  
You are free to use, modify, and learn from this project.
