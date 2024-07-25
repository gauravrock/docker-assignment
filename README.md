# Docker Application Deployment

## Overview

This project involves deploying a simple web application using Docker containers. The application is a basic web server that returns "Hello, World!" when accessed.

## Steps Followed

1. **Developed a Simple Web Application:**
   - Created a Python Flask application to serve "Hello, World!" on the web.

2. **Created a Dockerfile:**
   - Used Python 3.9 slim as the base image.
   - Set up the working directory and copied the application files.
   - Installed Flask and exposed port 5000.

3. **Built the Docker Image:**
   - Executed `docker build` to create an image named `my-web-app` using cmd docker build -t my-web-app .

4. **Deployed the Application:**
   - Ran the container using `docker run` to map port 5500 to the host using cmd docker run -d -p 5500:5000 my-web-app

5. **Verified the Deployment:**
   - Accessed the application through a web browser at `http://localhost:5500`.

## App Functionality

The application is a simple HTTP server that responds with "Hello, World!" when the root URL is accessed.

## Author
- Name: Gaurav Sharma
- Roll Number: [G23AI2051]
