# CI/CD Pipeline for HTML Portfolio

An automated CI/CD pipeline for a personal HTML/CSS portfolio using Git, GitHub, GitHub Actions, and GitHub Pages.

## 📌 Project Overview

This project demonstrates how a simple HTML/CSS portfolio can be managed and deployed using a CI/CD pipeline.

Whenever changes are pushed to the `main` branch, GitHub Actions automatically runs the workflow to validate the project and deploy the website.

## 🔄 CI/CD Workflow

```text
Developer
    ↓
Edit HTML / CSS
    ↓
Git Add
    ↓
Git Commit
    ↓
Git Push
    ↓
GitHub Repository
    ↓
GitHub Actions
    ↓
Build
    ↓
Test
    ↓
Deploy
    ↓
GitHub Pages
    ↓
Live Portfolio
🛠️ Technologies Used
HTML5
CSS3
Git
GitHub
GitHub Actions
GitHub Pages
⚙️ CI/CD Pipeline

The GitHub Actions workflow contains three stages:

1. Build

The build stage prepares the portfolio files for the deployment process.

2. Test

The test stage checks whether the required HTML and CSS files are available before deployment.

3. Deploy

The deploy stage automatically deploys the portfolio to GitHub Pages after the previous stages complete successfully.

If the test stage fails, the deployment stage will not run.

📂 Project Structure
resume-portfolio-cicd/
│
├── index.html
├── style.css
├── profile.jpg
├── README.md
│
└── .github/
    └── workflows/
        └── ci-cd.yml
🚀 How It Works
Make changes to index.html or style.css.
Test the changes locally in a web browser.
Add the changes using Git.
Commit the changes.
Push the changes to the main branch.
GitHub Actions automatically starts the CI/CD workflow.
The project is validated.
If the workflow succeeds, the portfolio is deployed to GitHub Pages.
💻 Run Locally

Clone the repository:

git clone https://github.com/Khushiyabegam/resume-portfolio-cicd.git

Go into the project directory:

cd resume-portfolio-cicd

Open index.html in a web browser.

📦 Git Workflow
git add .
git commit -m "Update portfolio"
git push

After pushing the changes, GitHub Actions automatically runs the CI/CD workflow.

🎯 Project Objectives
Learn Git and GitHub version control.
Understand CI/CD concepts.
Create an automated GitHub Actions workflow.
Automate website validation and deployment.
Deploy a static portfolio using GitHub Pages.