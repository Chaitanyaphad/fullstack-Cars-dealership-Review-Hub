# Fullstack Cars Dealership Review Hub
This is final capstone project in the Coursera IBM FullStack Software Developer specialization course 
Welcome to the **Best Cars Dealership Review Platform**, a web application that provides a centralized database of dealership reviews across the United States. This platform allows users to explore car dealerships, read reviews, and post their own reviews, all while leveraging modern cloud-based microservices.

## Table of Contents
- [Project Overview](#project-overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
- [Architecture](#architecture)
  
## Project Overview

This project is a full-stack web application designed for **Best Cars Dealership**, a national car dealership with branches all over the US. The platform enables users to:
- View dealership details and reviews.
- Post their own reviews after logging in.
- Filter dealerships by state.
- Analyze review sentiments.

The platform is built with microservices architecture and follows modern development practices, including CI/CD pipelines, containerization, and serverless deployment.

## Features

- **Homepage**: Introduction to the dealership, links to static pages like *About Us* and *Contact Us*.
- **User Authentication**: User registration and login functionality using Django.
- **Dealership Listings**: View dealerships with the option to filter by state.
- **Reviews**: Logged-in users can post reviews for dealerships.
- **Sentiment Analysis**: Analyzes the sentiment of reviews using a Flask microservice.
  
## Technologies Used

### Frontend:
- **HTML, CSS, Bootstrap**: For static pages like the homepage, About Us, and Contact Us pages.
- **React**: For dynamic components such as login, registration, and review posting.

### Backend:
- **Python, Django, SQLite**: Main backend for user management and end-user views.
- **Python, Flask, NLTK**: Sentiment analysis microservice for review analysis.
- **Node.js, Express, MongoDB**: Service for managing dealership details and reviews.

### DevOps & Cloud:
- **Git, GitHub, GitHub Actions**: Version control and CI/CD pipelines.
- **Docker, Kubernetes**: Containerization and orchestration of services.
- **IBM Cloud Code Engine**: Serverless deployment of microservices.

## Architecture

This project follows a microservices architecture, with the following components:

1. **Frontend Service**: React-based frontend for user interaction.
2. **User Management Service**: Django backend for handling user authentication and management.
3. **Dealership and Review Service**: Node.js and MongoDB service to manage dealerships and reviews.
4. **Sentiment Analysis Service**: Flask microservice that performs sentiment analysis on reviews using NLTK.
