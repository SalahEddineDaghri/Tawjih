# Tawjih - Student Management and Course Selection Platform

## Overview

Tawjih is a comprehensive web platform designed to help students manage their academic journey and course selections. The platform consists of two main components:
- A modern React + TypeScript frontend (`new-frontend-tawjih`)
- A Laravel 12 backend API (`tawjih-backend-laravel`)

## 🚀 Features

### **Student Management System**
- **Multi-step Registration Process**
  - Personal information with bi-lingual support (French/Arabic)
  - Parent and guardian information management
  - Academic background and transcript tracking
  - Document uploads (CIN, photos, academic certificates)
  - Form pre-filling for returning users

- **User Authentication & Authorization**
  - Role-based access control (Student, Admin, Employee, Secretary)
  - Secure JWT-based authentication via Laravel Sanctum
  - Session management and automatic data recovery

- **Academic Tools**
  - Course catalog browsing and filtering
  - University application submission and tracking
  - Subscription and payment management
  - Academic counselor assignment system

- **Administrative Dashboard**
  - Student application processing and approval workflows
  - Document verification and status tracking
  - University and course management
  - Analytics and reporting tools
  - Bulk operations for administrative tasks

## 🛠️ Tech Stack

### Frontend (`new-frontend-tawjih`)
- **React 18.3.1** with TypeScript for type safety
- **Vite** for fast development and building
- **Redux Toolkit** for centralized state management
- **React Router 7** for client-side routing
- **React Hook Form** with Yup validation
- **Tailwind CSS** for responsive styling
- **i18next** for internationalization (French/Arabic)
- **Lucide React** for consistent iconography
- **Axios** for API communication

### Backend (`tawjih-backend-laravel`)
- **Laravel 12.0** with PHP 8.2+
- **Laravel Sanctum** for API authentication
- **MySQL** database with Eloquent ORM
- **RESTful API** architecture
- **File upload handling** for documents
- **CORS configuration** for cross-origin requests
- **Database migrations and seeders**
