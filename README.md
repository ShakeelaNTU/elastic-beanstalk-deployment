# elastic-beanstalk-deployment Assignment 2.8

Elastic Beanstalk - New Version Deployment

This document contains the CLI commands used to create a new version package bundle and deploy it to AWS Elastic Beanstalk.

Steps to Create and Deploy a New Version

1. Modify the Application Code

Updating the homepage text in app.py:

@app.route('/')
def home():
    return "<h1>Sample app in Development Environment by Shakeela after update</h1>"

2. Create a ZIP Package

After modifying the application, create a new ZIP package with the updated files.

zip -r app-v0.0.2.zip .

3. Upload the New Version to Elastic Beanstalk
