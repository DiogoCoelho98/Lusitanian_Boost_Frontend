# Lusitanian Boost

## Description
Lusitian Boost is a web application designed to combat sedentary behavior through interactive challenges. Additionally, it allows users to strategize and track their advancement, empowering them to reach their fitness goals.
 
## Built With 
<img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5 icon" />
<img src="https://img.shields.io/badge/CSS-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS icon" />
<img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=white" alt="React icon" />
<img src="https://img.shields.io/badge/Chakra_UI-319795?style=for-the-badge&logo=chakra-ui&logoColor=white" alt="Chakra UI icon" />
<img src="https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white" alt="MongoDB icon" />
<img src="https://img.shields.io/badge/Mongoose-880000?style=for-the-badge&logo=mongoose&logoColor=white" alt="Mongoose icon" />
<img src="https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white" alt="Express icon" />
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript icon" />

## Features
- **Browse through a list of challenges, members results, and coaches**
- **View training sessions details** such as type of workout, description, exercises, etc
- **Add new training session** (requires authentication)
- **Edit/Delete existing traning session** (requires authentication)
- **Add/Update/Delete tracking variables, like bodyweight, number os steps, etc** (requires authentication)
- **User registration**
- **User authentication with email/password**

## Getting Started
### Prerequisites
- Node.js: Make sure Node.js is installed. You can download it here [Node.js](https://nodejs.org/en)
### Installation
```
git clone https://github.com/DiogoCoelho98/Lusitanian_Boost_Backend.git
cd Lusitanian_Boost_Backend
```
```
npm install
```
### Environment Variables
Create a `.env` file in the root directory of the project and add the following environment variables:
```
- PORT=3000
- MONGODB_URI=<your-mongodb-uri>
- TOKEN_SECRET=<your-jwt-secret>
- ORIGIN= 'http://localhost:5173'
- VITE_SERVER_URL = 'http://localhost:5005'
```
### Starting the Server
1. Run the server
```
node server.js
```
```
nodemon server.js
```
2. View Lusitanian Boost in your browser
- Open your web browser and navigate to http://localhost:3000 (or another port you specified).
### Usage
- Explore challenges, different coaches : Browse through various workouts, and view the details for each.
- Add/Update/Delete training session/track parameters: Register and login are necessary.

## Project Link
**https://project-3-frontend-ten.vercel.app/**

## Contacts
- **https://www.linkedin.com/in/diogo-borges-coelho/**
- **diogocoelho19988@gmail.com**



