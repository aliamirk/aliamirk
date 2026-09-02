<div align="center">

# Muhammad Ali

**Cloud Engineer & Applied AI/Backend Developer**

Cloud infrastructure, service mesh, and applied AI systems that run in production, not just in demos.

[![Medium](https://img.shields.io/badge/Medium-000000?style=flat-square&logo=medium&logoColor=white)](https://medium.com/@aliamirk)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/aliamirk/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/aliamirk)

</div>

<br>

## About

I'm an AWS Cloud Engineer with roots in the AWS re/Start program and about two years of production experience since. My work spans cloud infrastructure, backend engineering, and applied AI, usually where those three overlap: zero-trust Kubernetes networking, gRPC microservices, GPU-backed model serving, and computer vision pipelines running against real factory CCTV feeds.

I care about the same things whether I'm shipping infra or a model: does it hold up in production, is it observable, and does it cost what it should.

<br>

## Stack

**Cloud & DevOps**
 
![Amazon Web Services](https://img.shields.io/badge/Amazon%20Web%20Services-000000?style=flat-square&logo=amazonaws&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-000000?style=flat-square&logo=microsoftazure&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-000000?style=flat-square&logo=terraform&logoColor=white)
![EKS](https://img.shields.io/badge/EKS-000000?style=flat-square)
![Kubernetes](https://img.shields.io/badge/Kubernetes-000000?style=flat-square&logo=kubernetes&logoColor=white)
![Istio](https://img.shields.io/badge/Istio-000000?style=flat-square&logo=istio&logoColor=white)
![ArgoCD](https://img.shields.io/badge/ArgoCD-000000?style=flat-square&logo=argo&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-000000?style=flat-square&logo=githubactions&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-000000?style=flat-square&logo=docker&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-000000?style=flat-square&logo=nginx&logoColor=white)
 
**Languages & Frameworks**
 
![Python](https://img.shields.io/badge/Python-000000?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-000000?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-000000?style=flat-square&logo=javascript&logoColor=white)
![Java](https://img.shields.io/badge/Java-000000?style=flat-square&logo=openjdk&logoColor=white)
![C++](https://img.shields.io/badge/C%2B%2B-000000?style=flat-square&logo=cplusplus&logoColor=white)
![C](https://img.shields.io/badge/C-000000?style=flat-square)
![Bash](https://img.shields.io/badge/Bash-000000?style=flat-square&logo=gnubash&logoColor=white)
![gRPC](https://img.shields.io/badge/gRPC-000000?style=flat-square)
![FastAPI](https://img.shields.io/badge/FastAPI-000000?style=flat-square&logo=fastapi&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-000000?style=flat-square&logo=nodedotjs&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-000000?style=flat-square&logo=mongodb&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-000000?style=flat-square&logo=mysql&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-000000?style=flat-square&logo=postgresql&logoColor=white)
![Boto3](https://img.shields.io/badge/Boto3-000000?style=flat-square)
 
**AI & Computer Vision**
 
![LangChain](https://img.shields.io/badge/LangChain-000000?style=flat-square&logo=langchain&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-000000?style=flat-square)
![OpenAI](https://img.shields.io/badge/GPT--4o--mini-000000?style=flat-square&logo=openai&logoColor=white)
![YOLOv8](https://img.shields.io/badge/YOLOv8-000000?style=flat-square)
![BoT-SORT](https://img.shields.io/badge/BoT--SORT-000000?style=flat-square)
![MediaPipe](https://img.shields.io/badge/MediaPipe-000000?style=flat-square)
![vLLM](https://img.shields.io/badge/vLLM-000000?style=flat-square)
 
**Observability & Security**
 
![Grafana](https://img.shields.io/badge/Grafana-000000?style=flat-square&logo=grafana&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-000000?style=flat-square&logo=prometheus&logoColor=white)
![OpenID Connect](https://img.shields.io/badge/OpenID%20Connect-000000?style=flat-square&logo=openid&logoColor=white)
![Zero Trust Networking](https://img.shields.io/badge/Zero%20Trust%20Networking-000000?style=flat-square)
![HIPAA-Aligned Infra](https://img.shields.io/badge/HIPAA--Aligned%20Infra-000000?style=flat-square)
![IAM/RBAC](https://img.shields.io/badge/IAM%2FRBAC-000000?style=flat-square)

<br>

## Currently building

- **LLM serving on EKS** — self-hosted open-source LLMs (Llama, Mistral) on GPU nodes, EKS-optimized GPU AMI, g5.xlarge instances, FSx for Lustre for model weights, warm-pool inference
- **Real-time sign language recognition** — MediaPipe hand landmarks feeding a lightweight classifier, targeting 100 to 150 custom signs, built for mobile camera streaming

<br>

## Featured projects

| Project | What it is |
|---|---|
| [Vapor](https://github.com/aliamirk/vapor-aws-cost-auditor) | Open-source AWS cost auditor — parallel service scanning with LangGraph + GPT-4o-mini, severity-tagged reports |
| EKS + Istio Service Mesh | Production-grade zero-trust networking on Kubernetes, Terraform, GitOps, canary traffic |
| Clinic Platform | gRPC microservices on EKS with an SQS event backbone and mTLS-enforced mesh |
| LLM Serving on EKS | GPU-backed inference for self-hosted open-source LLMs |
| Factory CV Pipeline | YOLOv8/BoT-SORT detection and tracking for real-time box/sack counting |
| Sign Language Recognition | MediaPipe landmarks + classifier for real-time sign detection, mobile-bound |
| Gatepass & Clinic Systems | FastAPI + MongoDB backends in production, with search, analytics, and PDF generation |
| Systems Programming | Multithreaded C++17 task scheduler on raw POSIX primitives, classical OS concurrency problems in C |

<br>

## Writing

I write up what I build, mostly Kubernetes and service mesh, applied CV in production, and practical LLM tooling that isn't just a demo.

→ [Medium](https://medium.com/@aliamirk)

<br>

## Get in touch

Open to conversations on Kubernetes, service mesh, cloud architecture, computer vision, or backend systems. Feel free to connect, open an issue, or dig through the repos.

</div>
