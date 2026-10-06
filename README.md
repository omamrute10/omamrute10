<!-- ============================== HEADER ============================== -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0ea5e9,50:6366f1,100:a855f7&height=220&section=header&text=Om%20Amrute&fontSize=62&fontColor=ffffff&animation=twinkling&fontAlignY=38&desc=Cloud%20%7C%20DevOps%20%7C%20Automation&descSize=22&descAlignY=60" alt="Om Amrute banner"/>
</p>

<p align="center">
  <a href="https://github.com/omamrute10">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=24&duration=3000&pause=1000&color=0EA5E9&center=true&vCenter=true&width=700&height=50&lines=%E2%98%81%EF%B8%8F+Cloud+%26+DevOps+Engineer+in+the+making;%F0%9F%90%B3+Containerizing+apps+with+Docker;%E2%98%B8%EF%B8%8F+Orchestrating+workloads+on+Kubernetes+%28EKS%29;%E2%9A%99%EF%B8%8F+Automating+infra+with+Terraform+%26+Ansible;%F0%9F%9A%80+Shipping+with+CI%2FCD+pipelines" alt="Typing animation"/>
  </a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Open%20to-Internships%20%26%20Entry--level--jobs-a855f7?style=for-the-badge" alt="Open to work"/>
</p>

<p align="center">
  <a href="mailto:omamrute10@gmail.com">
    <img src="https://img.shields.io/badge/Email-omamrute10%40gmail.com-ea4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/>
  </a>
  <a href="https://github.com/omamrute10">
    <img src="https://img.shields.io/badge/GitHub-omamrute10-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/>
  </a>
</p>

---

## 👨‍💻 About Me

```bash
om@cloud:~$ whoami
> Om Amrute — TY BSc Cloud Computing student & aspiring Cloud / DevOps Engineer

om@cloud:~$ cat focus.txt
> ☁️  Cloud       : AWS & Multi-Cloud
> ⚙️  DevOps      : Docker • Kubernetes • Terraform • CI/CD • Observability
> 🐧 Foundations : Linux • Networking • Security
> 🎯 Goal        : Build secure, scalable & automated cloud infrastructure

om@cloud:~$ echo $STATUS
> 🌱 Building practical cloud projects & learning every day
```

I enjoy designing cloud infrastructure, deploying applications, automating environments, and understanding how production systems are built and operated.

---

## 🚀 Featured Project

<table>
<tr>
<td>

### ☁️ Container Orchestration with Kubernetes using AWS

A cloud-native deployment project for running and managing containerized applications on **AWS EKS** — covering networking, load balancing, autoscaling, security and monitoring end to end.

<img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white"/>
<img src="https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white"/>
<img src="https://img.shields.io/badge/Amazon%20EKS-FF9900?style=flat-square&logo=amazoneks&logoColor=white"/>
<img src="https://img.shields.io/badge/CI%2FCD-2088FF?style=flat-square&logo=githubactions&logoColor=white"/>
<img src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white"/>

**AWS services used:**
`EKS` `ECR` `EC2` `VPC` `ALB` `Route 53` `RDS` `CloudWatch` `CloudTrail` `IAM` `CloudFront` `S3` `EBS` `Auto Scaling`

<a href="https://github.com/omamrute10/Container-Orchestration-with-Kubernetes-using-AWS">
  <img src="https://img.shields.io/badge/View%20Repository-%E2%86%92-0ea5e9?style=for-the-badge&logo=github" alt="View repository"/>
</a>

</td>
</tr>
</table>

### 🗺️ High-Level Flow

```mermaid
flowchart LR
    U([👤 User]) --> R53[Route 53]
    R53 --> CF[CloudFront]
    CF --> ALB[Application Load Balancer]

    subgraph VPC["🔒 AWS VPC"]
        ALB --> EKS{{"☸️ EKS Cluster"}}
        EKS --> P1[Pods]
        EKS --> P2[Pods]
        P1 --> RDS[(Amazon RDS)]
        P2 --> RDS
    end

    DEV([💻 Developer]) --> CI[CI/CD Pipeline]
    CI --> ECR[(Amazon ECR)]
    ECR -.pulls image.-> EKS
    EKS -.metrics & logs.-> CW[CloudWatch]

    style EKS fill:#326CE5,color:#fff,stroke:#fff
    style ALB fill:#FF9900,color:#000
    style RDS fill:#6366f1,color:#fff
    style CW fill:#0ea5e9,color:#fff
```

---

## 🛠️ Tech Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=aws,azure,gcp,docker,kubernetes,terraform,ansible,jenkins,githubactions,git,github,linux,nginx,prometheus,grafana,mysql,python,bash,html&perline=10" alt="Tech stack icons"/>
</p>

<details open>
<summary><b>☁️ Cloud & Containers</b></summary>
<br>

| Area | Skills |
|------|--------|
| ☁️ **Cloud Platforms** | AWS (primary) • Azure • Google Cloud — multi-cloud core services |
| 🐳 **Containerization** | Docker, Dockerfiles, Images, Container Networking |
| ☸️ **Orchestration** | Kubernetes — Pods, Deployments, Services, Ingress, HPA, RBAC • Helm |

</details>

<details open>
<summary><b>⚙️ Automation & Delivery</b></summary>
<br>

| Area | Skills |
|------|--------|
| 🏗️ **Infrastructure as Code** | Terraform, AWS Infrastructure Provisioning |
| 🤖 **Config Management** | Ansible — Playbooks, Inventory, SSH Automation |
| 🔄 **CI/CD** | Jenkins, GitHub Actions |
| 🌿 **Version Control** | Git, GitHub, Branching, Repository Management |

</details>

<details open>
<summary><b>🐧 Systems, Networking & Observability</b></summary>
<br>

| Area | Skills |
|------|--------|
| 🐧 **Linux** | Administration, SSH, Processes, Filesystems, Permissions, Package Management |
| 🌐 **Networking** | IP Addressing, Subnets, Routing, DNS, Firewalls, Security Groups, VPC |
| 🔐 **Security** | IAM, RBAC, Security Fundamentals |
| 📈 **Monitoring** | CloudWatch, Prometheus & Grafana fundamentals |
| 🗄️ **Database** | MySQL, Amazon RDS |
| 💻 **Programming** | Python fundamentals, Bash/Shell scripting, HTML basics, Nginx |

</details>

---

## 📚 Currently Learning

<p align="center">
  <img src="https://img.shields.io/badge/Advanced%20Cloud%20Architecture-FF9900?style=for-the-badge&logo=amazonwebservices&logoColor=white"/>
  <img src="https://img.shields.io/badge/DevOps-2088FF?style=for-the-badge&logo=githubactions&logoColor=white"/>
  <img src="https://img.shields.io/badge/Cloud%20Automation-EE0000?style=for-the-badge&logo=ansible&logoColor=white"/>
  <img src="https://img.shields.io/badge/Multi--Cloud-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white"/>
</p>

---

## 🎯 Career Goal

<p align="center">
  <i>"To become a Cloud / DevOps Engineer and build secure, scalable and automated cloud infrastructure."</i>
</p>

<p align="center">
  <code>Cloud Infrastructure</code> • <code>DevOps</code> • <code>Multi Cloud</code> • <code>Automation</code>
</p>

---


## 🤝 Let's Connect

<p align="center">
  Open to <b>internships</b>, <b>Entry-level jobs</b>
</p>

<p align="center">
  <a href="mailto:omamrute10@gmail.com">
    <img src="https://img.shields.io/badge/Say%20Hello-omamrute10%40gmail.com-ea4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email me"/>
  </a>
</p>

<p align="center">
  <b>☁️ Building in the cloud. ⚙️ Automating infrastructure. 🚀 Learning every day.</b>
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:6366f1,50:0ea5e9,100:a855f7&height=120&section=footer&animation=twinkling" alt="Footer"/>
</p>
