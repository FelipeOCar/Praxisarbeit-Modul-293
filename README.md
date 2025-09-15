Overview

This repository showcases the culmination of my work in Module 293, focusing on the practical application of containerization technologies. It includes:

HTML/CSS/JavaScript: Core technologies for web development.

Containerization: Utilizing Docker to package and deploy applications.

Kubernetes: Orchestrating containerized applications for scalability and management.

Features

Responsive Web Design: Ensures compatibility across various devices.

Dockerized Environment: Simplifies deployment and consistency across development stages.

Kubernetes Integration: Demonstrates the use of Kubernetes for managing containerized applications.

Getting Started

Clone the repository:

git clone https://github.com/FelipeOCar/Praxisarbeit-Modul-293.git


Navigate into the project directory:

cd Praxisarbeit-Modul-293


Build the Docker image:

docker build -t praxisarbeit-modul-293 .


Run the application:

docker run -p 8080:80 praxisarbeit-modul-293
