<div align="center">

# Muhammad Bilal Talha
**DevOps Engineer | Full Stack Developer**

Mustafa Town, Lahore · bilalsaeed000095@gmail.com

<p align="center">
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=18&duration=3000&pause=1000&color=38BDF8&center=true&vCenter=true&width=780&lines=Zero-Trust+Cloud-to-On-Prem+Migrations;Edge-AI+Pipelines+on+NVIDIA+%26+Hailo+Hardware;Deterministic+CI%2FCD+%26+Infrastructure+as+Code;No+Open+Ports+%C2%B7+No+Manual+Bottlenecks" alt="Typing SVG" />
  </a>
</p>

<p align="center">
  <a href="https://bilal-talha.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-0F172A?style=for-the-badge&logo=vercel&logoColor=38BDF8" alt="Portfolio" /></a>
  <a href="https://linkedin.com/in/muhammad-bilal-talha-225543246"><img src="https://img.shields.io/badge/LinkedIn-0F172A?style=for-the-badge&logo=linkedin&logoColor=38BDF8" alt="LinkedIn" /></a>
  <a href="https://instagram.com/bilal.talha__"><img src="https://img.shields.io/badge/Instagram-0F172A?style=for-the-badge&logo=instagram&logoColor=38BDF8" alt="Instagram" /></a>
  <a href="mailto:bilalsaeed000095@gmail.com"><img src="https://img.shields.io/badge/Email-0F172A?style=for-the-badge&logo=gmail&logoColor=38BDF8" alt="Email" /></a>
</p>

<br>

<img src="./assets/terminal.svg" alt="Live System Terminal" width="820" />

<br><br>

*I engineer systems that eliminate manual bottlenecks and refuse to break under load.*

*From ripping entire cloud environments out of AWS and anchoring them on bare-metal on-prem clusters behind zero-trust tunnels, to shipping edge-AI vision pipelines on NVIDIA and Hailo hardware that erase thousands of hours of repetitive human labor.*

*Every deployment is automated. Every release gate is deterministic. No open ports, no manual intervention, no wasted cycles.*

*Ship resilient code, own your infrastructure from the kernel up, and let the machines do the heavy lifting.*

</div>

---

### Impact at a Glance

- **35+ hrs/week** of manual AI team workload eliminated via automated full-stack AI pipelines
- **3x faster** data labeling achieved with an internal GPU-accelerated SAM annotation tool
- **100% cloud-to-on-prem** environment migration (3 production apps + Dev/UAT/Prod workloads) with zero open inbound ports
- **35% reduction** in manual client response time via a custom customer portal and Lark Suite workflow automation
- **17+ production & personal systems** shipped across Full Stack, Edge AI, and DevOps infrastructure

---

### System Architecture & Blueprints

```mermaid
flowchart LR
    Internet((Internet)) -->|Zero-Trust TLS| CF[Cloudflare Tunnel]
    CF -->|No Open Ports| K8s[On-Prem Ubuntu / K8s Cluster]
    K8s --> App1[FastAPI / Django Services]
    K8s --> DB[(PostgreSQL + pgvector)]
    Edge[NVIDIA / Hailo Edge Nodes] -->|MQTT Telemetry| K8s
    GHA[GitHub Actions + SentinelGate] -->|Deterministic Deploy| K8s
