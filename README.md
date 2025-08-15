# Streamin 💧

As a fun summer project, I've decided to completely create a full stack video streaming platform called `Streamin`. The goal is to build a website where users can upload, share, and watch videos seamlessly. (Basically completely ripping off youtube)

As a fun bit, I'm going to make the website water/fluid based (Haha get it cause its called streaming). Anyways, this was inspired by learning about DASH in my computer networks course. I will be attempting to the best of my ability to follow proper software engineering protocols; all the way from requirements gathering up until CI/CD. If you think I made any mistakes, feel free to reach out to me.


# Table of Contents
1. [Introduction](#streamin-💧)
2. [Requirements Gathering](#requirements-gathering)
3. [Use Case Diagram](#use-case-diagram)
4. [Database Design](#database-design)
5. [Sequence Diagram](#sequence-diagram)
6. [System Architecture and Tech Stack](#system-architecture-and-tech-stack)
7. [UI/UX Prototype](#uiux-prototype)
8. [Implementation](#implementation)
9. [Testing and Quality Assurance](#testing-and-quality-assurance)
10. [Deployment and CI/CD](#deployment-and-cicd)
11. [Maintenance (maybe?)](#maintenance-maybe?)

## Requirements Gathering
### Functional Requirements
* Users should be able to create a new account by providing the necessary information.
* Users should be able to update their account details, such as contact information or password.
* (TENTATIVE) Users should be able to like, comment, and add videos towards a playlist
* Users should be able to upload videos with relative ease.
* Users should be able to see videos that were uploaded by other users as well as their own videos.
* The platform should showcase videos from different users 
* The system should provide appropriate error messages and handle exceptions gracefully.
* Only users who uploaded their videos and admins can delete videos.
* Admins must provide a reason for taking down videos (e.g vioaltion of local laws)
* Guest users or users who aren't authenticated can only view videos. 

### Non-Functional Requirements
* The system should be scalable to handle a large number of users. For now, we limit this number to 50.
* The system should be secure to protect user data and privacy. All sensitive details like passwords must be encrypted within the database.
* The system should provide a fast and responsive user experience.
* The platform should support adaptive bitrate streaming.
* The website should be able to be loaded fully in 5 seconds. 

