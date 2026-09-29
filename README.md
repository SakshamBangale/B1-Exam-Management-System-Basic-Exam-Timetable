# Exam Management System

A simple college Exam Management System where Admin can manage exam timetables and Students can view exams according to their year and section.

## Features

* Admin and Student authentication using Auth0
* Admin dashboard
* Student dashboard
* Admin can add exams
* Students can view their exam timetable
* Timetable filtered by year and section
* Basic form validation
* Protected routes using middleware
* MongoDB database

## Technologies Used

* HTML
* CSS
* JavaScript
* Bootstrap
* Node.js
* Express.js
* MongoDB
* Auth0

## How to Run

Clone the repository:

```bash
git clone <your-repository-url>
```

Go to the project folder:

```bash
cd exam-management-system
```

Install dependencies:

```bash
npm install
```

Create a `.env` file and add your MongoDB and Auth0 credentials:

```env
PORT=5000
MONGODB_URI=your_mongodb_uri

AUTH0_DOMAIN=your_auth0_domain
AUTH0_CLIENT_ID=your_auth0_client_id
AUTH0_CLIENT_SECRET=your_auth0_client_secret
AUTH0_CALLBACK_URL=http://localhost:5000/callback
```

Start the application:

```bash
npm start
```

Open:

```text
http://localhost:5000
```

## Authentication

Auth0 is used for user authentication and middleware is used to protect the required routes.

## Admin

Admin can add and manage exam timetable details such as:

* Subject
* Year
* Section
* Exam Date
* Exam Time

## Student

Students can view only the exams that match their own year and section.

## Database

MongoDB is used to store exam and user-related data.

## Project Scope

This project does not include:

* Seating arrangement
* Room allocation
* Exam clash detection
* Advanced timetable generation

## Developer

Saksham Rajendra Bangale
