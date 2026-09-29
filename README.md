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




<img width="1600" height="801" alt="WhatsApp Image 2026-09-29 at 2 02 08 PM" src="https://github.com/user-attachments/assets/4dea549d-faca-4b11-ab39-f9c62fa9b061" />
<img width="1600" height="807" alt="WhatsApp Image 2026-09-29 at 2 04 49 PM" src="https://github.com/user-attachments/assets/392a53dd-612c-422f-8bbb-04ed3eff4163" />
<img width="1600" height="798" alt="WhatsApp Image 2026-09-29 at 2 04 02 PM" src="https://github.com/user-attachments/assets/6f1e336b-0415-465b-b59f-9e37562f0d0a" />
<img width="1600" height="809" alt="WhatsApp Image 2026-09-29 at 2 03 49 PM" src="https://github.com/user-attachments/assets/30bfc1ad-2498-4bbe-9113-deae929f55b0" />
<img width="1600" height="804" alt="WhatsApp Image 2026-09-29 at 2 03 20 PM" src="https://github.com/user-attachments/assets/a45dac60-3d81-4c75-bd09-b1f2abd91baf" />
<img width="1600" height="802" alt="WhatsApp Image 2026-09-29 at 2 00 06 PM" src="https://github.com/user-attachments/assets/3a542281-60b1-46a9-89d0-d420712ca444" />
<img width="1600" height="822" alt="WhatsApp Image 2026-09-29 at 1 58 25 PM" src="https://github.com/user-attachments/assets/92ac3f00-09dd-4269-8a92-36957492bdd9" />
<img width="1600" height="822" alt="WhatsApp Image 2026-09-29 at 1 58 25 PM (1)" src="https://github.com/user-attachments/assets/c9a082c1-9f73-4e30-bcda-99580c44500b" />
<img width="240" height="618" alt="WhatsApp Image 2026-09-29 at 1 57 11 PM" src="https://github.com/user-attachments/assets/a97cb753-e5ef-40b8-b3a6-74a370124b08" />

