# Smart India Hackathon Workshop
# Date:28/04/25
## Register Number:21224220047
## Name:Keerthana C
## Problem Title
SIH1392 E-Waste Facility Locator
## Problem Description
Electronic waste (e-waste) generation is increasing at an alarming rate due to rapid technological advancements and short device lifespans. Despite the presence of certified recycling centers, people find it difficult to locate nearby, authorized e-waste collection facilities, leading to improper disposal practices, environmental degradation, and health hazards.
There is a need for an accessible solution that enables individuals and businesses to find verified e-waste collection and recycling facilities quickly and easily.
## Problem Creater's Organization
Ministry of organization
## Idea
1.Develop a web and/or mobile application that allows users to:
2.Locate nearby certified e-waste facilities using GPS or manual location entry.
3.View facility details (address, accepted materials, timings, contact).
4.Submit new facility suggestions for admin review.
5.Get awareness information on proper e-waste disposal practices.
6.Plan pickups (optional, if facilities provide logistics).
7.Track personal contribution to e-waste recycling (optional gamification).

## Proposed Solution / Architecture Diagram     

[User (Mobile/Web App)]
       |
       v
[Frontend App (React.js / Flutter)]
       |
       v
[Backend API Server (Node.js/Express)]
       |
       v
[Database (MongoDB / PostgreSQL)]
       |
       +--> [Facility Information DB]
       +--> [User Feedback/Suggestions DB]
       |
       v
[External APIs (Google Maps API, Location Services)]

                    


## Technology Stack
Layer | Technology
Frontend | React.js (Web) / Flutter (Mobile)
Backend | Node.js with Express.js
Database | MongoDB (NoSQL) or PostgreSQL (SQL)
Hosting/Cloud | AWS / Azure / Google Cloud Platform
Maps & Location | Google Maps API / Mapbox
Authentication | Firebase Auth / JWT (for login, if needed)
Admin Panel | React.js Admin Dashboard (e.g., using libraries like Material UI or Ant Design)
Notification Service | Firebase Cloud Messaging (FCM) (for optional mobile notifications)
CI/CD | GitHub Actions / Jenkins
Version Control | Git + GitHub / GitLab
## Dependencies
Google Maps API or Mapbox API (for geolocation and map rendering)

Node.js packages:

Express.js (backend server)

Mongoose or Sequelize (database ORM)

dotenv (environment variables)

bcrypt.js / JWT (for authentication)

Frontend packages:

React Router (for navigation)

Axios (for API communication)

Redux (optional, for state management)

Database:

MongoDB Atlas (if using cloud DB) or a hosted PostgreSQL instance

Hosting Platforms:

Vercel/Netlify (for frontend)

Heroku/AWS EC2/DigitalOcean (for backend)



