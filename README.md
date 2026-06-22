<h1 align="center">Ahmad Swedan</h1>
<p align="center"><b>DevSecOps Engineer</b> · Cloud-Native Security · Infrastructure as Code</p>

<p align="center">
  <a href="mailto:swedam324@gmail.com"><img src="https://img.shields.io/badge/Email-swedam324@gmail.com-0f3460?style=flat-square&logo=gmail&logoColor=white" alt="Email"></a>
  <a href="https://linkedin.com/in/ahmad-swedan"><img src="https://img.shields.io/badge/LinkedIn-ahmad--swedan-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="https://github.com/hag19"><img src="https://img.shields.io/badge/GitHub-hag19-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub"></a>
  <img src="https://img.shields.io/badge/Based%20in-Paris,%20France-555?style=flat-square&logo=googlemaps&logoColor=white" alt="Location">
</p>

---

## About

DevSecOps engineer focused on **shifting security left** — embedding SCA/SAST into CI/CD, hardening containers and Kubernetes, and building Zero-Trust infrastructure entirely as code. Currently at **Nokia (Paris-Saclay)**, with a bare-metal HA Kubernetes home lab and a Rust application-sandbox project on the side. BSc in Systems, Networks & Security at ESGI, Paris.

I like the seam where **security meets infrastructure**: making the secure path the default one, and proving it with reproducible, declarative systems.

---

## Experience

**DevSecOps Engineer** — *Nokia · Paris-Saclay* · `Dec 2024 – Sep 2026`
- Reduced CVE exposure via SCA/SAST dependency scanning in CI/CD (shift-left security)
- Hardened containers: non-root, read-only FS, admission policies on Azure Kubernetes Service
- Implemented Zero-Trust network segmentation and threat modelling across internal microservices
- Centralized log collection & security event monitoring; built internal tooling in C#/.NET MVC

**DevOps Engineer** — *Nexus · ESGI* · `Oct 2023 – Nov 2024`
- Automated server provisioning and app deployment with Ansible playbooks and Docker Compose
- Built and maintained GitLab CI/CD pipelines; managed container registry and image lifecycle
- Deployed Kubernetes workloads; configured VLAN segmentation and OPNsense firewall rules
- Set up Grafana + Prometheus monitoring with centralized logging for club infrastructure

---

## Featured Projects

### 🏗️ Home Lab — Bare-Metal Private Cloud · `2024 – Present`
A fully Infrastructure-as-Code private cloud running on my own hardware.
- **HA Kubernetes** (kubeadm): 3 control-plane (stacked etcd) + 3 workers, keepalived/HAProxy VIP, Calico CNI, BIND9, Rancher, NFS dynamic storage — provisioned via **Terraform & Ansible**
- **GitOps with ArgoCD**: automated sync, multi-env promotion, rollback policies — fully declarative cluster state
- Full IaC stack: Proxmox VE, TrueNAS ZFS, OPNsense + VLAN, Twingate VPN, Grafana/Prometheus/Loki
- GPU passthrough (VFIO/IOMMU), CPU-partitioned nodes, local LLM inference via Ollama

### 🎓 LaboInfra — University Private Cloud · ESGI · `Apr 2026 – Present`
Production bare-metal, multi-rack infrastructure for the school.
- Full VM lifecycle via GitLab CI + Terraform (`bpg/proxmox`) + Ansible; Netbox inventory
- Identity: **authentik** OIDC IdP + **Netbird** mesh VPN
- Security: **Wazuh** SIEM + Grafana/Loki/Alertmanager — zero public exposure

### 🦀 Hagbox — Linux Application Sandbox
- Rust sandbox using Linux **namespaces, seccomp-BPF, Landlock LSM, cgroups v2**
- Default-deny with an audit mode (strace/ptrace) that auto-generates TOML security profiles

### 🛡️ Penetration Testing — Academic Labs
- **Evil Twin** lab: rogue AP, RADIUS bypass, credential capture — full written report
- **Binary exploitation**: Ghidra, edb, shellcode injection, canary bypass (13-page report)

> 📌 More on my pinned repos: [`infrapilot`](https://github.com/hag19/infrapilot) · [`proxmox-k8s-ha`](https://github.com/hag19/proxmox-k8s-ha) · [`wifi-replication`](https://github.com/hag19/wifi-replication) · [`cvec_report`](https://github.com/hag19/cvec_report)

---

## Tech Stack

**Languages**
`Rust` `C` `Go` `Python` `C#` `Java` `PHP` `Bash`

**Security**
`Pentesting` `Reverse Engineering` `seccomp-BPF` `Landlock` `WiFi auditing` `Ghidra` `Burp Suite` `Metasploit` `Wazuh`

**Cloud & Infra**
`Azure` `AWS` `Kubernetes (kubeadm HA)` `Helm` `Rancher` `Calico` `Docker` `Proxmox` `Terraform` `TrueNAS` `Netbox`

**DevOps & GitOps**
`ArgoCD` `Ansible (+Vault)` `GitLab CI/CD` `SCA/SAST` `cert-manager` `Grafana` `Prometheus` `Loki` `Alertmanager`

**Identity & Network**
`Zero Trust` `OPNsense` `Netbird VPN` `OIDC` `authentik` `Active Directory` `BIND9` `HAProxy` `Cisco` `mTLS` `VLAN`

---

## Certifications & Education

- **CC — Certified in Cybersecurity** · (ISC)² · 2025
- **ISO/IEC 27001:2022** · Lead Implementer
- **Cisco CCNA 1, 2 & 3** · Cisco Networking Academy
- **SOC Analyst Path** · Hack The Box Academy
- **EVE-NG** Virtual Network Labs
- **BSc Systems, Networks & Security** · ESGI, Paris · 2023 – 2026

---

## Beyond the Terminal

- 🏆 **2× University Champion** — C Programming · ESGI
- 👥 **VP, Algorithms Association** · ESGI — Clash of Code events & algorithmic workshops
- 🌍 Languages: Ukrainian · Russian · Arabic · English · French (C1)

---

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=hag19&show_icons=true&hide_border=true&theme=tokyonight&count_private=true" alt="GitHub stats" height="160">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=hag19&layout=compact&hide_border=true&theme=tokyonight&langs_count=8" alt="Top languages" height="160">
</p>

<p align="center"><i>📫 Open to DevSecOps / Cloud Security / Platform Engineering roles — reach me at <a href="mailto:swedam324@gmail.com">swedam324@gmail.com</a></i></p>
