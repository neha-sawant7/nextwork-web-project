# 🚀 Complete CI/CD Pipeline Using AWS DevOps Tools

This project demonstrates how to build a full CI/CD pipeline on AWS using native services such as CodeCommit, CodeBuild, CodeDeploy, and CodePipeline. The pipeline automates code integration, testing, and deployment onto an EC2 instance, simulating a production-ready DevOps environment.

---

## Here is the link of detailed project:
https://cicd-pipeline-usingaws-tools.hashnode.dev/complete-cicd-pipeline-using-aws-tools


## 📌 Project Overview

The goal of this project is to simulate an end-to-end CI/CD process for a Java-based web application using AWS cloud-native tools. It covers source control, build automation, deployment, and infrastructure configuration in a scalable and maintainable way.

---

## 🛠️ Technologies Used

- **AWS CodeCommit** – Source code repository
- **AWS CodeBuild** – Build and compile the application
- **AWS CodeDeploy** – Deployment to EC2 instance
- **AWS CodePipeline** – CI/CD automation
- **Amazon EC2** – Target environment for deployment
- **Amazon S3** – Artifact storage
- **CloudWatch Logs** – Monitoring build and deployment logs
- **IAM** – Role-based access control
- **Git** – Version control
- **Java (WAR File)** – Web application build

---

## 📂 Project Structure

.
├── appspec.yml
├── buildspec.yml
├── scripts/
│ ├── install_dependencies.sh
│ ├── start_server.sh
│ └── stop_server.sh
├── src/
│ └── [Java application files]
└── README.md



---

## 🔄 CI/CD Flow

1. **Code Commit:** Push source code to AWS CodeCommit
2. **Build Phase:** CodeBuild compiles Java source into a `.war` file and stores it in an S3 bucket
3. **Deploy Phase:** CodeDeploy deploys the artifact to a target EC2 instance using `appspec.yml`
4. **Lifecycle Hooks:** Shell scripts handle app stop/start and dependencies
5. **Monitoring:** CloudWatch captures build and deployment logs

---

## 📈 Learning Outcomes

- Hands-on experience with CI/CD pipelines on AWS
- Integrated build/test/deploy steps for automation
- Configured IAM roles and policies for least-privilege access
- Implemented lifecycle event scripts for deployment management
- Gained understanding of DevOps best practices in cloud environments

---

## 🙋‍♂️ Author
Neha Chandrakant Sawant
DevOps Engineer | AWS Enthusiast
LinkedIn: sawant-neha • GitHub: nehasawan
