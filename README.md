# Flask Todo App (Dockerized & Deployed on AWS EC2)

A simple Todo web application built using Flask, SQLAlchemy, and SQLite database. The app allows users to manage daily tasks using basic CRUD operations.

This project is containerized using Docker and deployed on an AWS EC2 instance with a public Elastic IP.

---

## Live Demo
http://52.215.98.248:5000/

---

## Features
- Add new tasks  
- View all tasks  
- Delete tasks  
- Simple UI  
- Dockerized application  
- Deployed on AWS EC2  

---

## Docker Commands
Build image:
```bash
docker build -t flask-todo .

Run Container:
docker run -d -p 5000:5000 flask-todo

Deployment (AWS EC2)
Launch Ubuntu EC2 instance
Install Docker
Clone repository
Build Docker image
Run container
Access via Elastic IP

Screenshots
## 📸 Screenshots

### 🏠 Home Page
![Home Page](https://raw.githubusercontent.com/ShahzaibGhaznavi/flask-todo/main/screenshots/Home_page.png)

### ➕ Add Task
![Add Task](https://raw.githubusercontent.com/ShahzaibGhaznavi/flask-todo/main/screenshots/Add_task.png)

### 🗑️ Delete Task
![Delete Task](https://raw.githubusercontent.com/ShahzaibGhaznavi/flask-todo/main/screenshots/Delete_task.png)

### ☁️ EC2 Running
![EC2 Running](https://raw.githubusercontent.com/ShahzaibGhaznavi/flask-todo/main/screenshots/ec2_running.png)

Running on AWS EC2
Build image:
```bash
docker build -t flask-todo .

<!-- refresh trigger -->
