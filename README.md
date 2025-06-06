# StudySync

StudySync is a full-stack study and productivity app that helps users set learning goals, track study time, and review material using a flashcard system powered by spaced repetition. Built with React, Redux, and Ruby on Rails, the app combines habit-forming design with extensible architecture and future-facing features like social interaction, gamification, and AI-assisted learning.

# 🚀 Features (MVP)
Learning Goals: Create, edit, delete, and track time spent on custom goals
Flashcards & Decks: Manage decks and cards, including nested flashcards
Spaced Repetition: Card review intervals adjust based on memory strength
Study Sessions: Log focused sessions tied to specific goals
Progress Dashboard: Track streaks, study time, and learning outcomes
Extensible Models: Built to support tagging, sharing, and public/private data

# 🧠 Stretch Goals (Tiers)
Tier 1: Public deck sharing, daily review dashboard, user settings, tagging
Tier 2: Followers, reactions, XP system, reminders, public profiles
Tier 3: Challenges, media-rich flashcards, reflections, activity timeline, AI card generation
Full breakdown of features and user stories: _project-details/project-summary.md

# 🛠 Tech Stack
Frontend
React (Vite)
Redux Toolkit
React Router
SCSS Modules
Backend
Ruby on Rails (API-only)
PostgreSQL
bcrypt (auth)
JBuilder (structured JSON)
Planning for future integration: Firebase/Cron (notifications), OpenAI API (AI flashcards)

# 📁 Folder Structure
client/ – React frontend
server/ – Rails API backend
_project-details/ – ERD, setup, task list, and documentation

# 🧪 Setup & Run Locally
bash
Copy
Edit

# Clone the repo
git clone https://github.com/ArcaneCipher/StudySync.git
cd StudySync

# Set up the backend
cd server
bundle install
rails db:create db:migrate db:seed
rails s
bash
Copy
Edit

# Set up the frontend
cd ../client
npm install
npm run dev
Visit http://localhost:5173 to start using the app.

# 🗂 API Structure
RESTful Rails routes with clearly scoped controllers for:
Auth: login/signup/logout
Goals: CRUD with time tracking
Decks & Flashcards: nested, with spaced repetition logic
Sessions: Study logs tied to goals
Reviews: Track memory performance + next due date
See full route design: _project-details/project-summary.md

## 👩🏾‍💻 Contributions
This project was built as part of a collaborative team effort.  
My contributions include:

- Implemented the Redux login/logout flow  
- Built and styled the login UI  
- Developed the study session tracking component  
- Integrated frontend logic with goal-related session data

Other team members contributed to backend setup, goal/deck models, and overall app design.

