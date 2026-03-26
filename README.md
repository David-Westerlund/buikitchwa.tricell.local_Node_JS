# Backend Design

## Overview

This repository contains our implementation of a simple backend web application built using JavaScript and Node.js.

The project was developed as part of the university course "Backend Development" (5 ECTS) at Åland University of Applied Sciences. It builds upon the work from a previous course, "Frontend Development" (5 ECTS), where we created the frontend of the application. In this course, our focus was on developing the backend to support that frontend.

Throughout the project, we worked with core backend concepts such as routing, handling requests and responses, and connecting the application to a database. The application stores data in an MS Access database, as the course is designed for beginners who have not yet studied advanced database design.

The development was done in a Windows environment, and the final application is intended to be deployed on an IIS web server.

For learning purposes, the project uses the MD5 hashing algorithm for passwords. This was done intentionally to demonstrate security weaknesses and to help us understand why stronger hashing methods like bcrypt or Argon2 should be used in real-world applications.

Overall, this project represents our first experience building a full backend system and integrating it with an existing frontend.

---

## Project Structure

/config – Configuration files

/data – Data sources in various formats for exercises (JSON, XML, MDB)

/masterframe – Frontend HTML files

/public/css – Stylesheet files

/public/images – Layout images (GIF, JPG, PNG)

/public/photos – Personnel registry images

/public/scripts – Frontend JavaScript files

/routes – Route definitions (JavaScript)

/ – Main application files

---

## Installation

git clone https://github.com/David-Westerlund/buikitchwa.tricell.local_Node_JS.git

npm install

## Dependencies

- body-parser

- config

- cookie-parser

- express

- express-session

- formidable 2.0.1 (important, version must be correct)

- node-adodb

- nodemon

- pug

- xml2js

## Disclaimer

This example is intended for educational purposes only and should not be used in production environments.

Security mechanisms included in this project are deliberately simplified to support learning objectives.

## Author

David Westerlund, M.Eng, B.Sc

Higher Education IT Program

Course: Backend Development (5 ECTS)

IT Student

Åland Islands, Finland

david.westerlund@ha.ax

2026
