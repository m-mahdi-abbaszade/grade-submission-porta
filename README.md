# Grade Submission Portal

A practice project consisting of **two services**:

1. **Flask Portal**: A web interface for submitting student grades.
2. **Node.js API**: A service for managing and storing grades.

This project is fully **containerized using Docker and Docker Compose** for easy deployment and management.

---

## Project Structure

07-starter-code/
├─ grade-submission-portal/ # Flask app
│ ├─ app.py
│ ├─ Dockerfile
│ ├─ requirements.txt
│ └─ templates/ + static/
├─ grade-submission-api/ # Node.js API
│ ├─ app.js
│ ├─ Dockerfile
│ └─ package.json
└─ docker-compose.yml


---

## Prerequisites

- Docker
- Docker Compose

---


## Important Notes
The GRADE_SERVICE_HOST environment variable in Flask Portal defines where the Node.js API is located.

node_modules and __pycache__ are ignored via .gitignore.

For production, use a proper WSGI server instead of the Flask development server.

---


## Author
Mohammad Mahdi Abbaszadeh


 


