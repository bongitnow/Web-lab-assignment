Resume & Biodata Web Application
This project is a simple, structured web application that allows users to view the Resume or Biodata of four individuals. The site is built using HTML, CSS, and JavaScript, with all information stored in a centralized data.js file. The goal is to present content directly on the website without redirecting to external PDF files.

Features
1. Home Interface
Users begin by selecting whether they want to view a Resume or a Biodata. This selection determines the type of information displayed later.

2. Person Selection Page
After choosing the content type, users are presented with four options:

Arnav Singh

Bhavana Hegde

Abhishek Saini

Chaithanya D S

Selecting a name loads the corresponding data dynamically.

3. Dynamic Content Rendering
The application uses JavaScript to extract and display the selected individual's Resume or Biodata from data.js. No server-side processing is required.

4. Structured Resume and Biodata Format
Each resume includes structured sections such as:

Summary or Objective

Contact Information

Education

Technical Skills

Projects

Achievements

Certifications (if available)

Each biodata contains:

Date of Birth

Address

Languages Known

Hobbies

5. Easy Navigation
All pages include a "Go Back" button to return to the previous step, allowing smooth navigation throughout the website.

File Structure
project/
│── index.html
│── select-person.html
│── display.html
│── data.js
│── style.css
└── assets/         (optional folder for images or icons)
Technologies Used
HTML5 for structure

CSS3 for styling and layout

JavaScript (Vanilla JS) for logic and data rendering

data.js for central data storage

This is a fully client-side application requiring no backend.

How the Website Works
Step 1: Landing Page
The user selects either "Resume" or "Biodata".

Step 2: Profile Selection
The user selects one of the four individuals.
The site remembers both the selected person and the selected type (resume or biodata).

Step 3: Display Page
The application fetches the corresponding information from data.js and displays it in a readable, organized structure.
All rendering happens within the browser.


Team Members
Arnav Singh

Bhavana Hegde

Abhishek Saini

Chaithanya D S

