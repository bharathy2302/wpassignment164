CBIT Online Academy - Web Programming Assignment 1
Project Overview
This project is a multi-page static educational website developed as part of the IV-Semester Assignment - I (Mar-2026) at Chaitanya Bharathi Institute of Technology (Autonomous). The platform provides a simulated environment for students to browse courses, register for accounts, and contact administration.

Repository Contents
index.html: Home page with a professional banner and website introduction.

courses.html: A grid-based course listing featuring "Amazon-style" interactive cards.

register.html: A membership form that includes real-time JavaScript validation.

contact.html: A dedicated page for campus address, phone, and inquiry forms.

style.css: A centralized CSS file utilizing Grid Systems and custom hover effects.

website_data.xml: A global XML database containing all site-wide content.

website_data.xsd: A schema file used to strictly validate the XML structure.

Technical Implementation
Separation of Concerns: The website is split into 4 distinct HTML pages for better navigation.

Form Validation: The registration form uses JavaScript to ensure the "Password" and "Confirm Password" fields match before submission.

Interactive UI: Course cards in courses.html use JavaScript to toggle short descriptions and curriculum details when clicked.

Visuals: Modern styling with a colorful palette, using external images and local assets.

XML Data & XSD Validation
This project incorporates an XML/XSD layer to manage website data.

The XML file acts as a lightweight data store for course titles, prices, and contact details.

The XSD file ensures data integrity by defining specific rules (e.g., prices must be integers, and ratings must be decimals).

This follows industry best practices for separating website content from the structural code.


Deployment
The website is live and hosted via GitHub Pages.
Live Site Link: 
