
🩺 Dr. Siddesh.g.g – Clinical Consultation Interface

A futuristic clinical consultation web interface designed for secure patient appointment requests.
The application features a modern neon-themed UI, splash screen intro, and Firebase backend integration for storing patient consultation data.

🚀 Features

🌌 Futuristic UI Design

Deep Purple & Electric Blue theme

Neon glow effects

Glassmorphism card layout

🎬 Splash Screen Intro

Animated entry screen with doctor branding

Smooth fade transition into main interface

📋 Appointment Booking Form

Patient Name

Age Validation

Symptoms/Problem Description

🔐 Firebase Integration

Anonymous authentication

Firestore database storage

Secure appointment data submission

⚡ Dynamic Feedback System

Real-time success/error messages

Loading states during submission

🛠️ Technologies Used

HTML5

Tailwind CSS

JavaScript (ES Modules)

Firebase Authentication

Firebase Firestore

Google Fonts (Inter)

📂 Project Structure
project/
│
├── index.html       # Main application file
├── README.md        # Project documentation
⚙️ Setup Instructions
1️⃣ Clone or Download Project
git clone <your-repo-link>
cd project-folder
2️⃣ Configure Firebase

Create a Firebase project.

Enable:

Authentication (Anonymous Sign-In)

Firestore Database

Copy your Firebase configuration.

Replace environment variables:

const firebaseConfig = {
   apiKey: "YOUR_API_KEY",
   authDomain: "YOUR_DOMAIN",
   projectId: "YOUR_PROJECT_ID",
};
3️⃣ Run the Project

Simply open:

index.html

in your browser.

Or use Live Server in VS Code for best experience.

📊 Database Structure

Firestore Path:

artifacts/{appId}/public/data/appointments

Stored Fields:

name

age

problem

submittedByPatientId

timestamp

🔒 Security Notes

Currently allows public appointment submission.

For production:

Add Firestore security rules

Implement doctor/admin authentication

Use HTTPS hosting

Validate input server-side

🎨 UI Components

Splash Screen Transition

Neon Glow Buttons

Futuristic Input Fields

Glassmorphism Booking Card

🧑‍⚕️ Future Improvements

Admin dashboard for doctors

Appointment scheduling calendar

AI-based symptom triage

Email/SMS notifications

Dark/Light theme toggle

Patient login system
