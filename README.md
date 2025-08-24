<img width="1845" height="920" alt="Screenshot 2025-05-14 133246" src="https://github.com/user-attachments/assets/e37b21ce-1b81-4a92-8ef2-c876be39bcea" /># 🎉 Event Management System

An **Event Management System** built using **Java, MySQL, HTML, CSS, and JavaScript**.  
This project allows users to create, manage, and participate in events while providing administrators tools to oversee the system.

---

## 📌 Features
- 🔐 **User Authentication** – Sign up, login, and manage profiles
- 📝 **Event Management** – Create, update, delete, and view events
- 📅 **Event Calendar** – Display upcoming events in a user-friendly view
- 👥 **Participant Registration** – Users can register for events
- 📊 **Admin Dashboard** – Manage all users, events, and registrations
- 💾 **Database Integration** – Store event and user data securely in MySQL

---

## 🛠️ Tech Stack
- **Frontend:** HTML, CSS, JavaScript  
- **Backend:** Java (Servlets/JSP or Core Java depending on your setup)  
- **Database:** MySQL  
- **Version Control:** Git & GitHub  

---

## 📂 Folder Structure
Event-management-System/
│-- frontend/ # UI (HTML/CSS/JS)
│ ├── index.html
│ ├── style.css
│ └── script.js
│
│-- backend/ # Java source code
│ ├── src/
│ └── Main.java
│
│-- database/ # SQL scripts
│ └── schema.sql
│
└── README.md # Documentation

## ⚙️ Setup Instructions

### 1. Clone the Repository
```bash
git clone https://github.com/karthikeyanr62vk/Event-management-System.git
cd Event-management-System
2. Configure Database
Install MySQL and create a database (e.g., eventdb)

Import database/schema.sql into MySQL:

sql
Copy
Edit
mysql -u root -p eventdb < database/schema.sql
Update DB connection details in your Java backend config file.

3. Run Backend
If using Java:

bash
Copy
Edit
javac Main.java
java Main
4. Run Frontend
Open frontend/index.html in a browser

Or use Live Server (VS Code extension) for better experience.

📄 License
This project is licensed under the MIT License.

👨‍💻 Author
Karthikeyan R
