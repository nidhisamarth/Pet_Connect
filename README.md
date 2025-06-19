# Pet_Connect

PetConnect – Pet Adoption Platform

PetConnect is a responsive web application that enables users to browse, filter, and adopt pets. It provides real-time listings and chat functionality, allowing seamless communication between adopters and shelters.

Built using modern web technologies like React, TypeScript, Node.js, and Firebase, the app focuses on creating an intuitive, fast, and engaging adoption experience.

Tech Stack

- Frontend: React, TypeScript, SCSS
- Backend: Node.js, Express.js
- Database: MongoDB
- Real-Time Communication: Firebase
- UI: Responsive layout using Flexbox and modular components

Key Features

- Pet Listings: Browse adoptable pets with filters by type, age, and location  
- Live Chat: Communicate in real-time with shelters using Firebase  
- Pet Profiles: View detailed info and images for each pet  
- Responsive Design: Optimized for desktop and mobile devices  
- Role-based Access: Shelter vs. Adopter user views  
- Authentication: Login, registration, and password reset with Firebase Auth  
- Form Validation: Built-in validation using React Hook Form and custom hooks  

Installation

1. Clone the repository
2. Install dependencies
3. Start the development server.
4. Open http://localhost:3000 to view the app in your browser.

Folder Structure

PetConnect/
├── client/                 React frontend
│   ├── components/         Reusable UI components
│   ├── pages/              Application views
│   ├── styles/             SCSS styling
│   └── firebase/           Firebase chat & auth configs
├── server/                 Node.js backend
│   ├── routes/             API routes
│   ├── controllers/        Business logic
│   └── models/             Mongoose schemas

Future Enhancements

- Admin dashboard for shelter staff  
- Pet image uploads using Cloudinary or Firebase Storage  
- Google Maps integration for geolocation filtering  
- Push notifications for chat and adoption status updates  


