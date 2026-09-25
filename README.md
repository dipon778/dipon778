<h1 align="center">Hi, I'm Dipon 👋</h1>

<p align="center">
  <i>Pipeline red? Pods in CrashLoopBackOff? Pager won't stop buzzing?</i><br/>
  Take a breath and <a href="https://dipon778.github.io/just-a-piano/"><b>🎹 play a few keys here</b></a>. The cluster can wait 30 seconds. Probably.
</p>

<p align="center">
  <b>DevOps Engineer</b> · Kubernetes · Cloud Infrastructure · CI/CD · Observability<br/>
  📍 Dhaka, Bangladesh
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/dipon778"><img src="https://img.shields.io/badge/LinkedIn-dipon778-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:dipon778@gmail.com"><img src="https://img.shields.io/badge/Email-dipon778@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
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

> 📌 **Currently:** running production Kubernetes at Miaki Media and standardizing CI/CD templates and Helm-based deployments across product teams.

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

## 🧰 Core Stack

<p>
  <img src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white" alt="AWS"/>
  <img src="https://img.shields.io/badge/Google_Cloud-4285F4?style=flat-square&logo=googlecloud&logoColor=white" alt="Google Cloud"/>
  <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white" alt="Kubernetes"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker"/>
  <img src="https://img.shields.io/badge/Helm-0F1689?style=flat-square&logo=helm&logoColor=white" alt="Helm"/>
  <img src="https://img.shields.io/badge/Terraform-844FBA?style=flat-square&logo=terraform&logoColor=white" alt="Terraform"/>
  <img src="https://img.shields.io/badge/Ansible-EE0000?style=flat-square&logo=ansible&logoColor=white" alt="Ansible"/>
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" alt="GitHub Actions"/>
  <img src="https://img.shields.io/badge/GitLab_CI-FC6D26?style=flat-square&logo=gitlab&logoColor=white" alt="GitLab CI"/>
  <img src="https://img.shields.io/badge/Jenkins-D24939?style=flat-square&logo=jenkins&logoColor=white" alt="Jenkins"/>
  <img src="https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white" alt="Prometheus"/>
  <img src="https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white" alt="Grafana"/>
  <img src="https://img.shields.io/badge/ELK_Stack-005571?style=flat-square&logo=elasticstack&logoColor=white" alt="ELK Stack"/>
  <img src="https://img.shields.io/badge/Linux-333333?style=flat-square&logo=linux&logoColor=white" alt="Linux"/>
  <img src="https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white" alt="Bash"/>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python"/>
</p>

<sub>Also: Dynatrace · Fluent Bit · Zabbix · Nginx · MySQL · PostgreSQL · MongoDB · Redis · BigQuery · Okta · Node.js · SQL</sub>

## 💼 Experience

### DevOps Engineer · Miaki Media Ltd, Bangladesh
*Jan 2025 – Present*

- **Kubernetes platform:** Run production clusters for Dockerized microservices, managing Helm charts, Secrets and resource quotas so multi-tenant product teams get consistent deployments.
- **CI/CD with security gates:** Built pipeline-as-code in GitLab CI and GitHub Actions with reusable YAML templates, image and dependency scanning, and multi-stage rollouts, plus shared Jenkins pipelines for several teams.
- **Observability & on-call:** Set up ELK, Prometheus, Grafana and Zabbix, and tuned symptom-based alerts to cut noise and catch slowdowns before users see an outage.

### DevOps Engineer · BJIT Limited
*Nov 2021 – Dec 2024*

- **Multi-cloud IaC:** Provisioned AWS, GCP and Azure with Terraform and Ansible, peer-reviewed across dev, staging and production.
- **Containers at scale:** Led EKS and GKE deployments for Node.js, Spring Boot and Flask services, with image promotion through ECR, Artifact Registry and Docker Hub.
- **Logging & automation:** Shipped logs to BigQuery through Fluent Bit sidecars, and wrote Bash and Python tooling that removed manual deploy and environment-setup steps.

<sub>Full history on <a href="https://www.linkedin.com/in/dipon778">LinkedIn</a>.</sub>

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
