# AI-Powered Community Health Management Platform - Backend

## Overview

This repository contains the backend services for the AI-Powered Community Health Management Platform. The system is designed to improve healthcare access and patient follow-up in rural and underserved communities by providing APIs for patient management, chronic disease monitoring, AI-assisted risk detection, notifications, and healthcare analytics.

## Features

* Patient registration and management
* Community Health Worker (CHW) management
* Chronic disease tracking
* Appointment and medication reminders
* AI-assisted risk assessment
* Real-time analytics and reporting
* Role-based authentication and authorization
* RESTful API architecture

## Technology Stack

* Node.js
* Express.js
* MongoDB
* JWT Authentication
* Python (AI/ML Services)
* Docker
* Git & GitHub

## Getting Started

### Prerequisites

* Node.js (v20+)
* MongoDB
* Git

### Installation

1. Clone the repository:

   ```bash
   git clone <repository-url>
   ```

2. Navigate to the project directory:

   ```bash
   cd backend
   ```

3. Install dependencies:

   ```bash
   npm install
   ```

4. Configure environment variables:

   ```env
   PORT=5000
   MONGO_URI=<your_mongodb_uri>
   JWT_SECRET=<your_jwt_secret>
   ```

5. Start the development server:

   ```bash
   npm run dev
   ```

## Project Structure

```text
src/
├── controllers/
├── routes/
├── models/
├── middleware/
├── services/
├── utils/
├── config/
└── app.js
```

## API Endpoints




