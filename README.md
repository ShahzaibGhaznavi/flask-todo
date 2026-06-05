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
Home Page (UI)
<img width="1366" height="768" alt="ec2 server" src="https://github.com/user-attachments/assets/ef7000c1-d55a-439a-88d9-e00692652ca9" />
<img width="1366" height="768" alt="Delete Task" src="https://github.com/user-attachments/assets/e46c8744-5191-433d-bea4-e6a26b7d0304" />
<img width="1366" height="768" alt="Add Task" src="https://github.com/user-attachments/assets/de05063b-2636-471c-b509-04badffdc1a6" />
<img width="1366" height="768" alt="Home page" src="https://github.com/user-attachments/assets/cd63ac94-ddb1-4e8d-8aff-ae7f17d2be76" />


Add Task
Delete Task
Running on AWS EC2
Build image:
```bash
docker build -t flask-todo .
