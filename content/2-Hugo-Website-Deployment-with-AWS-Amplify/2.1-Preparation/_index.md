+++
title = "Preparation"
date = 2025
weight = 1
chapter = false
pre = "<b>2.1. </b>"
+++

### Prerequisites

* An AWS account with access to AWS Amplify

* A GitHub account

* Hugo and Git installed locally

  * [Hugo Theme](https://gohugo.io/)

  * [Git](https://git-scm.com/downloads)

* A code editor (e.g., VS Code)

  * [Visual Studio Code](https://code.visualstudio.com/download)

### Project Setup

* Use an existing Hugo project or create a new one if necessary.

* Ensure the project has a valid structure, including a public directory to contain the build output.

* Push the entire source code to a GitHub repository (on the main or master branch).

### Push to GitHub

* Create a new repository on GitHub

* Initialize Git and push your Hugo project to GitHub:

        git init
        git remote add origin https://github.com/<your-username>/<your-repo>.git
        git add .
        git commit -m "Initial commit"
        git push -u origin main