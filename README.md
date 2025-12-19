# Full-Stack To-Do List Application

This document explains how to run the backend (Node.js) and frontend (Angular)
of the To-Do List application locally.

---

## Backend (Node.js)

The backend provides RESTful API endpoints for managing tasks and connects to
MongoDB for data storage.

### Backend Requirements
- Node.js v22.11.0
- MongoDB 8.2.2 running locally

### Start MongoDB
Make sure MongoDB is running before starting the backend.

```bash
mongod

Install and Run Backend
cd backend
npm install
npm start

Install Angular CLI
npm install -g @angular/cli


Install and Run Frontend
cd frontend
npm install
ng serve
npm run dev  


Launch the Docker conterners

Créer les CONTENEURS

Conteneur MongoDB

docker run -d --name todo-mongo -p 27017:27017 -v mongo-data:/data/db mongo:8.2.2



docker run -d --name todo-frontend -p 4200:80 todo-frontend



