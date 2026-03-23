# CBIT Online Academy - Web Programming Assignment 1

## Project Overview
[cite_start]This project is a multi-page static educational website developed for the **IV-Semester Assignment - I (Mar-2026)** at **Chaitanya Bharathi Institute of Technology (Autonomous)**[cite: 1, 2]. The platform allows users to explore courses, register for accounts, and submit inquiries to the institution.

## Live Deployment
[cite_start]The website is hosted via **GitHub Pages**[cite: 43].
**Live Site Link:** [https://bharathy2302.github.io/wpassignment164/](https://bharathy2302.github.io/wpassignment164/)

## Repository Structure
[cite_start]The project consists of the following essential files[cite: 37, 38, 39, 41, 42]:
* [cite_start]**index.html**: The Home page featuring a professional introduction and navigation menu[cite: 10].
* [cite_start]**courses.html**: A catalog listing all available courses with detailed "Amazon-style" info cards[cite: 11, 12].
* [cite_start]**register.html**: A user registration form including Name, Email, and Password fields[cite: 18].
* [cite_start]**contact.html**: A contact page providing the campus address, email, and an inquiry form[cite: 20].
* [cite_start]**style.css**: An external stylesheet managing the site's layout, colors, and hover effects using a **Grid System**[cite: 27, 30].
* [cite_start]**website_data.xml**: A centralized XML file storing the website's data (courses and services)[cite: 32].
* **website_data.xsd**: A schema file used to validate the XML structure for data integrity[cite: 33].

## Key Features
* **Navigation**: Functional menu for seamless movement between separate HTML pages[cite: 10].
* [cite_start]**JavaScript Validation**: The Registration and Login forms are validated via script to ensure password matching and data entry[cite: 19].
* [cite_start]**Interactive UI**: "Course Details" toggle functionality to reveal curriculum and duration on the Courses page[cite: 17].
* **Modern Styling**: Implementation of hover effects on buttons and links for enhanced user experience[cite: 29].

## XML and XSD Validation
This project utilizes a structured data approach by separating content from presentation[cite: 32, 33]:
1.  **XML Data Store**: All dynamic content like course titles, instructors, and contact details are managed in `website_data.xml`.
2.  **XSD Enforcement**: The `website_data.xsd` file acts as a validator, ensuring that all data entries follow strict rules (e.g., ensuring prices are numerical and ratings are within range).
3.  **Data Integrity**: This system prevents malformed data from affecting the website's structure, following professional software engineering standards.

---
**Course:** BE/BTech (CSE-3)  
**Subject:** Web Programming (WP) [cite: 2, 3]  
**Institution:** Chaitanya Bharathi Institute of Technology, Hyderabad [cite: 1]
