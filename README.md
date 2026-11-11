# NexPathSA – Career & Education Guidance Platform

## Overview

NexPathSA is an Android-based career and education guidance platform developed as a four-member university capstone project at Nelson Mandela University.

The application aims to help South African learners, matriculants, graduates and job seekers explore educational and career opportunities based on their individual circumstances, interests and goals.

It combines personalised recommendations, educational resources and opportunity discovery to make career and education planning more accessible.

## Key Features

- **Career Pathway Recommendations:** A rules-based recommendation engine that identifies potentially suitable career and study pathways.
- **Personalised Guidance:** Uses information such as education level, school subjects, qualifications, interests, goals and location.
- **Education and Opportunity Discovery:** Provides access to bursaries, study programmes and career opportunities.
- **Opportunity Management:** Supports saving and managing relevant opportunities and application information.
- **Subject Guidance:** Helps users explore educational pathways in relation to their school subjects.
- **User Accounts:** Supports different user categories, including students, graduates and matriculants/job seekers.
- **Cloud Synchronisation:** Uses Firebase services to support authentication and cloud-based data storage.
- **Preference-Based Recommendations:** Includes an on-device preference model to support more personalised recommendations.

## Technology Stack

| Technology | Purpose |
|---|---|
| Java | Android application development |
| XML | User interface layouts |
| Android Studio | Development environment |
| SQLite | Local database management |
| Firebase Authentication | User authentication |
| Firebase Firestore | Cloud database and synchronisation |
| Firebase Storage | Cloud file storage |

## Recommendation Engine

One of the core components of NexPathSA is its rules-based recommendation engine.

It evaluates information provided by users, including their educational background, school subjects, qualifications, interests and career goals, to identify potentially relevant study and career pathways.

The application also incorporates an on-device preference model to support personalised recommendations.

The goal is to make career and education guidance more relevant to the needs of South African learners and students.

## Database and Cloud Services

NexPathSA uses SQLite for local data storage, with database schema version 9.

Firebase services provide additional functionality:

- Firebase Authentication for account management.
- Cloud Firestore for cloud-based data storage and synchronisation.
- Firebase Storage for file storage.

The application also incorporates functionality relating to bursary and SAQA information.

## Project Context

NexPathSA was developed collaboratively by a team of four as part of our Bachelor of Information Technology capstone project at Nelson Mandela University.

The project involved applying software development, database management, system design and problem-solving principles to address a real-world challenge: helping young people navigate education and career opportunities.

This repository showcases the collaborative project and its implementation.

## Running the Project

1. Clone the repository.
2. Open the project in Android Studio.
3. Allow Android Studio to sync the Gradle dependencies.
4. Configure the required Firebase project settings.
5. Run the application using a compatible Android emulator or physical device.

**Note:** Additional Firebase configuration may be required to run the application. Local SDK configuration files are specific to individual development environments and are not included in the repository.

## Repository Structure

The `app` directory contains the Android application source code and related resources, including its database, recommendation logic and application components.

## Project Information

- **Project:** NexPathSA
- **Institution:** Nelson Mandela University
- **Qualification:** Bachelor of Information Technology
- **Project Type:** Academic Group Capstone Project
- **Team Size:** Four members
