<h1 align="center">Hi, I'm Dipon Kumer Sarker 👋</h1>

<p align="center">
  <b>DevOps Engineer</b> · Kubernetes · Cloud Infrastructure · CI/CD · Observability<br/>
  📍 Dhaka, Bangladesh
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/dipon778"><img src="https://img.shields.io/badge/LinkedIn-dipon778-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:dipon778@gmail.com"><img src="https://img.shields.io/badge/Email-dipon778@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
  <a href="https://dipon778.github.io/just-a-piano/"><img src="https://img.shields.io/badge/🎹_Play_a_piano-just--a--piano-222222?style=for-the-badge" alt="Piano"/></a>
</p>

---

```yaml
apiVersion: people/v1
kind: DevOpsEngineer
metadata:
  name: dipon-kumer-sarker
  location: Dhaka, Bangladesh
spec:
  experience: 5y
  clouds: [aws, gcp]
  replicas: 1   # but I mentor, so the platform scales anyway
  owns:
    - kubernetes platforms (EKS, GKE, self-managed)
    - infrastructure as code (Terraform, Ansible, Helm)
    - ci/cd (GitHub Actions, GitLab CI, Jenkins)
    - observability (Prometheus, Grafana, ELK, Dynatrace)
  alerting: symptom-based   # page on user pain, not on noise
  onCall: true
status:
  phase: Running
  currentFocus: platform standardization that reduces toil for product teams
```

## 🚀 About Me

I build and run cloud infrastructure and internal developer tooling on **AWS** and **GCP**. I own Kubernetes and Docker platforms end-to-end — from Terraform and Ansible, through CI/CD pipelines, to the dashboards and alerts that tell us something is wrong *before* users notice.

- 🏗️ I lead platform work from architecture through rollout
- 🧑‍🏫 I mentor engineers on pipeline and operational best practices
- 🚨 I'm comfortable owning on-call and incident response
- 🗣️ I explain infrastructure clearly to technical and non-technical people alike

## 🔁 How I Ship

```mermaid
flowchart LR
    A[git push] --> B[CI<br/>GitHub Actions · GitLab CI · Jenkins]
    B --> C[Scan<br/>image & dependency gates]
    C --> D[Registry<br/>ECR · Artifact Registry]
    D --> E[Deploy<br/>Helm → EKS / GKE]
    E --> F[Observe<br/>Prometheus · Grafana · ELK · Dynatrace]
    F -. symptom-based alerts .-> G[On-call]
    T[Terraform + Ansible] -. provisions .-> E
```

## 🧰 Tech Stack

**Cloud**<br/>
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![Google Cloud](https://img.shields.io/badge/Google_Cloud-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![BigQuery](https://img.shields.io/badge/BigQuery-669DF6?style=flat-square&logo=googlebigquery&logoColor=white)

**Containers & Orchestration**<br/>
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Helm](https://img.shields.io/badge/Helm-0F1689?style=flat-square&logo=helm&logoColor=white)

**Infrastructure as Code**<br/>
![Terraform](https://img.shields.io/badge/Terraform-844FBA?style=flat-square&logo=terraform&logoColor=white)
![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=flat-square&logo=ansible&logoColor=white)

**CI/CD**<br/>
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![GitLab CI](https://img.shields.io/badge/GitLab_CI-FC6D26?style=flat-square&logo=gitlab&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=flat-square&logo=jenkins&logoColor=white)

**Observability**<br/>
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)
![Elastic Stack](https://img.shields.io/badge/ELK_Stack-005571?style=flat-square&logo=elasticstack&logoColor=white)
![Dynatrace](https://img.shields.io/badge/Dynatrace-1496FF?style=flat-square&logo=dynatrace&logoColor=white)
![Fluent Bit](https://img.shields.io/badge/Fluent_Bit-49BDA5?style=flat-square&logo=fluentbit&logoColor=white)
![Zabbix](https://img.shields.io/badge/Zabbix-CC2936?style=flat-square&logo=zabbix&logoColor=white)

**Languages & Scripting**<br/>
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-5FA04E?style=flat-square&logo=nodedotjs&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white)

**Systems, Data & Networking**<br/>
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-FF4438?style=flat-square&logo=redis&logoColor=white)
![Okta](https://img.shields.io/badge/Okta-007DC1?style=flat-square&logo=okta&logoColor=white)

## 💼 Experience

### DevOps Engineer · Miaki Media Ltd, Bangladesh
*Jan 2025 – Present*

- **Kubernetes platform:** Run production Kubernetes clusters for Dockerized microservices. I manage the Helm charts, ConfigMaps, Secrets and resource quotas for multi-tenant workloads, so product teams get consistent deployments.
- **Centralized logging:** Deployed Elasticsearch, Logstash and Kibana, with custom dashboards and symptom-based alert rules.
- **CI/CD:** Pipeline-as-code in GitLab CI and GitHub Actions, with reusable YAML templates, secret management, image and dependency scanning gates, and multi-stage deployments.
- **Jenkins at scale:** Run a master–agent setup for parallel builds and maintain shared pipelines and plugins for several development teams.
- **Monitoring & on-call:** Host and cluster monitoring for Redis and Kubernetes with Zabbix, Prometheus and Grafana. I tune alert thresholds to cut noise and catch slowdowns before users see an outage.

### DevOps Engineer · BJIT Limited
*Nov 2021 – Dec 2024*

- **Infrastructure as code:** Provisioned AWS, GCP and Azure with Terraform and configured it with Ansible, all version-controlled and peer-reviewed across dev, staging and production.
- **CI/CD standardization:** Standardized pipelines across teams on Jenkins, GitLab and GitHub Actions.
- **Containers:** Led Docker and Kubernetes (EKS/GKE) deployments for Node.js, Java/Spring Boot and Flask services, and managed image promotion through ECR, Artifact Registry and Docker Hub.
- **Logging pipeline:** Ran Fluent Bit as a sidecar to send logs to BigQuery, and set up alerting with Cloud Monitoring, CloudWatch, ELK, Grafana and Zabbix.
- **Automation:** Wrote Bash and Python tooling that cut manual deployment and environment-setup steps for developers.

## 🛠️ Featured Projects

| Project | What I built | Stack |
|---|---|---|
| **React-MySQL-Penta** | Designed and deployed 5 Spring Boot services and 2 React frontends on GKE (single-node for staging, multi-node for production), backed by Cloud SQL, with **20+ log streams** shipped to BigQuery | GKE · Cloud SQL · Fluent Bit · BigQuery |
| **Snowflake → BigQuery / MySQL ETL** | Continuous data pipeline: in-warehouse SQL stages data to Cloud Storage, then Cloud Functions load it into MySQL and BigQuery, with validation and re-execution on failure | Snowflake · Cloud Functions · GCS · BigQuery · MySQL |
| **DevOps R&D** | Full DevOps lifecycle for a frontend app, plus a C# notification service that emails the team when a pipeline or deployment fails | GitHub · Jenkins · Ansible · ELK · C# |
| **Test Automation** | Translation-accuracy testing: Apps Script loads CSV datasets, a serverless function scores them, and the results are exported as a CSV report | Apps Script · Serverless |

## 🎓 Education & Certifications

- **Professional Masters in IT (PMIT)** — Jahangirnagar University, 2020
- **B.Sc. in Computer Science & Engineering** — American International University–Bangladesh (AIUB), 2016–2019
- 📜 Scrum Certification · IELTS 7.0 · BJIT Academy Training

## 🤝 Let's Connect

I'm always happy to talk about Kubernetes, platform engineering, observability, or anything that makes deployments boring (in the good way).
Reach me on [LinkedIn](https://www.linkedin.com/in/dipon778) or at [dipon778@gmail.com](mailto:dipon778@gmail.com).

<p align="center"><i>"If it hurts, do it more often — and automate it."</i></p>
