# Contact_Book
<img width="1920" height="1080" alt="Screenshot (6)" src="https://github.com/user-attachments/assets/3863086d-a4a9-42d6-9284-e0327eefca53" />
Contact Book App 📒

A modern Single Page Application (SPA) built with Vue 3 for managing personal contacts. This project is developed for the MTM6407 Web Development IV course (Week 10 Assignment).

🚀 Overview

This application allows users to store, manage, and search through their contacts efficiently. It leverages the browser's LocalStorage to persist data, ensuring contacts remain saved even after refreshing the page. The user interface is designed with Tailwind CSS for a clean, responsive, and mobile-friendly experience.

✨ Features

List View: Displays contacts sorted alphabetically by Last Name.

Search & Filter: Real-time filtering of contacts by First Name or Last Name.

Contact Details: View full information (Email, Phone) for a specific contact.

CRUD Operations:

Create: Add new contacts with auto-generated IDs.

Read: View contact details.

Update: Edit existing contact information.

Delete: Remove contacts permanently.

Data Persistence: All data is stored in the browser's LocalStorage.

Responsive Design: Fully functional on desktop and mobile devices.

🛠️ Technologies Used

Vue 3: Composition API for state management and component logic.

Vue Router 4: For handling SPA navigation (Home, Details, Add, Edit).

Vite: Next Generation Frontend Tooling.

Tailwind CSS: Utility-first CSS framework for styling.

LocalStorage API: For client-side data persistence.

📦 Project Setup

To run this project locally, follow these steps:

Prerequisites

Node.js (v14.0.0 or higher)

npm (usually comes with Node.js)

Installation

Clone the repository:

git clone [https://github.com/Guer0157/contact-book-app.git](https://github.com/Guer0157/contact-book-app.git)
cd contact-book-app


Install dependencies:

npm install


Run the development server:

npm run dev


Open your browser and navigate to http://localhost:5173 (or the port shown in your terminal).

Building for Production

To build the project for deployment:

npm run build


📂 Project Structure

src/
├── assets/          # Static assets and global styles
├── router/          # Vue Router configuration
├── views/           # Page components (Home, Details, Form)
├── App.vue          # Root component
└── main.js          # Application entry point


👤 Author

GitHub: Gagan

Course: MTM6407 - Web Development IV
