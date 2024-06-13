## Welcome to Cloud-Webapp-Shantanu!
 This organization hosts a comprehensive Cloud Native Web Application project, featuring three interconnected repositories.

## Project Overview

The Cloud Native Web Application project consists of three main components:
1. **Web Application**
2. **Serverless Infrastructure**
3. **Terraform Infrastructure as Code (IaC) for Google Cloud Platform (GCP)**

These components work together to provide a robust and seamless user experience, from user registration and authentication to infrastructure automation and serverless functions.

## Repositories

### 1. Web Application Repository
- **Repository Link:** [Web Application Repository](https://github.com/Cloud-Webapp-Shantanu/webapp)
- **Description:** 
  - Developed Node.js CRUD APIs for user registration and management.
  - Integrated with Sequelize ORM for efficient database management.
  - Enforced robust OAuth2 authentication to enhance the security of user interactions.
  - Automated CI/CD processes using GitHub Actions for image builds, template validation, integration tests, and code deployments.

### 2. Serverless Repository
- **Repository Link:** [Serverless Infrastructure Repository](https://github.com/Cloud-Webapp-Shantanu/serverless)
- **Description:**
  - Implemented serverless Cloud Functions triggered by Pub/Sub for sending verification emails to new users via Mailgun.
  - Utilized serverless architecture to ensure scalability and efficient resource usage.

### 3. Terraform Infrastructure as Code (IaC) for Google Cloud Platform (GCP) Repository
- **Repository Link:** [Terraform Iac Repository](https://github.com/Cloud-Webapp-Shantanu/tf-gcp-infra)
- **Description:**
  - Automated GCP infrastructure setup using Terraform.
  - Managed resources such as KMS, IAM, Cloud SQL, DNS, Logging, Autoscaling, and Load Balancing.
  - Employed Packer to create custom VM images containing necessary dependencies.

## Key Features and Technologies

- **Node.js**: Server-side JavaScript runtime for developing the web application.
- **Sequelize ORM**: Database ORM for managing complex queries and database interactions.
- **Packer**: Tool for creating machine images with all necessary dependencies pre-installed.
- **Terraform**: Infrastructure as Code (IaC) tool for automating cloud resource management.
- **GitHub Actions**: CI/CD tool for automating workflows, including testing and deployment.
- **Google Cloud Platform (GCP)**: Cloud provider offering scalable infrastructure and services.
- **Mailgun**: Email service for sending verification emails.
- **Serverless Functions**: Lightweight, event-driven functions for handling asynchronous tasks.

## License
All repositories in our organization are licensed under the [MIT License](LICENSE) unless otherwise specified.

![image](https://github.com/Cloud-Webapp-Shantanu/.github/assets/113257035/1418c48c-444a-4a1e-871b-7d663bfb3a79)

