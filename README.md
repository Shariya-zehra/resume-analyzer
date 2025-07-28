💼 Resume Analyzer
AI-powered Resume Analyzer Web App that helps users analyze their resumes against job descriptions, extract relevant skills, calculate match percentage, and fetch real-time job suggestions.

🛠 Tech Stack
Backend: Java 17, Spring Boot, Maven, MySQL, JavaMail (OTP verification), Apache POI (PDF parsing), REST APIs

Frontend: HTML5, CSS3, Vanilla JavaScript

IDE: Spring Tool Suite (STS)

Database: MySQL (local setup)

Others: Ngrok (for local access), Remotive API (for live job suggestions)

✨ Features
✅ Email OTP Verification before resume upload

📄 PDF Resume Parsing to extract skills, email, phone

🤖 Keyword Matching against user-entered job description

📊 Match Percentage with glowing circular chart UI

💡 Job Suggestions using Remotive API

🔒 Secure resume upload and skill extraction

💻 Runs locally with frontend served via terminal

🚀 Getting Started
1️⃣ Backend Setup (Spring Boot)
Run this via Spring Tool Suite or mvn spring-boot:run

Configure application.properties with your MySQL and SMTP credentials.

Start MySQL server.

Ensure required tables are auto-created or initialize schema manually.

Start the backend:

🔑 API Highlights
POST /send-otp – Sends OTP to email

POST /verify-otp – Verifies entered OTP

POST /upload-resume – Uploads resume and analyzes content

POST /match-skills – Matches resume content with job description

GET /job-suggestions – Fetches real-time job suggestions via API

📌 Notes
Not deployed yet. Runs completely on local environment.

You must configure email (SMTP) and Remotive API key for full functionality.
