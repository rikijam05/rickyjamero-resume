Interactive Resume: Ricky G. Jamero
This repository hosts an interactive, single-page web application serving as Ricky G. Jamero's professional resume and portfolio. It is designed to be easily explorable and consumable by recruiters and hiring managers.

Project Overview
This interactive resume transforms a traditional resume into a dynamic web experience. It features:

An interactive career timeline to explore professional history.

A filterable technical skills explorer to showcase expertise across various domains.

A dedicated section for featured projects and achievements.

A clean, professional, and fully responsive UI/UX design.

Technologies Used
HTML5: For the core structure of the web page.

Tailwind CSS: A utility-first CSS framework for rapid and responsive styling.

Vanilla JavaScript: For all interactive elements, data handling, and dynamic content updates.

Chart.js: A JavaScript charting library for data visualization (though currently not in use, it's part of the base setup).

Setup and Deployment Guide
This guide outlines the steps to set up this project locally using Visual Studio Code and deploy it to GitHub Pages.

I. Essential Software & Accounts
Visual Studio Code (VS Code):

A free, powerful code editor.

Download: https://code.visualstudio.com/

Git:

The version control system.

Download: https://git-scm.com/downloads

Crucial during installation: Select "Use Git from the command line and also from 3rd-party software" to add Git to your system's PATH.

GitHub Account:

For hosting your code and deploying your website via GitHub Pages.

Sign Up/Login: https://github.com/

Personal Access Token (PAT): Essential for pushing code to GitHub via HTTPS. Generate from GitHub Settings > Developer settings > Personal access tokens (classic) with repo scope.

II. Recommended VS Code Extensions
These extensions enhance your web development workflow in VS Code:

Live Server: Launches a local development server with live reload.

Purpose: See changes instantly in your browser as you save.

Prettier - Code formatter: Automatically formats your code for consistency.

Purpose: Keeps your HTML, CSS, and JS clean and readable.

Tailwind CSS IntelliSense: Provides auto-completion, syntax highlighting, and linting for Tailwind CSS classes.

Purpose: Speeds up Tailwind CSS development.

III. Step-by-Step Project Setup & Deployment
Local Project Folder Creation:

Create a new, empty folder on your computer (e.g., C:\Users\YourUser\Desktop\Dadi\Git\rickyjamero-resume).

Ensure this folder is truly empty and does not contain any hidden .git folders.

Save the HTML File (index.html):

Copy the entire HTML code from the rickyjamero_resume_new_vscode_start Canvas.

Save this code as index.html directly inside your new rickyjamero-resume folder.

Open Project in VS Code:

Launch VS Code and open the rickyjamero-resume folder (File > Open Folder...).

Initialize Git Locally (in VS Code Terminal):

Open the integrated terminal (Terminal > New Terminal).

Run:

git init
git branch -M main

Make Your First Commit (in VS Code Source Control):

Go to the Source Control view (sidebar icon).

Stage index.html (click + icon).

Type a commit message (e.g., "Initial commit: Interactive Resume").

Click the Commit button.

Create Empty Repository on GitHub:

Go to https://github.com/new (logged in as rikijam05).

Name it rickyjamero-resume.

Set to Public.

Leave ALL initialization checkboxes UNCHECKED (no README, .gitignore, etc.) to ensure it's truly empty.

Click "Create repository."

Connect Local Project to GitHub (in VS Code Terminal):

Copy the HTTPS URL of your newly created empty GitHub repository (e.g., https://github.com/rikijam05/rickyjamero-resume.git).

In your VS Code terminal, run:

git remote add origin https://github.com/rikijam05/rickyjamero-resume.git

Push Your Code to GitHub (from VS Code):

In VS Code's Source Control view, click the Publish Branch button (or Sync Changes).

If prompted for credentials, use your rikijam05 GitHub username and your PAT.

Enable GitHub Pages:

Go to your rickyjamero-resume repository on GitHub.

Navigate to Settings > Pages.

Under "Build and deployment" > "Source," select "Deploy from a branch."

For "Branch," select main and for "Folder," select / (root).

Click Save.

Access Your Live Resume:

After a few minutes, your site will be live at https://rikijam05.github.io/rickyjamero-resume/.