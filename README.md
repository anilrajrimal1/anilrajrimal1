<a href="https://anilrajrimal.com.np"><img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,100:7FFF00&height=180&section=header&text=Anil%20Raj%20Rimal&fontSize=42&fontColor=ffffff&fontAlignY=35&desc=DevOps%20Engineer%20%C2%B7%20AWS%20%C2%B7%20Kubernetes%20%C2%B7%20Terraform&descAlignY=58&descSize=16" alt="Anil Raj Rimal, DevOps Engineer"/></a>

<p align="center">
  <a href="https://anilrajrimal.com.np">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=3000&pause=600&color=7FFF00&background=00000000&center=true&vCenter=true&width=560&lines=Terraform+%2B+Terragrunt+on+AWS;CI%2FCD+that+ships+in+minutes%2C+not+half-hours;Observability+across+AWS+accounts;AWS+Community+Builder" alt="Typing SVG"/>
  </a>
</p>

<p align="center">
  <a href="https://anilrajrimal.com.np"><img src="https://img.shields.io/badge/Portfolio-7FFF00?style=for-the-badge&logo=googlechrome&logoColor=black" alt="Portfolio"/></a>
  <a href="https://www.linkedin.com/in/anilrajrimal/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="https://medium.com/@anilrajrimal"><img src="https://img.shields.io/badge/Medium-000000?style=for-the-badge&logo=medium&logoColor=white" alt="Medium"/></a>
  <a href="mailto:anilrajrimal@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/AWS-Community%20Builder-FF9900?style=flat-square&logo=amazonwebservices&logoColor=white" alt="AWS Community Builder"/>
  <img src="https://img.shields.io/badge/Based%20in-Kathmandu%2C%20Nepal-0d1117?style=flat-square" alt="Based in Kathmandu, Nepal"/>
  <img src="https://img.shields.io/badge/Open%20to-Remote%20roles-7FFF00?style=flat-square" alt="Open to remote roles"/>
</p>

---

<table align="right">
  <tr>
    <td align="center">
      <img width="280" src="https://media.giphy.com/media/QMHoU66sBXqqLqYvGO/giphy.gif" alt="This is fine"/><br/>
      <sub><i>how prod looks before I set up monitoring</i></sub>
    </td>
  </tr>
</table>

## About Me

DevOps Engineer working on the cloud and Kubernetes infrastructure behind open-source humanitarian mapping tools used in disaster response. Before that I ran AWS production infrastructure for geospatial and government-sector platforms. I went from intern to engineer one incident and one Terraform module at a time, and I now supervise the interns and trainees coming up behind me.

I automate what's worth automating, watch what needs watching, and lock down what needs locking down. The goal is systems that are boring in the best way.

**Highlights**

- Cut CI/CD build-and-deploy time from **20-25 min to 5-10 min** with layer caching, dependency caching and multi-stage builds
- Led the move from **Jenkins to reusable GitHub Actions** workflows and custom actions
- Replaced long-lived AWS keys with **OIDC** across CI; production access through **Teleport**
- Built **cross-account observability** with CloudWatch OAM and Grafana alerting
- Run services on **EKS** through **ArgoCD**, Helm and Sealed Secrets
- Worked remotely with an **Australian drone and satellite imagery platform** on GPU worker autoscaling (ECS, Lambda, RabbitMQ)

<br clear="right"/>

## Tech Stack

<table>
  <tr>
    <td><b>Cloud & IaC</b></td>
    <td><img src="https://skillicons.dev/icons?i=aws,terraform,cloudflare" alt="AWS, Terraform, Cloudflare"/></td>
    <td><sub>Terragrunt · ECS Fargate · Aurora Serverless v2 · CloudFront · Lambda</sub></td>
  </tr>
  <tr>
    <td><b>Containers & CI/CD</b></td>
    <td><img src="https://skillicons.dev/icons?i=docker,kubernetes,githubactions,jenkins,git" alt="Docker, Kubernetes, GitHub Actions, Jenkins, Git"/></td>
    <td><sub>EKS · ArgoCD · Helm · Sealed Secrets · OIDC · Teleport</sub></td>
  </tr>
  <tr>
    <td><b>Observability & Systems</b></td>
    <td><img src="https://skillicons.dev/icons?i=prometheus,grafana,linux,bash,nginx" alt="Prometheus, Grafana, Linux, Bash, Nginx"/></td>
    <td><sub>CloudWatch · OAM · Alerting</sub></td>
  </tr>
  <tr>
    <td><b>Languages & Data</b></td>
    <td><img src="https://skillicons.dev/icons?i=python,postgres,redis,mongodb,rabbitmq" alt="Python, PostgreSQL, Redis, MongoDB, RabbitMQ"/></td>
    <td><sub>Python CLIs on PyPI · Celery</sub></td>
  </tr>
</table>

## Featured Work

| Project | What it is | Proof |
|---|---|---|
| [**aws-ecs-platform-infra**](https://github.com/anilrajrimal1/aws-ecs-platform-infra) | Multi-service AWS platform in Terraform + Terragrunt: ECS Fargate, Aurora Serverless v2, Redis, CloudFront, ALB, with stateful and purgeable layers split for cost | Architecture notes and ADRs |
| [**dockedup**](https://github.com/anilrajrimal1/dockedup) | `htop` for Docker Compose: live CPU/memory, health, logs and shell from one terminal | ![stars](https://img.shields.io/github/stars/anilrajrimal1/dockedup?style=flat-square) ![pypi](https://img.shields.io/pypi/v/dockedup?style=flat-square) |
| [**n8n-backups**](https://github.com/anilrajrimal1/n8n-backups) | Scheduled backup of every n8n workflow to a GitHub repo | ![stars](https://img.shields.io/github/stars/anilrajrimal1/n8n-backups?style=flat-square) |
| [**phase-secrets-fetch-action**](https://github.com/anilrajrimal1/phase-secrets-fetch-action) | GitHub Action that pulls secrets from Phase into CI without hardcoding them | [![Marketplace](https://img.shields.io/badge/GitHub-Marketplace-2088FF?style=flat-square&logo=githubactions&logoColor=white)](https://github.com/marketplace/actions/fetch-phase-secrets) |
| [**deploy-with-teleport**](https://github.com/anilrajrimal1/deploy-with-teleport) | GitHub Action to deploy a Compose stack through Teleport instead of open SSH | Zero-trust deploys |

## Latest Writing

| Article | Published on |
|---|---|
| [How to Build Multi-Account AWS Observability with CloudWatch OAM and Grafana](https://medium.com/@anilrajrimal/how-to-build-multi-account-aws-observability-with-cloudwatch-oam-and-grafana-00d6a1f10768) | Medium · Oct 2026 |
| [Docker Log Rotation: The Production Lesson Most Teams Learn After the Disk Is Already Full](https://blog.devops.dev/docker-log-rotation-the-production-lesson-most-teams-learn-after-the-disk-is-already-full-ae9e60bfbf20) | DevOps.dev · Jul 2026 |
| [DockedUp: My First DevOps Tool to Simplify Docker Monitoring](https://blog.devops.dev/dockedup-my-first-devops-tool-to-simplify-docker-monitoring-b4c79a76f897) | DevOps.dev · Jun 2025 |
| [Using Terraform to Attach an EBS Volume to an EC2 Instance During Boot](https://awstip.com/using-terraform-to-attach-an-ebs-volume-to-an-ec2-instance-during-boot-a588db95b841) | AWS Tip · Jan 2025 |

<p align="right"><a href="https://medium.com/@anilrajrimal">All articles →</a></p>

---

<p align="center">
  <sub>Open to mid-level DevOps, Cloud and Platform roles, remote or global. The fastest way to reach me is <a href="https://www.linkedin.com/in/anilrajrimal/">LinkedIn</a>.</sub>
</p>

<a href="https://anilrajrimal.com.np"><img src="https://capsule-render.vercel.app/api?type=waving&color=0:7FFF00,100:0d1117&height=100&section=footer" width="100%" alt=""/></a>
