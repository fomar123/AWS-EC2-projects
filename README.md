# AWS-EC2-projects


# AWS & Jenkins Part 1 - Jenkins Pipeline to Deploy on AWS EC2

##### Demo 1 - Deploying WebApp Container via Jenkins Pipeline on EC2 Instance:
- Installed the SSH agent plugin on Jenkins to enable secure connections.
- Created SSH credentials in Jenkins to establish a connection to the EC2 instance.
- Configured the Jenkinsfile to utilise the sshAgent and execute a Docker run command on the EC2 instance.
- Ensured Docker login to DockerHub.
- Configured the security group on AWS, adding Jenkins IP address and opening the required port to access the web application.
- Successfully deployed the web application on an EC2 instance by executing a Multi-Branch Pipeline.
- Accessed the deployed web application in a browser using the specified port (e.g., 3080).

##### Demo 2 - Deploying Java Maven App via Jenkins Pipeline on EC2 Instance:
- Configured the Jenkinsfile to build and deploy a Java Maven application on an EC2 instance.
- Executed a Multi-Branch Pipeline on Jenkins to trigger the deployment process.

# AWS & Jenkins Part II - Deploy Using Docker Compose (Docker-Compose, ECR)

##### Demo - Deploying Java Maven App via Jenkins Pipeline on EC2 Instance using Docker-Compose File:
- Installed Docker-Compose on the EC2 instance, allowing for the management of multi-container Docker applications.
- Created a docker-compose.yaml file to define and configure the services required for the application.
- Configured the Jenkinsfile to execute the docker-compose command for deployment.
- Executed a Jenkins Pipeline to deploy the application to an AWS EC2 instance.

# AWS & Jenkins Part III - Complete Pipeline (Docker-Compose, ECR, Dynamic Versioning)

##### Demo - Complete Pipeline with Dynamic Versioning:
- Adjusted the Jenkinsfile to include dynamic versioning for the application.
- Executed a Jenkins Pipeline that deploys the application to an AWS EC2 instance, incorporating the dynamic versioning approach.
