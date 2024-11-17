# 🍴 Bite-Me: Restaurant Management System  

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white)  
![JavaFX](https://img.shields.io/badge/JavaFX-GUI-blue?style=for-the-badge)  
![MySQL](https://img.shields.io/badge/MySQL-005C84?style=for-the-badge&logo=mysql&logoColor=white)  
![License](https://img.shields.io/badge/License-Academic-red?style=for-the-badge)  

---

## 📖 Overview  
**Bite-Me** is a fully functional and scalable restaurant management system designed to manage multiple branches with ease.  
It was developed as part of a group project for the *Engineering Methods for Software Systems Development* course during our third year.  

**Key Features:**  
- Multi-role system: Customers, HR, CEO, Branch Managers, Restaurant Managers.  
- Interactive GUI built with **JavaFX** (using Scene Builder).  
- Real-time notifications and reports.  
- Secure and optimized with **multi-threading**.  

---

## 🎯 Features  

### 🔑 User Roles  
| Role              | Key Features                                                                |
|-------------------|-----------------------------------------------------------------------------|
| **Customer**      | Place orders, track orders, receive notifications.                          |
| **Branch Manager**| Approve employees, create user accounts, manage permissions, view reports.  |
| **HR**            | Add new employees to the system.                                            |
| **CEO**           | Access reports for all branches, including performance data.                |

### 🛠️ General Features  
- **Secure Login System:** Role-based access for various users.  
- **Real-time Notifications:** Powered by Twilio for customer updates.  
- **PDF Reports:** Generate and download branch and performance reports (via iTextPDF).  
- **Automated Setup:** Initialize the database with basic data automatically.  
- **Performance Optimization:** Multi-threaded architecture for faster, concurrent operations.  
- **Real-time Monitoring:** Track logged-in users and request activity.  

---

## 🧑‍💻 Technical Architecture  

### **Client-Server Communication**  
- The client sends structured requests, and the server handles database operations and returns responses.  
- Communication is facilitated by a custom `Message` class for structured data exchange.  

### **Server-Side Features**  
- **Concurrency:** Multi-threading allows the server to handle multiple requests simultaneously.  
- **Database Security:** Ensures safe operations to prevent data breaches.  

### **Database**  
- **MySQL:** Centralized storage for all user, order, and branch data.  
- Automated initialization for quick deployment.  

---

## 🛠️ Technology Stack  

| Component        | Technology                                                                 |
|------------------|---------------------------------------------------------------------------|
| **Frontend**     | JavaFX (designed with Scene Builder).                                    |
| **Backend**      | Java.                                                                    |
| **Database**     | MySQL.                                                                   |
| **Notifications**| Twilio API.                                                              |
| **Reports**      | iTextPDF.                                                                |
| **Framework**    | OCSF (Object Client/Server Framework, provided by the college).          |

---

## 🚀 Installation  

1. **Clone the repository:**  
   ```bash  
   git clone https://github.com/MohamedAboSaleh/Bite-Me.git

2. **Set up the database:**
- Import the provided SQL file into your MySQL server (bitemedb.sql).

3.**Run the server application:**

- Start the server to handle requests and manage data.

4.**Launch the client application:**

- Interact with the system through its intuitive JavaFX GUI.

---
## 💡 Usage
- Server: Manages database interactions, client requests, and responses.

- Client: User interface for various roles to perform actions like ordering, managing employees, and viewing reports.

---
## 🤝 Team Contributions
### My Role
I was responsible for:

- Implementing functionalities for Branch Manager and CEO roles.

- Enhancing communication with an improved Message class for efficient client-server data exchange.

- Adding multi-threading to handle concurrent user requests.

- Securing MySQL database operations.

- Automating database initialization for streamlined deployment.

- Designing JavaFX GUI components using Scene Builder.
---

## 🏆 Challenges and Achievements
### Challenges:
- Optimizing performance for concurrent requests.

- Designing secure client-server communication.

- Creating role-specific features and functionalities.

### Achievements:
- Enhanced system performance through multi-threading.

- Improved user experience with a sleek and interactive GUI.

- Successfully implemented real-time user tracking and notifications.

- Built scalable, secure, and user-friendly software.

---

## 📜 License
This project was developed for academic purposes under the supervision of **Braude College of Engineering**. 


