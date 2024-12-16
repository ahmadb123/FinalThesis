# Final Thesis E-Commerce Project

## Table of Contents
- [About The Project](#about-the-project)
- [Built With](#built-with)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
- [Roadmap](#roadmap)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)
- [Acknowledgments](#acknowledgments)

---

## About The Project
This project is a comprehensive e-commerce platform built as part of my final thesis. It aims to deliver a secure, user-friendly online shopping experience. The platform features user registration and authentication, product browsing, shopping cart functionality, and a secure checkout process. It is designed with scalability and security in mind, adhering to best practices for modern web applications.

### Key Features
- **JWT-based Authentication**: Secure login and role-based access.
- **Product Management**: Browse and filter products with dynamic categories.
- **Cart System**: Add items to the cart and view cart details.
- **Address Management**: Update or delete addresses in the user's profile.
- **Payment Integration**: PCI-DSS-compliant secure payment processing.
- **Role Support**: Admin and user roles for different functionalities.

---

## Built With
- **Backend**:
  - [Java](https://www.java.com/) (Spring Boot Framework)
  - [MongoDB](https://www.mongodb.com/) (Database)
- **Frontend**:
  - [React.js](https://reactjs.org/) (UI Framework)
- **Build Tools**:
  - [Gradle](https://gradle.org/) / [Maven](https://maven.apache.org/)

---

## Getting Started

To get a local copy up and running, follow these steps.

### Prerequisites
1. **Java 17** or later.
2. **MongoDB** installed and running locally or remotely.
3. **Node.js** and **npm** for the frontend.
4. **Gradle** or **Maven** for backend builds.

### Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/ahmadb123/finalthesis.git
  ## Backend navigation ->
  cd ~/finalthesis/backend
  Configure environment-
  spring.data.mongodb.uri=mongodb://localhost:27017/ecommerceApp
  jwt.secret=your_jwt_secret_key
  jwt.expiration=86400000
  
  ## Build the backend 
  ./gradlew build
  run the application-
  java -jar target/<your-jar-file>.jar

  ## Frontend setup 
  cd ~/Finalthesis/frontend
    install dependency - 
    npm install
  ## start frontend 
    npm start 

  
## Usage
- **Access the Backend API**: [http://localhost:8080/api](http://localhost:8080/api)
- **Access the Frontend**: [http://localhost:3000](http://localhost:3000)



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



  


