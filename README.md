
Lab 6 Exercise - Software Engineering (CS 415)

Overview
This repository contains our Lab 6 Exercise for CS 415: Software Engineering. The lab focuses on Git and GitHub workflows, including branching, merging, and collaborative development.

Project Description
The project is a basic static website that includes:

An index page (index.html) that serves as the homepage.

Personal members' pages contain things  (chika.html, daniel.html, dave.html, ewura.html) for each team member.

CSS files (index.css, chika.css, daniel.css, dave.css, ewura.css) to style individual pages.

Each team member created their own page and styled it using CSS before merging their changes into the main branch.

Repository Structure

📂 Lab-6-Exercise-SWE
 ├── README.md          # Project documentation
 ├── index.html         # Landing page with links to individual profiles
 ├── index.css          # General styling for the homepage
 ├── chika.html         # Chika's profile page
 ├── chika.css          # Chika's page styles
 ├── daniel.html        # Daniel's profile page
 ├── daniel.css         # Daniel's page styles
 ├── dave.html          # Dave's profile page
 ├── dave.css           # Dave's page styles
 ├── ewura.html         # Ewura's profile page
 ├── ewura.css          # Ewura's page styles
Git Workflow Followed

1. Clone the Repository

git clone https://github.com/AmannaP/Lab-6-Exercise-SWE.git
cd Lab-6-Exercise-SWE

2. Create and Switch to a New Feature Branch
git checkout -b feature-branch-name

3. Make Changes and Commit
git add .
git commit -m "Added my profile page"

4. Push Changes to GitHub
git push origin feature-branch-name

5. Create a Pull Request (PR)
Go to the repository on GitHub.

Navigate to Pull Requests → New Pull Request.

Select your branch and submit for review.

6. Merge the Pull Request
Once approved, merge the PR into main.

Delete the feature branch after merging.

Contributors
Chika

Daniel

Dave

Ewura

License
This project is for academic purposes under university guidelines.
