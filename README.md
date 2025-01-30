# elastic-beanstalk-deployment Assignment 2.8

Elastic Beanstalk - New Version Deployment

Overview

This document contains the CLI commands used to create a new version package bundle and deploy it to AWS Elastic Beanstalk.

Steps to Create and Deploy a New Version

1️⃣ Modify the Application Code

Make necessary changes to your app.py file or any other relevant files in your application.

Example: Updating the homepage text in app.py:

@app.route('/')
def home():
    return "<h1>Sample app in Development Environment by MYNAME - Version 2</h1>"

2️⃣ Create a ZIP Package

After modifying the application, create a new ZIP package with the updated files.

zip -r app-v0.0.2.zip .

3️⃣ Upload the New Version to Elastic Beanstalk
