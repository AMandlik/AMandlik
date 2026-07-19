# Hello There 👋

I'm **Arpit Mandlik**

[![Typing SVG](https://readme-typing-svg.herokuapp.com?font=Fira+Code&pause=1000&color=2E9EF7&center=true&vCenter=true&width=600&duration=2000&lines=DevOps+Engineer;GCP+%7C+AWS+%7C+Kubernetes+(GKE+%26+EKS);Terraform+%7C+CI%2FCD+%7C+GitOps;Observability+%26+Cost+Optimization)](https://git.io/typing-svg)

---

## 🚀 About Me

I'm a **DevOps Engineer** with **5+ years of hands-on experience** designing, automating, and operating production-grade, scalable, and secure cloud infrastructure.

I specialize in **GCP, AWS, Kubernetes (GKE & EKS), Terraform, CI/CD automation, GitOps, and observability**, with proven impact reducing deployment time, cutting cloud spend, and hardening security posture across multi-project cloud environments.

- 🔭 Currently working as a **DevOps Engineer at Reventlabs**, Indore, India
- ☸️ Managing **multi-AZ, highly available Kubernetes clusters** on GKE & EKS
- ⚙️ Automating infrastructure with **Terraform** — reusable modules across GCP/AWS
- 🚀 Building **CI/CD pipelines** with GitHub Actions, GitOps via ArgoCD & Argo Rollouts
- 📊 Running observability stacks — **Prometheus, Grafana, Datadog, ELK, Victoria Metrics**
- 🔐 Practicing DevSecOps — **Trivy, SonarCloud, Cloud Armor, Workload Identity Federation**
- 💰 Driving **cloud cost optimization** with Kubecost & Cloud Custodian
- 🤝 Collaborating cross-functionally to keep releases smooth and on time

---

## 🛠️ Tech Stack

### **Cloud Platforms**

![GCP](https://raw.githubusercontent.com/devicons/devicon/master/icons/googlecloud/googlecloud-original.svg) ![AWS](https://raw.githubusercontent.com/devicons/devicon/master/icons/amazonwebservices/amazonwebservices-original-wordmark.svg)

- **GCP** — GKE, VPC, Cloud Load Balancing, Cloud DNS, Cloud Storage, IAM, Workload Identity Federation (WIF), Cloud Logging, Cloud Monitoring, Cloud Run, Cloud Armor
- **AWS** — EKS, ECS, EC2, VPC, IAM, S3, Route53, Lambda, WAF

---

### **Containerization & Orchestration**

![Docker](https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original-wordmark.svg) ![Kubernetes](https://raw.githubusercontent.com/devicons/devicon/master/icons/kubernetes/kubernetes-plain-wordmark.svg) ![Helm](https://raw.githubusercontent.com/devicons/devicon/master/icons/helm/helm-original.svg)

- Docker — multi-stage builds, image optimization
- Kubernetes (GKE & EKS) — HPA with custom metrics, auto-healing infra, multi-AZ clusters
- Helm — chart-based deployments across environments
- Gloo API Gateway for traffic management & service exposure

---

### **GitOps & CI/CD**

![GitHub Actions](https://raw.githubusercontent.com/devicons/devicon/master/icons/githubactions/githubactions-original.svg) ![ArgoCD](https://raw.githubusercontent.com/devicons/devicon/master/icons/argocd/argocd-original.svg)

- GitHub Actions — reusable/centralized workflows, self-hosted & auto-scaling runners
- ArgoCD, Argo Rollouts, FluxCD — progressive delivery & GitOps
- Blue-green deployment pipelines with automated rollback (GitHub Actions + Python)
- On-demand, auto-teardown QA/test environments in isolated namespaces

---

### **Infrastructure as Code**

![Terraform](https://raw.githubusercontent.com/devicons/devicon/master/icons/terraform/terraform-original.svg)

- Terraform — reusable modules for GCP/AWS, consistent multi-environment provisioning
- Fully automated infra provisioning via GitHub Actions CI (zero manual steps)

---

### **Monitoring, Observability & Security**

![Prometheus](https://raw.githubusercontent.com/devicons/devicon/master/icons/prometheus/prometheus-original.svg) ![Grafana](https://raw.githubusercontent.com/devicons/devicon/master/icons/grafana/grafana-original.svg)

- Prometheus + Grafana, Grafana Loki (with Alloy) for centralized logging
- Datadog — real-time monitoring across GKE and Cloud Run
- GCP Stackdriver, ELK, Victoria Metrics
- Trivy (container scanning) & SonarCloud (SAST) integrated into CI/CD
- Google Cloud Armor — DDoS protection & rate limiting
- OpsGenie — automated on-call scheduling & incident alerting
- External Secrets Operator + Reloader — automated secret rotation, zero-downtime restarts

---

### **Databases**

![PostgreSQL](https://raw.githubusercontent.com/devicons/devicon/master/icons/postgresql/postgresql-original-wordmark.svg) ![MongoDB](https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original-wordmark.svg)

- PostgreSQL (including self-managed CloudNativePG on Kubernetes)
- MongoDB
- ScyllaDB

---

### **Languages & Scripting**

![Python](https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg) ![Bash](https://raw.githubusercontent.com/devicons/devicon/master/icons/bash/bash-original.svg)

- Python, Bash — automation of repetitive ops tasks and deployment pipelines

---

## 🏢 Professional Experience

### **DevOps Engineer — Reventlabs**

📍 Indore, India | **June 2022 – Present**

- Architected **multi-AZ, highly available Kubernetes clusters** with auto-healing infrastructure and scalable microservices
- Implemented **custom metrics-based autoscaling** (HPA) for dynamic, workload-driven scaling
- Migrated multiple services from individual load balancers to a **single shared load balancer**, cutting infra overhead with minimal downtime
- Automated **secret rotation & service restarts** via External Secrets Operator + Reloader — eliminated 100% manual intervention
- Deployed monolithic apps on **Cloud Run** alongside microservices on **GKE**, using GitHub Actions + Helm
- Executed a **seamless PostgreSQL migration** from Cloud SQL to self-managed CloudNativePG on Kubernetes, reducing cloud spend
- Used **Kubecost & Cloud Custodian** for namespace/deployment/node-level cost allocation and optimization
- Deployed **Cloud Armor** security policies, mitigating DDoS/abusive traffic by **over 95%**
- Automated infra provisioning with **Terraform + GitHub Actions**, cutting deployment time by **70%** and eliminating manual provisioning entirely
- Managed **self-hosted GitHub Actions runners** via Helm across multiple GCP projects with Workload Identity Federation, reducing resource usage by **15%**
- Implemented **auto-scaling, on-demand GitHub Runners** on GCP, provisioned via webhooks — cutting CI/CD cost
- Centralized CI/CD with **reusable GitHub Actions workflows** across **7+ repositories**, reducing maintenance by **80%** and removing all long-lived service account keys
- Designed a fully automated **blue-green deployment pipeline** (GitHub Actions + Python) with traffic switching, failure handling, and rollback logic
- Built a pipeline provisioning **on-demand QA/test environments** in isolated namespaces with automatic teardown
- Integrated **Trivy & SonarCloud** into CI/CD for container vulnerability scanning and code security
- Deployed **Datadog** for real-time observability across GKE and Cloud Run
- Built a logging & metrics stack with **Grafana Loki (Alloy) + Prometheus-Grafana**
- Improved on-call efficiency with **OpsGenie** — automated scheduling and real-time alerting
- Collaborated on **JIRA** ticket management to keep project workflows and deployment timelines on track

---

### **DevOps Engineer — Nenosystems Private Limited**

📍 Indore, India | **June 2021 – June 2022**

- Managed and provisioned **AWS infrastructure** (EC2, VPC, S3, IAM) for scalable, secure deployments
- Containerized applications with **Docker**, standardizing builds across dev, staging, and prod
- Optimized Docker images with **multi-stage builds**, reducing image size and improving deploy speed
- Built and maintained **CI/CD pipelines** automating build, test, and deployment stages
- Wrote **Bash scripts** to automate repetitive operational tasks

---

## 💻 Key Projects

### **Mobility, Delivery & FinTech Super App**
Large-scale on-demand services platform spanning ride-hailing, food delivery, grocery delivery, last-mile logistics, and digital payment solutions.

### **Creative Project Management — Content Operations Platform**
SaaS platform enabling enterprises, marketing teams, and creative agencies to manage digital content production, asset lifecycle, campaign workflows, stakeholder collaboration, and AI-assisted creative operations.

### **Cloud Communications Platform (CPaaS)**
Large-scale cloud communication platform delivering Voice, SMS, Video, and Authentication services to enterprise customers across multiple regions.

---

## 🎓 Education

**Bachelor of Engineering, Computer Science and Engineering**
Acropolis Technical Campus, Indore (M.P.), India | 2012 – 2017

---

## 🌐 Connect With Me

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?style=for-the-badge&logo=linkedin)](https://linkedin.com/in/arpit-mandlik-62b427115)
[![Email](https://img.shields.io/badge/Email-Contact-red?style=for-the-badge&logo=gmail)](mailto:arpitmandlik026@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-black?style=for-the-badge&logo=github)](https://github.com/AMandlik)

📍 Indore (M.P.), India | 📱 +91 9893098360

---

### 💡 *"Automate everything, secure everything, optimize the rest."*
