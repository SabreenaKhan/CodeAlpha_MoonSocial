🌙 MoonSocial - Full Stack Social Media Platform
MoonSocial is a modern, responsive social media application built during my CodeAlpha Web Development Internship. It features a clean, minimalist UI with full-stack capabilities including user authentication, real-time data fetching, and a relational database backend.

🚀 Features
User Authentication: Secure login and registration using JWT (JSON Web Tokens) and cookies.

Dynamic Feed: View posts from users you follow, ordered by the latest activity.

Profile Customization: Fully functional "Update Profile" system allowing users to change their Name, City, Website, Profile Picture, and Cover Photo.

Interactions: Real-time Like and Comment systems with dynamic counts.

Content Management: Users can create new posts with images and delete their own posts (enforced by server-side ownership checks).

Responsive Design: Aesthetic, mobile-friendly UI built with Sass and Material UI Icons.

🛠️ Tech Stack
Frontend:

React.js (Hooks, Context API)

React Query (TanStack Query) for efficient data caching & state management.

Sass for advanced styling and "Soft Girl" aesthetic themes.

Axios for API communication.

Backend:

Node.js & Express

MySQL (Relational Database)

Multer for handling multi-part file uploads (images).

JWT & bcryptjs for secure authentication.

📸 Project Architecture
The application follows a structured client-server architecture:

Client: Handles the UI and optimistic updates via React Query.

Server: Express REST API managing business logic and middleware.

Database: MySQL schema handling relational data between users, posts, likes, and comments.

⚙️ Installation & Setup
Clone the repository:

Bash
git clone https://github.com/SabreenaKhan/CodeAlpha_MoonSocial.git
Install dependencies:

Bash
# For Backend
cd api && npm install
# For Frontend
cd client && npm install
Setup Environment Variables:
Create a .env file in the api folder:

Code snippet
JWT_SECRET = your_secret_key
DB_HOST = localhost
DB_USER = your_mysql_user
DB_PASSWORD = your_mysql_password
DB_NAME = social
Run the application:

Bash
# Start Backend (Port 8000)
npm start
# Start Frontend (Port 3000)
npm start


🎓 Internship Milestone
This project was developed as Task 1 of the CodeAlpha Web Development Internship. It demonstrates proficiency in CRUD operations, relational database management, and modern frontend architecture.

Developed by: Sabreena Khan

Location: Lucknow, UP
