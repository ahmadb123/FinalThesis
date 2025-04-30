# GamerHub
### A unified platform for gamers to connect, share, and stay up-to-date with the latest in gaming.

## Table of Contents
- [About The Project](#about-the-project)
- [Key Features](#Key Features)
- [Tech Stack](#Tech Stack)
- [Getting Started](#Getting Started)
    - [Prerequisites](#prerequisites)
    - [Installation](#installation)
- [Usage](#contact)
- [Configuration](#Configuration)
- [Directory Structure](#Directory Structure)
- [Contact](#Contact)

---

## About The Project
GamerHub brings together your favorite gaming platforms—Xbox, PlayStation, Steam, and more—into one place.
Create or join chats and groups, share news and game info, plan events, and discover up-to-date trailers and reviews.


### Key Features
- ** Gamertag-Based Login: Authenticate via Xbox, PlayStation, Steam, or a custom gamertag. Link multiple accounts under one unified profile.
- ** Chats & Groups Topic-based chat rooms (e.g., “Elden Ring Players”). Group roles (admins, moderators) and threaded discussions.
- ** Centralized News Feed Aggregates updates from Xbox News, PlayStation Blog, Steam News, etc. Filter by platform, genre, or personalized preferences.
- ** Game Info & Trailers Searchable database powered by IGDB for release dates, trailers, reviews. One-click shareable game pages in chat.
- ** Social & Community Real-time notifications for mentions and replies. Badges and gamification for top contributors. In-chat event scheduling and tournament planning.


---

## Tech Stack
  - Frontend: React.js, Tailwind CSS
  - Backend: Java 17, Spring Boot
  - Database: MySQL
  - [WebSockets: STOMP over SockJS for real-time messaging
  - APIs & Authentication: IGDB for game metadata Steam OpenID, Xbox OAuth2, Discord OAuth2 for user authentication YouTube API for trailers and videos Platform-specific news endpoints (Xbox News, PlayStation Blog, Steam News)

---



## Getting Started

### Prerequisites
1. ** Node.js (v16+) & npm
2. **Java 17+ & Maven
3. **MySQL (running locally or remotely)

### Installation

##Installation
1. ## git clone https://github.com/your-org/GamerHub.git  cd GamerHub
2. ## Backend Setup cd backend  
    # configure src/main/resources/application.properties (see below)  
    mvn clean package  
    mvn spring-boot:run  
    # runs on http://localhost:8080
3. ## Frontend setup cd ../frontend  
      npm install  
      npm start  
      # runs on http://localhost:3000  

  
## Usage
- **Sign up / Log in via your preferred gamertag.
- **Browse or create chat rooms and groups.
- ##Follow news feeds and share articles.
- ##Search for games, view trailers, and discuss in real time.

##Configuration
- ##In backend/src/main/resources/application.properties, set MySQL connection and JWT secret:
- ## spring.datasource.url=jdbc:mysql://localhost:3306/gamerhub
  spring.datasource.username=YOUR_DB_USER
  spring.datasource.password=YOUR_DB_PASS
  spring.jpa.hibernate.ddl-auto=update

  jwt.secret=your_jwt_secret_key
  jwt.expiration=86400000

  ## Directory Structure
  - ## GamerHub/
      ├── backend/               # Spring Boot service
      │   ├── src/
      │   │   ├── main/
      │   │   │   ├── java/...   # controllers, services, models, repos
      │   │   │   └── resources/
      │   │   │       └── application.properties
      │   └── pom.xml
      └── frontend/              # React application
          ├── public/
          ├── src/
          │   ├── components/
          │   ├── service/
          │   ├── App.jsx
          │   └── index.jsx
          └── package.json


## Contact
- **Author**: Ahmad Bishara  
- **Email**: [abishara@mail.endicott.edu](mailto:abishara@mail.endicott.edu)  
- **GitHub**: [ahmadb123](https://github.com/ahmadb123)


## Acknowledgments
- [Spring Boot](https://spring.io/projects/spring-boot)
- [MongoDB](https://www.mongodb.com/)
- [React.js](https://reactjs.org/)
- [JWT](https://jwt.io/)
- [Gradle](https://gradle.org/)



  


