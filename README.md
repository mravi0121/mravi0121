# 👋 Hi, I'm Ravi Mishra

### Senior Cloud & DevOps Engineer | AWS | Terraform | Kubernetes | CI/CD

<p align="left">
  <img src="https://img.shields.io/badge/AWS-Cloud-orange?style=flat-square&logo=amazonaws" />
  <img src="https://img.shields.io/badge/Terraform-IaC-7B42BC?style=flat-square&logo=terraform" />
  <img src="https://img.shields.io/badge/Kubernetes-Orchestration-326CE5?style=flat-square&logo=kubernetes" />
  <img src="https://img.shields.io/badge/Jenkins-CI%2FCD-D24939?style=flat-square&logo=jenkins" />
  <img src="https://img.shields.io/badge/Docker-Containers-2496ED?style=flat-square&logo=docker" />
  <img src="https://img.shields.io/badge/Python-Automation-3776AB?style=flat-square&logo=python" />
</p>

> **Building reliable cloud infrastructure, automating everything possible, and keeping production stable at scale.**

---

## 🧑‍💻 About Me

I'm a **Senior Cloud & DevOps Engineer with 4.4+ years of experience** designing, automating, securing, and operating AWS infrastructure across **20+ AWS accounts**.

My work focuses on:

- ☁️ AWS Cloud Architecture & Multi-Account Infrastructure
- 🏗️ Infrastructure as Code with Terraform & CloudFormation
- 🚀 CI/CD automation with Jenkins & GitHub Actions
- ☸️ Kubernetes & Amazon ECS workloads
- 🔐 Cloud security, vulnerability remediation & least-privilege access
- 📊 Monitoring, observability & SLO-based alerting
- 🔄 On-Premises → AWS migrations
- 💰 Cloud cost optimization
- 🤖 GenAI & agentic workflows using Amazon Bedrock

I follow the **AWS Well-Architected Framework** and focus on building infrastructure that is scalable, secure, observable, and reproducible.

---

## 📈 Engineering Impact

| Area | Impact |
|------|--------|
| ☁️ AWS Infrastructure | **20+ AWS Accounts** |
| 🖥️ Production Infrastructure | **200+ Nodes** |
| 🎯 Production SLA | **99.9%** |
| 💰 Cloud Cost Optimization | **25% Reduction** |
| 🏗️ ECS Infrastructure | **50+ EC2 Instances** |
| 🔐 Security | **Critical-vulnerability-free state** |
| 🔄 Linux Migration | **AL2 → AL2023 with zero service disruption** |

---

## 🛠️ Tech Stack

### ☁️ Cloud

`AWS` `EC2` `S3` `RDS` `VPC` `IAM` `Lambda` `ECS` `EKS`  
`CloudFront` `WAF` `Security Hub` `SageMaker` `Systems Manager`  
`Direct Connect` `VPN` `CloudTrail` `AWS Secrets Manager`

### 🏗️ Infrastructure as Code

`Terraform` `CloudFormation` `Ansible`

### 🐳 Containers & Orchestration

`Docker` `Kubernetes` `Amazon ECS`

### 🚀 CI/CD & Automation

`Jenkins` `GitHub Actions` `AWS CodePipeline`

### 📊 Monitoring & Observability

`Amazon CloudWatch` `Datadog` `Prometheus` `ELK Stack`

### 🔐 Security

`AWS Security Hub` `Amazon Inspector` `IAM`  
`Permission Boundaries` `SCPs` `NACLs` `Security Groups` `WAF`

### 🤖 AI / GenAI

`Amazon Bedrock` `AWS DevOps Agent` `Claude` `Agentic AI Workflows`

### 💻 Programming & Scripting

`Python` `Bash` `Shell Scripting`

### 🗄️ Databases

`MySQL` `MongoDB` `Amazon DocumentDB`

### 🔧 Tools

`Git` `GitHub` `Jira` `Agile/Scrum`

---

# 🚀 Featured Projects

## ☁️ Scalable Multi-Account Cloud Infrastructure

**AWS • EC2 • ECS • Kubernetes • ALB • CloudWatch • RabbitMQ**

Designed and managed scalable AWS workloads across multiple environments.

### Key Contributions

- Managed ECS workloads across **50+ EC2 instances**
- Implemented **multi-AZ architecture**
- Configured **Auto Scaling & Application Load Balancers**
- Built and maintained multi-branch **Jenkins CI/CD pipelines**
- Integrated automated testing and security scanning
- Implemented:
  - 🔵 Blue-Green deployments
  - 🟡 Canary releases
  - 🔄 Rolling deployments
- Built CloudWatch dashboards and proactive alerts
- Managed AWS Glue crawlers, data catalogs and ETL workloads

---

## 🔄 On-Premises → AWS Cloud Migration

**AWS • Terraform • ECS • Microservices • MGN • DMS • DataSync**

Worked on migrating on-premises applications and databases to AWS.

### Migration Architecture

```text
                 ON-PREMISES
                      │
                      ▼
             ┌─────────────────┐
             │ Migration Plan  │
             └────────┬────────┘
                      │
          ┌───────────┼───────────┐
          ▼           ▼           ▼
       AWS MGN      AWS DMS    DataSync
       Servers      Databases   Storage
          │           │           │
          └───────────┼───────────┘
                      ▼
                AWS Environment
                      │
             ┌────────┴────────┐
             ▼                 ▼
           ECS               RDS
             │                 │
             └────────┬────────┘
                      ▼
                 Production
