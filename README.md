# 🚀 CodeLab – Cloud Based Code Review System

![React](https://img.shields.io/badge/React-Frontend-blue)
![Supabase](https://img.shields.io/badge/Supabase-Backend-green)
![Cloud Computing](https://img.shields.io/badge/Project-Cloud%20Computing-orange)

CodeLab is a modern **cloud-based code review and project management platform** designed for developers, reviewers, and administrators. It enables seamless **code submission, structured review workflows, version tracking, and system administration** through role-based dashboards.

This project was developed as part of a **Cloud Computing academic project** and demonstrates how modern web technologies and cloud backend services can be used to build scalable developer collaboration tools.

---

# 📌 Project Overview

CodeLab provides a centralized platform where developers can submit code, reviewers can analyze and provide feedback, and administrators can manage the entire system.  

The platform simplifies the **code review workflow** by organizing submissions, maintaining version history, and ensuring secure user access through cloud-based authentication.

By integrating **React frontend technologies with Supabase cloud backend**, the application provides a modern, fast, and scalable developer platform.

---

# ✨ Key Features

## 🔐 Role-Based Access Control

The system supports three main user roles.

### 👨‍💻 Developer Dashboard
- Submit code for review
- Track submission status
- View version history with reviewer comments
- Manage profile information

### 🧑‍💻 Reviewer Dashboard
- Review submitted code
- View submission history
- Provide feedback with preserved formatting
- Manage review queues efficiently

### 🛠️ Admin Dashboard
- Manage all users and roles
- Delete users if required
- Monitor platform activities
- Maintain system control

---

## 📂 Submission Versioning

CodeLab tracks **multiple versions of code submissions**, allowing developers and reviewers to:

- View previous submissions
- Track improvements
- Maintain a clear development history

---

## 👤 Profile Management

Users can manage their personal profiles including:

- Updating personal details
- Uploading profile avatars
- Managing account information

---

## 🔑 Secure Authentication

Authentication and user management are handled using **Supabase**, providing:

- Secure login and registration
- Protected routes
- Role-based access
- Cloud database integration

---

## 🎨 Modern UI

The interface is built using modern UI technologies to provide:

- Clean design
- Responsive layout
- Smooth user experience
- Fast performance

---

## ⚡ Real-time Data Handling

CodeLab uses **React Query** to efficiently fetch and update data from the backend which provides:

- Faster API interactions
- Automatic caching
- Optimized performance
- Real-time updates

---

# 🛠️ Technology Stack

### Frontend
- React
- Vite
- JavaScript (JSX)

### Styling
- Tailwind CSS
- Shadcn UI

### State & Data Handling
- React Query
- Context API

### Backend & Cloud
- Supabase

### Routing
- React Router DOM

---

# ☁️ Cloud Integration

This project uses **Supabase**, a cloud backend platform that provides:

- Authentication
- Cloud database
- REST APIs
- File storage

Using Supabase eliminates the need to build a custom backend server.

---

# ⚙️ Getting Started

Follow the steps below to run the project locally.

---

# 📌 Prerequisites

Make sure you have installed:

- Node.js (v18 or higher recommended)
- npm or yarn
- Git

---

# 📥 Installation

### 1 Clone the Repository
git clone https://github.com/Sanjay83174/CodeLab-Code-Review-System


### 2 Navigate to Project Folder
cd code-lab


### 3 Install Dependencies
npm install


---

# 🔑 Supabase Setup (Step by Step)

If you are new to Supabase, follow these steps.

### Step 1: Create Supabase Account

Go to the official website:

https://supabase.com

Sign up using GitHub or email.

---

### Step 2: Create a New Project

1. Click **New Project**
2. Enter project name (example: `CodeLab`)
3. Set a strong database password
4. Choose a region
5. Click **Create Project**

Wait for the project to finish initializing.

---

### Step 3: Get API Credentials

After project creation:

1. Go to **Project Settings**
2. Click **API**
3. Copy the following values:

- Project URL
- Anon Public Key

---

### Step 4: Configure Environment Variables

Create a `.env` file in the root directory of the project.

Add the following:
VITE_SUPABASE_URL=your_supabase_project_url
VITE_SUPABASE_PUBLISHABLE_KEY=your_supabase_anon_public_key


---

### Step 5: Enable Authentication

In Supabase dashboard:

1. Go to **Authentication**
2. Open **Providers**
3. Enable **Email/Password Login**

This allows users to register and login.

---

### Step 6: Create Required Database Tables

Go to **Database → Table Editor** and create tables for:

- users
- submissions
- reviews
- comments

These tables will store:

- user information
- code submissions
- reviewer feedback
- version history

---

# ▶️ Run the Project

Start the development server.
npm run dev


---

# 🌐 Access the Application

Open your browser and go to:
http://localhost:5173


Register a new account and login to access the platform.

---

# 📖 Usage

1. Register or login to the platform
2. Access your dashboard depending on your role
3. Developers submit code
4. Reviewers provide feedback
5. Admin manages users and system

---

# 🎯 Project Objective

The goal of this project is to demonstrate how **cloud computing platforms can be used to build scalable collaborative developer tools**.

The system shows the practical implementation of:

- Cloud authentication
- Role-based access control
- Code review workflows
- Modern web application architecture

---

# 🔮 Future Improvements

Possible future enhancements include:

- AI-based code review suggestions
- Code syntax highlighting
- Notification system
- GitHub integration
- CI/CD pipeline integration
- Real-time collaboration

---

# 👨‍💻 Author

**Sanjay HL**

Developed as part of a **Cloud Computing Academic Project**

---

# ⭐ Support

If you find this project helpful, consider giving the repository a ⭐ on GitHub.
