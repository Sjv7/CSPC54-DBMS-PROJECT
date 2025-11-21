# **Project Management System (PMS) — Django + React + PostgreSQL**

This is a full-stack **Project Management System (PMS)** built using:

* **Django REST Framework** — Backend API
* **React.js** — Frontend single-page application
* **PostgreSQL** — Primary database
* **Token Authentication** for secure user access

The PMS allows users to manage **clients, projects, and to-do tasks**, providing a simple and effective project-tracking workflow.

---

## 🚀 **Features**

### 🔐 Authentication

* User registration & login
* DRF Token Authentication
* Secure access to protected API routes

### 👤 Client Management

* Create, view, update, and delete clients
* User-specific client filtering

### 📂 Project Management

* Manage multiple projects
* Filter by status (active/completed) and client
* Automatically associate projects with logged-in user

### 📝 To-Do / Task Management

* Add tasks under specific projects
* Track status (pending / completed)
* Filter tasks by project or status

### 🎨 Frontend Highlights

* React-based responsive UI
* React Router navigation
* Cookies for token persistence
* Clean component structure (Login, Client, Project, Tasks, Nav)

### 🛠️ Backend Highlights

* Django REST viewsets
* Token authentication
* Filters using `django-filter`
* CORS enabled for frontend compatibility
* PostgreSQL database integration

---

## 📁 **Main Pages**

* **Login**
* **Registration**
* **Home Dashboard**
* **Clients Page**
* **Projects Page**
* **Tasks Page**

---

## 🏗️ **Tech Stack**

### **Frontend**

* React.js
* React Router
* React Cookies
* Styled Components
* Bootstrap

### **Backend**

* Django
* Django REST Framework
* DRF Token Authentication
* django-filter
* CORS Headers

### **Database**

* **PostgreSQL**
