# 👋 Ravi Mishra

### Senior Cloud & DevOps Engineer

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=18&duration=2200&pause=700&color=00C7FF&center=true&vCenter=true&width=850&lines=Senior+Cloud+%26+DevOps+Engineer;AWS+Cloud+Architecture;Terraform+%7C+CloudFormation+%7C+Ansible;Kubernetes+%7C+ECS+%7C+Docker;CI%2FCD+%7C+Jenkins+%7C+GitHub+Actions;Cloud+Security+%7C+Observability;On-Premises+to+AWS+Migration;GenAI+%7C+Amazon+Bedrock" />
</p>

<p align="center">
  <a href="https://linkedin.com/in/mravi012">
    LinkedIn
  </a>
  &nbsp; · &nbsp;
  <a href="mailto:ravirmishra2995898@gmail.com">
    Email
  </a>
</p>

---

## 01 — About

I'm a **Senior Cloud & DevOps Engineer with 4.4+ years of experience**
building, automating, securing, and operating AWS infrastructure across
**20+ AWS accounts**.

I work across the full cloud infrastructure lifecycle — from architecture
and Infrastructure as Code to CI/CD, security, observability, migration,
incident response, and cost optimization.

My focus is simple:

> **Build reliable infrastructure. Automate the repetitive. Secure by
> design. Keep production stable.**

Based in **Noida, India**.

---

## 02 — Engineering Impact

<p align="center">

| 4.4+ | 20+ | 99.9% | 25% |
|:---:|:---:|:---:|:---:|
| Years Experience | AWS Accounts | Production SLA | Cloud Cost Reduction |

</p>

<p align="center">

| 200+ | 50+ | 35% | 0 |
|:---:|:---:|:---:|:---:|
| Nodes Managed | EC2 in ECS Infra | Migration Cost Reduction | Critical Vulnerabilities |

</p>

---

## 03 — Technologies

<p align="center">
  <img src="https://skillicons.dev/icons?i=aws,terraform,kubernetes,docker,jenkins,githubactions,python,bash,linux,ansible,prometheus,grafana,mysql,mongodb,git,github" />
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=17&duration=1800&pause=500&color=888888&center=true&vCenter=true&width=900&lines=AWS+%C2%B7+EC2+%C2%B7+S3+%C2%B7+RDS+%C2%B7+VPC+%C2%B7+IAM;ECS+%C2%B7+EKS+%C2%B7+Lambda+%C2%B7+CloudFront+%C2%B7+WAF;Terraform+%C2%B7+CloudFormation+%C2%B7+Ansible;Jenkins+%C2%B7+GitHub+Actions+%C2%B7+CodePipeline;Kubernetes+%C2%B7+Docker+%C2%B7+Amazon+ECS;CloudWatch+%C2%B7+Datadog+%C2%B7+Prometheus+%C2%B7+ELK;Security+Hub+%C2%B7+Inspector+%C2%B7+IAM+%C2%B7+CloudTrail;Python+%C2%B7+Bash+%C2%B7+Shell+Scripting;Amazon+Bedrock+%C2%B7+GenAI+%C2%B7+Agentic+AI" />
</p>

### Cloud

`AWS` `EC2` `S3` `RDS` `VPC` `IAM` `Lambda` `ECS` `EKS`
`CloudFront` `WAF` `Security Hub` `SageMaker` `Systems Manager`
`Direct Connect` `VPN` `CloudTrail` `Secrets Manager`

### Infrastructure

`Terraform` `CloudFormation` `Ansible`

### Containers

`Docker` `Kubernetes` `Amazon ECS`

### CI/CD

`Jenkins` `GitHub Actions` `AWS CodePipeline`

### Observability

`CloudWatch` `Datadog` `Prometheus` `ELK Stack`

### Security

`Security Hub` `Amazon Inspector` `IAM` `SCPs`
`Permission Boundaries` `NACLs` `Security Groups` `WAF`

### AI

`Amazon Bedrock` `AWS DevOps Agent` `Claude`
`Agentic AI Workflows`

### Scripting

`Python` `Bash` `Shell Scripting`

---

# 04 — Experience

## Senior Cloud Engineer — Cloud & DevOps

### VVDN Technologies
**June 2022 — Present · Noida, India**

I own and operate cloud infrastructure across **20+ AWS accounts**, applying
AWS Well-Architected principles to maintain highly available production
environments.

### What I work on

- Own AWS infrastructure across **20+ accounts**
- Maintain **99.9% production SLA**
- Lead Amazon Linux 2 → **Amazon Linux 2023** migrations
- Achieved migration with **zero service disruption**
- Reduced cloud spend by **25%**
- Resolve AWS Security Hub and Inspector findings
- Build CloudWatch dashboards and SLO-based alerts
- Configure VPC Peering and Transit Gateway
- Manage NACLs and Security Groups
- Implement IAM roles, Permission Boundaries and SCPs
- Manage EBS volumes, snapshots and EFS
- Act as primary escalation point for critical production incidents
- Perform RCA and coordinate production recovery
- Manage patching and vulnerability remediation across **200+ nodes**
- Provide on-call production support and client communication

---

# 05 — Selected Work

## Scalable Multi-Account Cloud Infrastructure

**AWS · EC2 · ECS · Kubernetes · ALB · CloudWatch · RabbitMQ**

Built and managed scalable workloads across multiple AWS environments.

### Highlights

- Managed ECS workloads across **50+ EC2 instances**
- Implemented multi-AZ architecture
- Configured Auto Scaling and ALB
- Built multi-branch Jenkins pipelines
- Automated testing and security scanning
- Implemented **Blue-Green deployments**
- Implemented **Canary releases**
- Implemented **Rolling deployments**
- Built CloudWatch dashboards and proactive alerts
- Managed AWS Glue crawlers, data catalogs and ETL jobs

---

## On-Premises → AWS Cloud Migration

**AWS · Terraform · ECS · Microservices · MGN · DMS · DataSync**

Migrated on-premises applications and databases to AWS using a
combination of rehost and replatform strategies.

### Architecture

```text
             ON-PREMISES
                  │
        ┌─────────┼─────────┐
        │         │         │
       MGN       DMS     DataSync
        │         │         │
     Servers   Database   Storage
        │         │         │
        └─────────┼─────────┘
                  │
                  ▼
             AWS CLOUD
                  │
          ┌───────┴───────┐
          │               │
         ECS             RDS
          │               │
          └───────┬───────┘
                  ▼
             Production
