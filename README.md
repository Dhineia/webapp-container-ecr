🚀 CI/CD Deployment of a Containerized App to AWS Fargate
Project Overview:
Designed and implemented a CI/CD pipeline using GitHub Actions to automate the deployment of a Dockerized application to AWS Fargate, ensuring scalability and zero-downtime deployment.
Key Steps:
- CI/CD Setup: Created a docker-deploy.yml workflow file in GitHub Actions to automate the build and deployment process.
- Secrets Management: Stored sensitive credentials like IAM Access Key, Secret Key, Region, and ECR Repository as GitHub Secrets for secure access within the pipeline.
- Containerization & Deployment:
- Built and pushed the Docker image to Amazon ECR.
- Created an ECS cluster on Fargate for serverless deployment.
- Defined a Task Definition and launched it through an ECS Service.
- Application Access: Retrieved the Public IP Address of the running task to access the deployed application via browser.
Tools Used:
GitHub Actions · Docker · AWS ECS (Fargate) · ECR · IAM · GitHub Secrets

![Cluster](https://github.com/user-attachments/assets/d800c6e8-b191-417d-947a-55cf2aa33f7c)

![Services](https://github.com/user-attachments/assets/ff056852-c7f0-464f-81a3-fdbf6ef9fdef)

![Task](https://github.com/user-attachments/assets/1f94cb3d-86ba-4499-89e7-b719e619c5a1)

![Screenshot 2025-07-05 175518](https://github.com/user-attachments/assets/8f9831ad-ae41-4340-9311-a626d14c2b6d)
