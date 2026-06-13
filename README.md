<div align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=JetBrains+Mono&size=26&duration=3000&color=00D4AA&center=true&vCenter=true&width=700&lines=Swan+Htet+Aung+Phyo;Go+Backend+%26+DevOps+Engineer;Distributed+Systems+%7C+Cloud+Infrastructure;Myanmar+%F0%9F%87%B2%F0%9F%87%B2+%E2%86%92+Poland+%F0%9F%87%B5%F0%9F%87%B1" alt="Typing SVG" />
</div>

<div align="center">
  <img src="https://komarev.com/ghpvc/?username=swanhtetaungphyo&label=Profile+views&color=00D4AA&style=for-the-badge" />
  <img src="https://img.shields.io/github/followers/swanhtetaungphyo?label=Followers&style=for-the-badge&color=00D4AA" />
  <img src="https://img.shields.io/github/stars/swanhtetaungphyo?label=Stars&style=for-the-badge&color=00D4AA" />
    <img src="https://wakatime.com/badge/github/SwanHtetAungPhyo/SwanHtetAungPhyo.svg" />
</div>

<br/>


## About

```yaml
name:        Swan Htet Aung Phyo
role:        Go Backend & DevOps Engineer
location:    Krakow, Poland
focus:       Distributed systems · Cloud infrastructure · gRPC · IaC
currently:   Go Backend / DevOps Engineer (Contractor)
open_to:     Backend collaboration · open source · contract work
timezone:    UTC+7
```

<br/>

## 🚀 Impact & Metrics

| Metric | Impact |
|--------|--------|
| **AWS Certified** | Solutions Architect Associate + Terraform Associate |
| **CI/CD Automation** | 85% reduction in manual deployments (Weekly → Daily) |
| **Multi-Region HA** | Route 53 failover, cross-region RDS, Auto Scaling across 2 regions |
| **Microservices** | 35% improvement in data transfer efficiency, 10,000+ daily interactions |
| **Security** | CloudTrail + Security Hub monitoring with live attack simulations |
| **IaC** | 8+ Terraform projects, custom IaC language (TBLang), reusable modules |
| **Open Source** | Contributing to Grafana Loki observability platform |

<br/>

## 💼 Experience highlights

- 🏗️ **Architected CI/CD pipelines** on AWS with GitHub Actions — reduced manual deployment by **85%**, shipped from weekly to daily
- 🔌 **Engineered gRPC microservices** improving data transfer efficiency by **35%** and supporting **10,000+ daily interactions**
- 🛠️ **Built TBLang** — a custom IaC language with full compiler pipeline (lexer, AST, semantic validation, AWS provider plugin)
- 📊 **Contributed to Grafana Loki** — open source observability tooling with production-grade telemetry
- 👥 **Mentored engineers** on DevOps best practices, microservice architecture, and gRPC patterns
- 🔐 **Developed KYC verification system** integrating AWS Textract & Rekognition with 70% similarity threshold and 90%+ confidence detection
- 🎙️ **Built voice analysis service** — Deepgram STT, 8-goroutine analysis pipeline, AWS Bedrock AI summaries, Lambda + API Gateway deployment
- 🌍 **Designed multi-region HA infrastructure** — Route 53 failover, cross-region RDS replication, Auto Scaling, CloudFront + WAF, all in Terraform

<br/>

## 🛠️ Tech stack

<div align="center">

**Languages**

![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)

**Backend & protocols**

![gRPC](https://img.shields.io/badge/gRPC-244C5A?style=for-the-badge&logo=grpc&logoColor=white)
![Gin](https://img.shields.io/badge/Gin-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![Fiber](https://img.shields.io/badge/Fiber-00ACD7?style=for-the-badge&logo=go&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Protocol Buffers](https://img.shields.io/badge/Protobuf-FF6D00?style=for-the-badge&logo=google&logoColor=white)

**Infrastructure & cloud**

![AWS](https://img.shields.io/badge/AWS-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=for-the-badge&logo=ansible&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

**Data**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)

</div>

<br/>

## 📌 Featured projects


---

### Multi-Region HA Infrastructure with Route 53 Failover
> Terraform · AWS · CloudFront · WAF · Route 53 · Auto Scaling · RDS

Production-grade multi-region setup across eu-central-1 and eu-north-1. Route 53 health-checked DNS failover, Auto Scaling groups behind ALBs in both regions, cross-region RDS read replicas, CloudFront with WAF (rate limiting, common rule sets), and static site delivery from S3 via OAI. Everything in Terraform with KMS encryption on all storage.

**AWS services used:** Route 53, CloudFront, WAF, ALB, Auto Scaling, EC2, RDS (cross-region replica), S3, KMS, ACM

---

### AWS Cloud Security Monitoring
> Terraform · AWS · CloudTrail · Security Hub · IAM · KMS

Full security monitoring stack. IAM lockdown with enforced MFA, multi-region CloudTrail encrypted with KMS, CloudTrail Lake with 10 SQL-based threat hunting queries, Security Hub running CIS and FSBP benchmarks, CloudWatch-to-SNS alerting pipeline. Deployed on a real AWS account, ran attack simulations, and verified detections end to end.

**AWS services used:** IAM, STS, CloudTrail, CloudTrail Lake, Security Hub, CloudWatch, SNS, KMS, S3

---

### TBLang — Infrastructure as Code Language
> Go · gRPC · Lexer/Parser · AWS SDK · Protocol Buffers

Custom IaC language with a full compiler pipeline (lexer, AST, semantic validation, code generation). AWS provider plugin handles VPC, EC2, and RDS provisioning. State management via `.tbstate` files. Published as a Homebrew tap with a VSCode syntax extension.

---

### AWS KYC Verification API
> Go · Fiber · AWS Textract · Rekognition · Docker

Takes an ID photo and a selfie, runs Textract for document validation, then Rekognition face comparison at a 70% similarity threshold. Returns pass/fail with confidence scores. Deployed as a Docker container.

**AWS services used:** Textract, Rekognition

---

### Terraform AWS Compute Network Module
> Terraform · AWS

Reusable module used across 3+ projects. VPC with multi-AZ public/private subnets, cost-effective NAT instances (not NAT Gateway), IMDSv2 enforcement, dynamic EC2 provisioning with per-instance security groups, encrypted EBS by default. Published to the Terraform registry.

**AWS services used:** VPC, EC2, EBS, IAM

---

### Cloud-Native Computer Use Agent
> Python · FastAPI · Docker Compose · PostgreSQL · Anthropic Claude API

Multi-session backend for browser-based task automation via Claude API. Async request handling, SSE streaming, stateless tool-proxy architecture for concurrent multi-user sessions.

<br/>

## 🏆 Open Source Contributions

- **Grafana Loki** — Contributing to production-grade observability and log aggregation platform
  - Focus: Distributed tracing, performance optimization
  - Impact: Used by thousands of organizations for log management

<br/>

## 📚 Blog & Insights

I regularly share technical deep-dives and best practices on:

[![Medium](https://img.shields.io/badge/Medium-12100E?style=for-the-badge&logo=medium&logoColor=white)](https://medium.com/@swanhtet102002)

Topics include: gRPC patterns, DevOps automation, infrastructure as code, microservice architecture, and cloud-native best practices.

<br/>

## 🎓 Certifications

- **AWS Solutions Architect – Associate (SAA-C03)** — Cloud architecture, high availability, cost optimization, security
- **HashiCorp Terraform Associate (003)** — Infrastructure automation & cloud provisioning
- **Introduction to Linux** — System administration fundamentals

<br/>

## 📊 GitHub analytics

<div align="center">
  <img height="180em" src="https://github-readme-stats.vercel.app/api?username=swanhtetaungphyo&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true&hide_border=true"/>
  <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=swanhtetaungphyo&layout=compact&langs_count=8&theme=tokyonight&hide_border=true"/>
</div>

<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=swanhtetaungphyo&theme=tokyonight&hide_border=true" />
</div>

<div align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=swanhtetaungphyo&theme=tokyo-night&hide_border=true" />
</div>

<br/>

## 🤝 Let's Connect

<div align="center">

[![Portfolio](https://img.shields.io/badge/Portfolio-00D4AA?style=for-the-badge&logo=globe&logoColor=white)](https://portfolio-swan-pi.vercel.app/)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:swanhtetaungp@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/swan-htet-aung-phyo-317912273)
[![Medium](https://img.shields.io/badge/Medium-12100E?style=for-the-badge&logo=medium&logoColor=white)](https://medium.com/@swanhtetaung102002)

</div>

---

<div align="center">
  <sub>⚠️ Previously: <a href="https://github.com/SwanHtetMorgan">SwanHtetMorgan</a></sub>
</div>
