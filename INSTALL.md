# Installation Guide

This guide explains how to set up and run the Jenkins pipeline project.

## Prerequisites

- Docker
- Docker Compose
- Jenkins

## Steps to Run the Project

1. **Clone the Repository**

   ```sh
   git clone <https://github.com/DanorSODA/Jenkins-Pipeline-task>
   cd <Jenkins-Pipeline-task>
   ```

2. **Clone the `details-app` Repository**

   ```sh
   git clone https://github.com/zero-pytagoras/details-app
   ```

3. **Build and Start Jenkins Containers**

   Navigate to the `docker` directory and run:

   ```sh
   cd docker
   docker-compose up --build
   ```

4. **Access Jenkins**

   Open your browser and navigate to `http://localhost:8080`. Complete the Jenkins setup by following the prompts.

5. **Create and Configure Pipeline Job**

   - Create a new pipeline job in Jenkins.
   - Configure the pipeline job to use the `Jenkinsfile` located at the root of your project.

6. **Run the Pipeline**

   Trigger the build manually from Jenkins and monitor the pipeline execution.

## Docker Hub Credentials

Ensure that your Docker Hub credentials are set up correctly in Jenkins to allow pushing the Docker image.
