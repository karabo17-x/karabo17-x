<div align="center" style="background:#000;padding:2rem;font-family:'Courier New',monospace;color:#00ff41;">
<img src="https://www.kali.org/images/kali-dragon-icon.svg" width="110" style="filter:invert(1) sepia(1) saturate(5) hue-rotate(90deg) brightness(1.2);"/>

# Karabo17-x

<img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=16&duration=3000&pause=800&color=00FF41&center=true&vCenter=true&width=700&lines=Security+Engineer+%40+Eclipse+Softworks;MWR+CyberSec+Alumni;Offensive+%26+Defensive+Ops;DevOps+%26+Automation;Breaking+Systems+to+Secure+Them" />

![](https://img.shields.io/badge/SYSTEM-ONLINE-00ff41?style=for-the-badge&labelColor=000000)
![](https://img.shields.io/badge/ACCESS-GRANTED-00ff41?style=for-the-badge&labelColor=000000)
![](https://img.shields.io/badge/MODE-ULTRA-00ff41?style=for-the-badge&labelColor=000000)

</div>

---

```bash
root@karabo17x:~# whoami
name      : Karabo Mothapo
role      : Security Engineer @ Eclipse Softworks
status    : MWR CyberSec Internship — COMPLETED ✔
location  : South Africa 
objective : Breaking systems to secure them, automating how they're built
project   : Building SIEM
focus     : Cybersecurity + DevOps
```

### ⬡ Mindset Loop

```mermaid
%%{init: {'theme':'base','themeVariables':{'background':'#0d1117','primaryColor':'#262626','primaryTextColor':'#e6e6e6','primaryBorderColor':'#8a8a8a','lineColor':'#b3b3b3','secondaryColor':'#262626','tertiaryColor':'#161616','edgeLabelBackground':'#555555','fontFamily':'Courier New, monospace'}}}%%
flowchart LR
    A["ATTACK<br/>to understand"] --> B["DEFEND<br/>to protect"]
    B --> C["AUTOMATE<br/>to scale"]
    C --> D["REMEMBER<br/>TO REMEMBER"]
    D --> A

    classDef node fill:#262626,stroke:#8a8a8a,stroke-width:2px,color:#e6e6e6;
    class A,B,C,D node;
```

---

##  Cyber Arsenal

|  Offensive |  Defensive |
|---|---|
| SQLi · XSS · CSRF · SSRF | SIEM Monitoring |
| Recon & Enumeration | Threat Detection |
| Exploit Development | System Hardening |
| Network Exploitation | Risk Mitigation |

```
[✔] Burp Suite   [✔] Metasploit   [✔] Nmap
[✔] Wireshark    [✔] Gobuster     [✔] Zenmap
```

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,bash,linux,docker,aws,go,c&theme=dark" />
</p>

### ⬡ Engagement Flow

```mermaid
%%{init: {'theme':'base','themeVariables':{'background':'#0d1117','primaryColor':'#262626','primaryTextColor':'#e6e6e6','primaryBorderColor':'#8a8a8a','lineColor':'#b3b3b3','secondaryColor':'#262626','tertiaryColor':'#161616','edgeLabelBackground':'#555555','fontFamily':'Courier New, monospace'}}}%%
flowchart LR
    R["Recon<br/>Nmap · Gobuster"] --> E["Enumeration<br/>Zenmap · Wireshark"]
    E --> X["Exploitation<br/>Burp · Metasploit"]
    X --> P["Privilege<br/>Escalation"]
    P --> REP["Report &<br/>Remediate"]
    REP -.->|"harden + detect"| SIEM[("SIEM<br/>Rules")]

    classDef step fill:#262626,stroke:#8a8a8a,stroke-width:2px,color:#e6e6e6;
    classDef sink fill:#262626,stroke:#b3b3b3,stroke-width:2px,stroke-dasharray:4 3,color:#e6e6e6;
    class R,E,X,P,REP step;
    class SIEM sink;
```

---

## ⚙ DevOps Arsenal

|  CI/CD & Automation |  Infra & Cloud |
|---|---|
| Jenkins · GitHub Actions | AWS (EC2, IAM, S3, VPC) |
| Docker · Container Hardening | Terraform (IaC) |
| Ansible Playbooks | Kubernetes (learning) |
| Shell/Bash Scripting | Log Aggregation & Monitoring |

```
[✔] Docker       [✔] Terraform    [✔] Ansible
[✔] Jenkins      [~] Kubernetes   [✔] GitHub Actions
```

<p align="center">
  <img src="https://skillicons.dev/icons?i=docker,kubernetes,terraform,ansible,jenkins,githubactions,aws,linux&theme=dark" />
</p>

> Security-minded DevOps: pipelines that fail closed, infra that's hardened by default, and logs that actually get watched.

### ⬡ Fail-Closed Pipeline

```mermaid
%%{init: {'theme':'base','themeVariables':{'background':'#0d1117','primaryColor':'#262626','primaryTextColor':'#e6e6e6','primaryBorderColor':'#8a8a8a','lineColor':'#b3b3b3','secondaryColor':'#262626','tertiaryColor':'#161616','edgeLabelBackground':'#555555','fontFamily':'Courier New, monospace'}}}%%
flowchart LR
    C["Commit"] --> S["Secrets &<br/>SAST Scan"]
    S -->|pass| B["Build<br/>Docker Image"]
    B --> I["Image &<br/>IaC Scan"]
    I -->|pass| D["Deploy<br/>Terraform · Ansible"]
    D --> M["Monitor<br/>Logs → SIEM"]

    S -->|fail| X["BLOCKED"]
    I -->|fail| X

    classDef ok fill:#262626,stroke:#8a8a8a,stroke-width:2px,color:#e6e6e6;
    classDef bad fill:#2a1515,stroke:#c0504d,stroke-width:2px,color:#e6a3a1;
    class C,S,B,I,D,M ok;
    class X bad;
```

---

## ⬡ Active Targets

```
[✔] Web Exploitation
[✔] Network Attacks
[✔] Privilege Escalation
[~] Advanced Malware Analysis   ← in progress
[~] CI/CD Pipeline Security     ← in progress
[~] Infrastructure as Code      ← in progress
```

```mermaid
%%{init: {'theme':'base','themeVariables':{'background':'#0d1117','primaryColor':'#262626','primaryTextColor':'#e6e6e6','primaryBorderColor':'#8a8a8a','lineColor':'#b3b3b3','secondaryColor':'#262626','tertiaryColor':'#161616','edgeLabelBackground':'#555555','fontFamily':'Courier New, monospace'}}}%%
flowchart TB
    ME(("Karabo17-x"))
    ME --> DONE["[✔] Completed"]
    ME --> WIP["[~] In Progress"]

    DONE --> W1["Web Exploitation"]
    DONE --> W2["Network Attacks"]
    DONE --> W3["Privilege Escalation"]

    WIP --> P1["Advanced Malware Analysis"]
    WIP --> P2["CI/CD Pipeline Security"]
    WIP --> P3["Infrastructure as Code"]

    classDef root fill:#4a4a4a,stroke:#d0d0d0,stroke-width:2px,color:#ffffff,font-weight:bold;
    classDef done fill:#262626,stroke:#8a8a8a,stroke-width:2px,color:#e6e6e6;
    classDef wip fill:#262626,stroke:#8a8a8a,stroke-width:2px,stroke-dasharray:5 3,color:#e6e6e6;
    class ME root;
    class DONE,W1,W2,W3 done;
    class WIP,P1,P2,P3 wip;
```

---

##  Completed Programs

<p align="center">
  <img src="https://img.shields.io/badge/MWR%20CyberSec-Internship%20Completed-00ff41?style=for-the-badge&labelColor=000000" />
</p>

---

##  Current Project: SIEM Build

```mermaid
%%{init: {'theme':'base','themeVariables':{'background':'#0d1117','primaryColor':'#262626','primaryTextColor':'#e6e6e6','primaryBorderColor':'#8a8a8a','lineColor':'#b3b3b3','secondaryColor':'#262626','tertiaryColor':'#161616','edgeLabelBackground':'#555555','fontFamily':'Courier New, monospace'}}}%%
flowchart LR
    subgraph SRC["Log Sources"]
        direction TB
        L1["Linux / Syslog"]
        L2["AWS CloudTrail"]
        L3["Docker / App Logs"]
    end

    subgraph PIPE["Pipeline"]
        direction LR
        COL["Collector"] --> PAR["Parser &<br/>Normalizer"] --> STO[("Storage")]
    end

    subgraph DET["Detection & Response"]
        direction TB
        RUL["Detection Rules"] --> ALR["Alerts"]
        RUL --> DSH["Dashboards"]
    end

    SRC --> COL
    STO --> RUL

    classDef n fill:#262626,stroke:#8a8a8a,stroke-width:2px,color:#e6e6e6;
    class L1,L2,L3,COL,PAR,STO,RUL,ALR,DSH n;
    style SRC fill:#161616,stroke:#8a8a8a,stroke-dasharray:4 3,color:#e6e6e6
    style PIPE fill:#161616,stroke:#8a8a8a,stroke-dasharray:4 3,color:#e6e6e6
    style DET fill:#161616,stroke:#8a8a8a,stroke-dasharray:4 3,color:#e6e6e6
```

---

##  Threat Intel

<p align="center">
  <a href="https://tryhackme.com/karabocollenm">
    <img src="https://img.shields.io/badge/TryHackMe-Active-00ff41?style=for-the-badge&logo=tryhackme&logoColor=00ff41&labelColor=000000&color=000000" />
  </a>
  <a href="https://hackthebox.com/karabo17x">
    <img src="https://img.shields.io/badge/HackTheBox-Active-00ff41?style=for-the-badge&logo=hackthebox&logoColor=00ff41&labelColor=000000&color=000000" />
  </a>
</p>

---

##  Connect

<p align="center">
  <a href="https://github.com/karabo17-x">
    <img src="https://img.shields.io/badge/GitHub-karabo17--x-00ff41?style=for-the-badge&logo=github&logoColor=00ff41&labelColor=000000&color=000000" />
  </a>
</p>

---

```
> Attack to understand. Defend to protect. Automate to scale. REMEMBER TO REMEMBER.
```
