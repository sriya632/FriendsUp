# FriendsUp

The BFF FriendsUp website is a modern, user-friendly web application built with Flask for the backend and React for the frontend. The application is designed to manage a collection of friends and their details in a social network-style platform. Users can add, edit, and delete friends with an intuitive interface, utilizing Chakra UI for the design elements. The application makes HTTP requests to a Flask API to perform CRUD operations on the friend data stored in a SQLite database.

This project leverages Postman for API testing and ensures smooth integration between the frontend and backend. It is built to provide an engaging and responsive experience for managing your friend list.

# Project Purpose

The purpose of this project is to create a web-based platform that allows users to:

Add new friends to a list with their personal information, such as name, role, description, and gender.

Edit existing friend details.

Delete friends from the list.

View friends' information in a grid layout.

# Tech Stack

Frontend: React, Chakra UI, React Icons

Backend: Flask, SQLAlchemy

Database: SQLite

Authentication: None (basic CRUD functionality)

Development Tools: Postman for API testing, VSCode for development

# Setting Up the Project

# Backend Setup (Flask)

Install dependencies:

Install Flask and SQLAlchemy along with flask-cors to handle CORS issues:

pip install flask flask-sqlalchemy flask-cors

Configure Flask:

Make sure the Flask app is configured correctly in app.py for the backend and has the necessary routes set up to handle requests for creating, editing, and deleting profiles. This app also connects to a SQLite database to persist user data.

Running Flask Server:

To start the backend server, run the following command in the terminal:

python app.py

The Flask backend will be running on http://127.0.0.1:5000

# Frontend Setup (React)

Install dependencies:

Navigate to the frontend folder and install the necessary dependencies for React and Chakra UI:

npm install

npm run dev

The React frontend will be running on http://localhost:3000.


# Notes

The project currently does not include advanced authentication features. You can expand it by adding login functionality with authentication tokens or social logins.

The frontend is mobile-friendly, but it can be enhanced further with more complex layouts or additional features.
