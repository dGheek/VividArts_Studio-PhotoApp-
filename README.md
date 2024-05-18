# VividArts
Name: Chijioke Edeh
Group: Faith Group
Project: VividArts Capstone Project 2
CE2 - Azubi Africa

## Introduction
VividArts is a web applications built to showcase and manage images, 
its a platform that enable its users to upload images which are processed, stored and displayed dynamically

## Technologies Used 
## Frontend 
The frontend of VividArts is responsible for providing a user-friendly interface for uploading and viewing images 

* HTML files structure the layout of the pages 

* CSS is used for styling elements and ensuring a visually pleasing user experince 

* JavaScript adds interactivity. such as form validation and dynamic content loading 


## Backend 
* Flask is used to handle server-side logic and manage routes
* Nodejs is used to handle image processing and the server-side logic
* AWS services for cloud infrastructure 

## Cloud Infrastructure
* AWS services are utilized to provide a scalable and reliable cloud environmant 

* Terraform is used for insfrastructure as Code to provision AWS Resources effectively 

* EC2 instances are deployed to host the flask application, managed through Terraform 

* S3 buckets store uploaded Images and serve as the primary storage solution 

* Lambda functuons are used for image processing, such resizing, triggerd by image uploads 

## DevOps
GitHub actions automaates the deployment process by building and deploying Docker images to docker hub



## Functionality
The Project utilizies HTML, CSS and JavaScript for the frontend, Flask for the backend, Nodejs for handling image processing, and AWS services for cloud infrastructure.
Docker is used to containerize the Flask application, ensuring consistency across different environment 
Once deployed, an EC2 instance runs a user data bash script to pull the Docker image from Docker Hub and launch the flask application

## Image Display
Users can view uploaded images in a gallery section of the VividArts application
The frontend requests images from the backend, which retrieves them from S3 and serves them to the client 

## Deployment Process
The team pushes code changes to the GitHub repository
GitHub Actions automatically builds and deploys a Docker image of the Flask Application to Docker Hub
Terraform provisions AWS resources, including EC2 instances, S3 buckets, Lambda functions
Once an EC2 instance is created, a user data bash script pulls the Docker image from Docker Hub and launches the Flask apliaction

## Project Deployment On AWS
# AWS Instance
EC2 instances was deployed to host the flask application
![AWS Inatnce](https://github.com/dGheek/VividArts_Studio-PhotoApp-/raw/main/instance.png)

# Lambda Funtion
Lambda functuons in this project was used for image processing, such as image resizing
![AWS Lambda Function](https://github.com/dGheek/VividArts_Studio-PhotoApp-/raw/main/lambda_code.png)

# AWS S3 Buckets
the two s3 bucket was created to store the before and after image of the app, the lambda function is triggered.
![AWS S3 Bucket](https://github.com/dGheek/VividArts_Studio-PhotoApp-/raw/main/s3.png)

## Project Demo


# Conclution 
VividArts is a comprehensive web appliaction that leverages modern technologies and cloud infrastructure to provide uses with a seamless experience for uploading, processing, and viewing images 
By utilizing HTML, CSS, JavaScipt, Flask, AWS, Terraform, Docker,  and GitHub Actions, the project demonstrates efficient development practices and scalability in deployment.


