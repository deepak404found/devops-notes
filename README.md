# DevOps Journey

## Welcome to the DevOps Journey! 🌟

This repository is designed to provide a comprehensive guide to DevOps practices, tools, and technologies. Whether you're a beginner or an experienced professional, you'll find valuable resources to enhance your skills and knowledge in the DevOps domain.

## Table of Contents 📚

- DevOps Overview
  - [What is DevOps?](#what-is-devops-)
  - [Why DevOps?](#why-devops-)
  - [Key Areas of DevOps](#key-areas-of-devops-)
- Cloud Computing
  - [What is Cloud Computing?](#what-is-cloud-computing-)
  - [Key Benefits of Cloud Computing](#key-benefits-of-cloud-computing-)
  - [Cloud Computing Service Models](#cloud-computing-service-models-%EF%B8%8F)
  - [Cloud Deployment Models](#cloud-deployment-models-)
  - [Leading Cloud Providers](#leading-cloud-providers-)
  - [Most Commonly Used Cloud Services by category](#most-commonly-used-cloud-services-by-category-%EF%B8%8F)
  - [Cloud Deployment & Hosting Platforms (Vercel)](#cloud-deployment--hosting-platforms-)
- Docker
  - [What is Docker?](#what-is-docker-)
  - [Why Use Docker?](#why-use-docker-)
  - [Docker Architecture](#docker-architecture-%EF%B8%8F)
  - [Common Docker Commands](#common-docker-commands-)
  - [Docker Compose](#docker-compose-%EF%B8%8F)
  - [Dockerfile](#dockerfile-)
  - [Docker Volumes](#docker-volumes-)
  - [Docker Networking](#docker-networking-)
- CI/CD
  - [Continuous Integration (CI)](#continuous-integration-ci-)
  - [Continuous Deployment (CD)](#continuous-deployment-cd-)
  - [CI/CD Pipeline (Full Process)](#cicd-pipeline-full-process-)
  - [Popular CI/CD Tools](#popular-cicd-tools-%EF%B8%8F)
- AWS
  - [AWS Notes](https://github.com/deepak404found/devops-notes/blob/main/cloud_aws.md)

## What is DevOps? 🚀

DevOps is a set of practices that merge software development (Dev) and IT operations (Ops) to enhance collaboration, automate workflows, and improve the speed and reliability of software delivery. It focuses on continuous integration, continuous deployment (CI/CD), infrastructure as code (IaC), security, monitoring, and automation.

![devops-steps](https://github.com/deepak404found/devops-notes/raw/main/images/devOps-steps.png)

### Why DevOps? 🤔

DevOps aims to:

- Improve collaboration between development and operations teams.
- Automate repetitive tasks to increase efficiency.
- Enhance software reliability and reduce deployment failures.
- Enable faster releases with continuous delivery.

### Key Areas of DevOps 🔑

1. **CI/CD Pipelines**: Automates software building, testing, and deployment to ensure rapid and reliable releases.
2. **Infrastructure as Code (IaC)**: Manages infrastructure using code for consistency, scalability, and automation.
3. **Monitoring & Logging**: Helps track system performance and detect issues proactively.
4. **Security (DevSecOps)**: Integrates security practices into DevOps workflows to ensure secure applications and infrastructure.
5. **Cloud Providers ([AWS, Azure, GCP](#leading-cloud-providers-))**: Provide cloud-based infrastructure and services to enhance scalability and performance.

---

## 1. Cloud Computing ☁️

### What is Cloud Computing? 🚀

- Cloud Computing is the delivery of computing services such as servers, storage, databases, networking, software, and analytics over the internet (“the cloud”).
- It allows users to access and store data, run applications, and leverage IT resources on demand without owning physical infrastructure.
- Cloud computing offers scalability, flexibility, and cost efficiency, making it a key enabler for modern businesses and technologies.

![cloud-computing](https://github.com/deepak404found/devops-notes/raw/main/images/cloud-computing.png)

### Key Benefits of Cloud Computing 🌍

- **Scalability**: Easily scale resources up or down as needed.
- **Cost Efficiency**: Pay only for the resources you use, reducing capital expenditure.
- **Flexibility**: Access computing resources from anywhere.
- **Security**: Cloud providers implement strong security measures to protect data.
- **Disaster Recovery**: Cloud-based backups ensure quick recovery from failures.

---

### Cloud Computing Service Models 🛠️

Cloud services are typically categorized into three main models:

1. **Infrastructure as a Service (IaaS)** 🏠

   - Provides virtualized computing resources over the internet.
   - Examples: Amazon EC2, Google Compute Engine, Microsoft Azure VMs (see [Leading Cloud Providers](#leading-cloud-providers-)).

2. **Platform as a Service (PaaS)** 🛠️

   - Offers a platform for developing, running, and managing applications.
   - Examples: Google App Engine, AWS Elastic Beanstalk, Azure App Services (see [Leading Cloud Providers](#leading-cloud-providers-)).

3. **Software as a Service (SaaS)** 🖥️

   - Delivers software applications over the internet on a subscription basis.
   - Examples: Google Workspace, Dropbox, Salesforce.

### Cloud Deployment Models 🌐

1. **Public Cloud** – Services are offered to multiple customers over the internet.
2. **Private Cloud** – Resources are dedicated to a single organization.
3. **Hybrid Cloud** – A combination of public and private cloud solutions.
4. **Multi-Cloud** – Utilizing multiple cloud providers for different services.

---

### Leading Cloud Providers 🔥

Cloud computing has become a cornerstone of modern IT infrastructure, and several leading providers offer a wide range of services. Here are some of the most prominent cloud providers:

![Top Cloud Providers](https://raw.githubusercontent.com/deepak404found/devops-notes/main/images/top-cloud-providers.jpg)

- **Amazon Web Services (AWS)**
  - The largest and most widely adopted cloud platform, offering a vast array of services.
  - Includes IaaS, PaaS, and SaaS solutions.
  - Popular services: EC2, S3, Lambda, RDS, and more.
  - [Learn more about AWS](https://aws.amazon.com/)
  - [Documentation](https://docs.aws.amazon.com/)
- **Microsoft Azure**
  - A comprehensive cloud platform with a wide range of services.
  - Supports various programming languages and frameworks.
  - Popular services: Azure VMs, Azure Functions, Azure SQL Database, and more.
  - [Learn more about Azure](https://azure.microsoft.com/)
  - [Documentation](https://docs.microsoft.com/en-us/azure/)
- **Google Cloud Platform (GCP)**
  - A suite of cloud computing services that runs on the same infrastructure as Google’s end-user products.
  - Offers IaaS, PaaS, and serverless computing.
  - Popular services: Google Compute Engine, Google Kubernetes Engine, BigQuery, and more.
  - [Learn more about GCP](https://cloud.google.com/)
  - [Documentation](https://cloud.google.com/docs)
- **IBM Cloud**
  - Offers a range of cloud computing services, including IaaS, PaaS, and SaaS.
  - Focuses on enterprise solutions and hybrid cloud deployments.
  - Popular services: IBM Cloud Kubernetes Service, IBM Cloud Functions, and more.
  - [Learn more about IBM Cloud](https://www.ibm.com/cloud)
  - [Documentation](https://cloud.ibm.com/docs)
- **Oracle Cloud**
  - Provides a comprehensive suite of cloud services, including IaaS, PaaS, and SaaS.
  - Focuses on enterprise applications and databases.
  - Popular services: Oracle Cloud Infrastructure, Oracle Autonomous Database, and more.
  - [Learn more about Oracle Cloud](https://www.oracle.com/cloud/)
  - [Documentation](https://docs.oracle.com/en/cloud/)

---

### Most Commonly Used Cloud Services by category 🔧☁️

- **Virtual Machine** 🖥️ => AWS EC2, Google Compute Engine (GCE), Azure VMs
- **Serverless** ⚡ => AWS Lambda, Google Cloud Functions, Azure Functions, Vercel, Netlify
- **Load Balancer** ⚖️ => AWS ELB, Cloud Load Balancing, Nginx Proxy
- **Object Storage** 📦 => AWS S3, Google Cloud Storage, Minio, Cloudflare R2
- **Database Services** 🗄️ => Cloud SQL, Cassandra, MongoDB, etc.
- **Container Registry** 📥 => AWS ECR, Docker Hub, etc.
- **Container Service** 🐳 => AWS ECS, Google Cloud Run, Azure AKS
- **Kubernetes** ☸️ => AWS EKS, Google GKE, Azure AKS
- **Cache** ⚡ => AWS ElastiCache, Redis, Memorystore, Memcached
- **Content Delivery Network (CDN)** 🌍 => Amazon CloudFront, BunnyCDN
- **DNS Server** 🌐 => Cloudflare, Route 53, Google Cloud DNS, Azure Traffic Manager
- **Identity Management** 🔐 => AWS IAM, Google IAM, Azure Active Directory
- **Event Streaming & PubSub** 📡 => Kafka, RabbitMQ, Redis PubSub, etc.
- **Networking** 🔌 => AWS VPC, Google VPC, Azure VNET (those who hate life use Netmaker 😂)
- **Code Build** 🏗️ => AWS CodeBuild, Google Cloud Build, Azure Pipelines, Jenkins

---

### Cloud Deployment & Hosting Platforms 🌍

### **Vercel** 🚀

Vercel is a cloud platform for deploying and hosting frontend applications, particularly those built with frameworks like Next.js, React, Vue, and Angular. It offers seamless integration with GitHub, GitLab, and Bitbucket, enabling automatic deployments with every code push.

For more information, visit the [Vercel website](https://vercel.com/).

#### **Key Features of Vercel:**

- **Serverless Deployment**: Deploys applications without managing infrastructure.
- **Automatic Scaling**: Scales applications based on traffic.
- **Edge Functions**: Runs server-side logic closer to users for faster response times.
- **Instant Rollbacks**: Easily revert to a previous deployment if needed.
- **Preview Deployments**: Provides unique URLs for testing before going live.

---

## 2. Docker 🐳

### What is Docker? 🚢

Docker is an open-source platform that enables developers to automate the deployment, scaling, and management of applications using containerization. Containers encapsulate an application and its dependencies, ensuring consistency across different environments.

![docker-intro](https://github.com/deepak404found/devops-notes/raw/main/images/docker-intro.jpeg)

- Docker allows developers to package applications into containers, which can run on any system that has Docker installed. This eliminates the "it works on my machine" problem and simplifies the deployment process.
- Containers are lightweight, portable, and can be easily shared across different environments, making them ideal for microservices architectures and cloud-native applications.
- Docker provides a rich ecosystem of tools and services, including Docker Hub (a registry for sharing container images), Docker Compose (for defining multi-container applications), and Docker Swarm (for orchestrating containers).
- Docker is widely used in DevOps practices to streamline the development and deployment process, enabling continuous integration and continuous delivery (CI/CD) pipelines.

For more information, visit the [Docker website](https://www.docker.com/).

### Why Use Docker? 🤔

- **Portability**: Run the same application on different environments without modifications.
- **Isolation**: Ensures that applications run in separate containers without conflicts.
- **Efficiency**: Containers are lightweight compared to virtual machines (VMs).
- **Scalability**: Easily scale applications with container orchestration tools.

### Docker Architecture 🏗️

Docker consists of the following components:

- **Docker Engine**: The core of Docker, responsible for running containers.
- **Docker Image**: A lightweight, stand-alone package containing everything needed to run an application.
- **Docker Container**: A running instance of a Docker image.
- **Docker Hub**: A cloud-based registry for sharing container images.
- **Docker Compose**: A tool for defining and running multi-container applications.
  
### Common Docker Commands 💻

```sh
# Check Docker version
docker --version

# Pull an image from Docker Hub
docker pull nginx

# Run a container
docker run -d -p 80:80 nginx

# List running containers
docker ps

# Stop a running container
docker stop <container_id>

# Remove a container
docker rm <container_id>

# Remove an image
docker rmi <image_id>
```

---

### Docker Compose 🏗️

Docker Compose allows you to define multi-container applications using a YAML file.

Example `docker-compose.yml` file:

```yaml
version: '3'
services:
  web:
    image: nginx
    ports:
      - "80:80"
```

To start the application, run:

```sh
docker-compose up -d
```

To stop the application, run:

```sh
docker-compose down
```

---

### Dockerfile 📜

A Dockerfile is a text file that contains instructions for building a Docker image. Here's a simple example:

```dockerfile
# Use the official Node.js image

FROM node:14

# Set the working directory
WORKDIR /app

# Copy package.json and install dependencies
COPY package.json .

RUN npm install

# Copy the rest of the application code
COPY . .

# Expose the application port
EXPOSE 3000

# Start the application
CMD ["npm", "start"]
```

### Build the Docker image

```sh
docker build -t my-node-app .
```

### Run the Docker container

```sh
docker run -d -p 3000:3000 my-node-app
```

---

### Docker Volumes 💾

Docker volumes are used to persist data generated by and used by Docker containers. They are stored outside the container filesystem, allowing data to persist even if the container is removed.

To create a volume:

```sh
docker volume create my-volume
```

To use a volume with a container:

```sh
docker run -d -v my-volume:/data my-node-app
```

---

### Docker Networking 🌐

Docker provides several networking options:

- **Bridge**: Default network mode; containers can communicate with each other.
- **Host**: Shares the host network stack.
- **Overlay**: Used in Docker Swarm for multi-host networking.

---

## 3. CI/CD 🔧

### Continuous Integration (CI) 🤖

Continuous Integration (CI) is a software development practice where developers frequently integrate their code changes into a shared repository. Each integration is verified by an automated build and testing process, allowing teams to detect and fix issues early in the development cycle.

🔹 CI Workflow:

1. Developers commit code changes to a shared repository (e.g., Git).
2. CI server (e.g., Jenkins, Travis CI) automatically triggers a build.
3. The build process compiles the code, runs tests, and generates artifacts.
4. If the build and tests pass, the code is merged into the main branch.
5. If the build or tests fail, developers are notified to fix the issues.
6. CI tools provide feedback on the build status, test results, and code quality.
7. Developers can review and address issues before deploying to production.
8. Once the code is stable, it can be deployed to production or staging environments.

---

### Continuous Deployment (CD) 🚀

Continuous Deployment (CD) is an extension of Continuous Integration that automates the deployment of code changes to production environments. It ensures that every code change that passes the CI process is automatically deployed to production, reducing the time between development and release.

🔹 CD Workflow:

1. CI process completes successfully, and code changes are merged into the main branch.
2. CD server (e.g., Jenkins, GitLab CI/CD) automatically triggers a deployment process.
3. The deployment process may include building Docker images, running tests, and deploying to staging or production environments.
4. Automated tests are run in the production environment to ensure the application is functioning correctly.
5. If all tests pass, the code is considered safe for production.
6. Monitoring tools (e.g., Prometheus, Grafana) track application performance and health.
7. If issues are detected, rollback mechanisms can revert to the previous stable version.
8. Continuous feedback loops provide insights into application performance and user experience.
9. Developers can monitor deployment status and receive notifications for any issues.
10. Continuous Deployment allows for rapid iterations and faster delivery of new features to users.

---

### CI/CD Pipeline (Full Process) 🔄

The following diagram represents a typical CI/CD pipeline:

![CI/CD Pipeline](https://github.com/deepak404found/devops-notes/blob/main/images/cicd-pipeline.png?raw=true)

### Explanation

1. **Code Development**: Developers push code changes to a version control system like GitHub.
2. **Static Code Analysis**: Tools analyze the code for errors and vulnerabilities.
3. **Build Triggers**: A CI tool like Jenkins detects the new changes and triggers the build process.
4. **Build Execution**: The CI system compiles the code and creates build artifacts.
5. **Testing**: Automated tests are executed to ensure the code functions correctly.
6. **Artifact Storage**: Build artifacts are stored in repositories like JFrog or Nexus.
7. **Deployment Preparation**: The application is packaged and prepared for deployment.
8. **Staging & Testing**: The application is deployed to a staging environment for further validation.
9. **Deployment Testing**: If all tests pass, the application proceeds to production.
10. **Continuous Deployment**: The final step where the application is deployed to the live environment.

This automated approach enhances efficiency, reduces manual errors, and accelerates software delivery cycles.

---

### Popular CI/CD Tools 🛠️

Several CI/CD tools are available to automate the software development process. Here are some of the most popular ones:

| Tool | Description |
|------|-------------|
| Jenkins | Open-source automation server for building, testing, and deploying applications. |
| GitLab CI/CD | Built-in CI/CD tool for GitLab repositories, providing seamless integration. |
| Travis CI | Continuous integration service for GitHub projects, automating builds and tests. |
| CircleCI | Cloud-based CI/CD platform that automates the software development process. |
| GitHub Actions | CI/CD feature integrated into GitHub, allowing automation of workflows. |
| Azure DevOps | Microsoft’s suite of development tools for CI/CD, project management, and collaboration. |
| AWS CodePipeline | Fully managed CI/CD service for automating application releases on AWS. |
| Google Cloud Build | Fully managed CI/CD service for building, testing, and deploying applications on GCP. |
| Bitbucket Pipelines | Integrated CI/CD service for Bitbucket repositories, automating builds and deployments. |
| Codeship | Cloud-based CI/CD platform for building, testing, and deploying applications. |

---

## Summary 📜

- This repository provides a comprehensive overview of DevOps practices, cloud computing, and Docker.
- It covers key concepts, benefits, and tools to help you on your DevOps journey.
- Feel free to explore the resources and contribute to the repository!
- For any questions or suggestions, please open an issue or submit a pull request.
- Happy learning! 🎉
