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
![image alt](https://github.com/ShahzaibGhaznavi/flask-todo/blob/e196e0817d956bca6bcd9836ab64675429226f27/Home%20page.png)


Add Task

Delete Task
Running on AWS EC2
Build image:
```bash
docker build -t flask-todo .
