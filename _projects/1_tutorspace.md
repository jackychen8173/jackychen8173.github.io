---
layout: page
title: TutorSpace
description: Full-stack tutoring management platform
img: 
importance: 1
category: personal
github: https://github.com/yourusername/tutorspace
---

A comprehensive tutoring management web application designed to streamline session scheduling, student tracking, and administrative tasks for tutors and tutoring businesses.

## Overview

TutorSpace provides tutors with a centralized platform to manage their students, schedule sessions, track progress, and handle administrative workflows. The platform features role-based authentication to support both tutors and students with appropriate access controls.

## Tech Stack

**Backend**
- **Spring Boot** - REST API framework
- **Spring Data JPA** - Database persistence
- **PostgreSQL** - Relational database
- **JWT** - Stateless authentication

**Frontend**
- **Next.js** - React framework with server-side rendering
- **React** - Component-based UI
- **TypeScript** - Type-safe development

## Key Features

**Authentication & Authorization**
- JWT-based authentication system
- Role-based access control (TUTOR/STUDENT)
- Secure session management

**Session Management**
- Create and schedule tutoring sessions
- Track session history
- Manage student enrollment

**Architecture**
- Layered architecture (Controller → Service → Repository)
- JPA entities for User and Session models
- RESTful API design
- Separation of concerns between frontend and backend

## Current Status

In active development. Core authentication and session management features implemented. Next steps include adding payment processing, calendar integration, and student progress tracking.

## What I Learned

- Building a full-stack application from scratch with modern frameworks
- Implementing JWT authentication in Spring Boot
- Designing RESTful APIs with proper layering
- Integrating React frontend with Spring Boot backend
- Database schema design for relational data

<!-- Add screenshots when available:
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/tutorspace-dashboard.png" title="Dashboard" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
-->