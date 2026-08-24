<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=190&section=header&text=Anjali%20Priya&fontSize=55&fontAlignY=35&desc=Software%20Engineer%20%E2%80%A2%20Platform%20Engineering%20%E2%80%A2%20Cloud%20Native%20%E2%80%A2%20AI&descSize=16&descAlignY=58&animation=fadeIn" width="100%"/>

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=19&duration=2800&pause=900&color=36BCF7&center=true&vCenter=true&width=850&lines=Software+Engineer+who+likes+building+systems.;Python+%E2%80%A2+Go+%E2%80%A2+Infrastructure+%E2%80%A2+Cloud;From+APIs+to+distributed+infrastructure.;Automate.+Scale.+Observe.+Improve.;Currently+exploring+AI+%C3%97+Infrastructure." />

<br/>

![Profile Views](https://komarev.com/ghpvc/?username=AnjaliPriyaa\&style=for-the-badge\&color=0891b2)
![Followers](https://img.shields.io/github/followers/AnjaliPriyaa?style=for-the-badge\&color=0891b2\&label=Followers)

</div>

---

## `~/about-me $ whoami`

```python id="1dwxfs"
class SoftwareEngineer:
    def __init__(self):
        self.name = "Anjali Priya"

        self.languages = [
            "Python",
            "Go",
            "Bash",
            "JavaScript"
        ]

        self.engineering = [
            "Software Engineering",
            "Platform Engineering",
            "Infrastructure Engineering",
            "Cloud Native Systems",
            "DevSecOps",
            "AI Systems"
        ]

        self.currently_exploring = [
            "Distributed Systems",
            "AI Infrastructure",
            "Agentic Systems"
        ]

    def philosophy(self):
        return "Understand it → Build it → Automate it → Make it reliable"
```

I’m a **Software Engineer who enjoys building systems and understanding how things work underneath**.

My work spans software development, infrastructure automation, cloud-native platforms, APIs, developer tooling, security, and reliability.

I primarily work with **Python and Go**, and I enjoy problems where software has to interact with real infrastructure.

---

# ⚡ Engineering, End to End

What interests me isn't one particular tool.

It's the entire path from **code → system → production**.

```text id="w8uwco"
                        ┌─────────────────┐
                        │      CODE       │
                        │   Python / Go   │
                        └────────┬────────┘
                                 │
                                 ▼
                        ┌─────────────────┐
                        │ APIs & Tooling  │
                        └────────┬────────┘
                                 │
                                 ▼
                  ┌─────────────────────────┐
                  │ Automation & Platforms  │
                  └────────────┬────────────┘
                               │
              ┌────────────────┼────────────────┐
              ▼                ▼                ▼
        Infrastructure     Containers        CI / CD
              │                │                │
              └────────────────┼────────────────┘
                               ▼
                    ┌─────────────────────┐
                    │ Production Systems  │
                    └──────────┬──────────┘
                               │
                    ┌──────────┼──────────┐
                    ▼          ▼          ▼
                Security   Reliability  Observability
```

---

# 🧩 What I Can Engineer

### `01. software`

I write software and automation primarily using **Python and Go**.

My work includes:

* APIs and integrations
* Infrastructure tooling
* Automation frameworks
* CLI-style tooling
* Data and configuration processing
* Health-check and validation systems
* Concurrent infrastructure operations
* LLM-powered workflows

```python id="yccfzi"
def engineer(problem):
    context = understand(problem)
    solution = design(context)
    system = build(solution)
    validate(system)
    return improve(system)
```

`Python` `Go` `Bash` `JavaScript` `REST APIs` `MySQL` `Kafka`

---

### `02. infrastructure`

I build software that **creates and controls infrastructure**.

```text id="0nb53n"
                    Desired State
                         │
                         ▼
                  ┌─────────────┐
                  │  Terraform  │
                  └──────┬──────┘
                         │
             ┌───────────┼───────────┐
             ▼           ▼           ▼
          Compute     Network      Platform
             │           │           │
             └───────────┼───────────┘
                         ▼
                   Actual State
```

My experience includes infrastructure provisioning, reusable IaC components, configuration management, infrastructure lifecycle operations, policy enforcement, and cloud automation.

`Terraform` `Ansible` `Packer` `Sentinel` `AWS` `Azure` `OCI`

---

### `03. platforms`

I work on the layer that allows applications and engineers to interact with infrastructure reliably.

```text id="kk6mhs"
Developer
    │
    ▼
┌───────────────┐
│ Platform/API  │
└───────┬───────┘
        │
        ▼
┌───────────────┐
│  Automation   │
└───────┬───────┘
        │
        ▼
┌───────────────────────────┐
│ Kubernetes / OpenShift    │
└───────────────┬───────────┘
                │
                ▼
         Infrastructure
```

`Kubernetes` `OpenShift` `Docker` `EKS` `Tekton`

---

### `04. delivery`

For me, engineering doesn't stop when the code works locally.

```text id="fr9sok"
git push
   │
   ▼
 Build
   │
   ▼
 Test
   │
   ▼
 Scan ───────X vulnerability
   │
   ▼
 Validate
   │
   ▼
 Deploy
   │
   ▼
 Verify
   │
   ▼
 Observe
```

I build and improve CI/CD workflows around application and infrastructure delivery.

`GitHub Actions` `Jenkins` `Tekton` `Harness`

---

### `05. security`

Security should be part of the system rather than something added before release.

```text id="x7pp2g"
                 CODE
                  │
        ┌─────────┼─────────┐
        ▼         ▼         ▼
       SCA      Image     Policy
                Scan      Check
        │         │         │
        └─────────┼─────────┘
                  ▼
              Validate
                  │
              ┌───┴───┐
              ▼       ▼
            PASS     FAIL
              │       │
           Deploy    Fix
```

`SCA` `Container Security` `Trivy` `BlackDuck` `Aqua Security` `Veracode` `JFrog Xray`

---

### `06. reliability`

I care about what happens **after deployment**.

```text id="j77ykk"
                  Production
                      │
          ┌───────────┼───────────┐
          ▼           ▼           ▼
       Metrics       Logs      Health Checks
          │           │           │
          └───────────┼───────────┘
                      ▼
                    Detect
                      │
                      ▼
                   Diagnose
                      │
                      ▼
                    Recover
```

`Dynatrace` `Splunk` `Monitoring` `Logging` `Runtime Validation`

---

# 🧠 The Kind of Problems I Like

```text id="ikjtkb"
"Can we automate this?"
          │
          ▼
"Can we make it reusable?"
          │
          ▼
"Can we make it scale?"
          │
          ▼
"How does it fail?"
          │
          ▼
"Can we detect that failure?"
          │
          ▼
"Can the system recover?"
```

Those questions are what pull me toward **software engineering, infrastructure, distributed systems, and reliability engineering**.

---

# 🤖 Now Exploring: AI × Systems

AI gets much more interesting to me when it moves beyond a chat interface.

```text id="szvgmc"
                     User / System
                          │
                          ▼
                   ┌─────────────┐
                   │ LLM / Agent │
                   └──────┬──────┘
                          │
                     Reason / Plan
                          │
          ┌───────────────┼───────────────┐
          ▼               ▼               ▼
        APIs             Tools       Infrastructure
          │               │               │
          └───────────────┼───────────────┘
                          ▼
                       Execute
                          │
                          ▼
                       Observe
                          │
                          ▼
                       Reason
```

I'm exploring engineering problems around:

**Agentic Systems** · **AI Infrastructure** · **Distributed Systems** · **LLM Applications** · **Tool Calling** · **AI Automation** · **LLM Observability**

The question that interests me:

> **How do we build AI systems that can safely interact with and reason about real infrastructure?**

---

# 🛠️ `~/toolbox`

<div align="center">

### Languages

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge\&logo=python\&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge\&logo=go\&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge\&logo=gnubash\&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge\&logo=javascript\&logoColor=black)

### Infrastructure & Platforms

![Terraform](https://img.shields.io/badge/Terraform-844FBA?style=for-the-badge\&logo=terraform\&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge\&logo=kubernetes\&logoColor=white)
![OpenShift](https://img.shields.io/badge/OpenShift-EE0000?style=for-the-badge\&logo=redhatopenshift\&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge\&logo=docker\&logoColor=white)
![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=for-the-badge\&logo=ansible\&logoColor=white)

### Cloud

![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge\&logo=amazonwebservices\&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=for-the-badge\&logo=microsoftazure\&logoColor=white)
![OCI](https://img.shields.io/badge/OCI-F80000?style=for-the-badge\&logo=oracle\&logoColor=white)

### Engineering

![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge\&logo=linux\&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge\&logo=git\&logoColor=white)
![Kafka](https://img.shields.io/badge/Kafka-231F20?style=for-the-badge\&logo=apachekafka\&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge\&logo=mysql\&logoColor=white)

</div>

---

# 📊 `git stats`

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=AnjaliPriyaa&show_icons=true&theme=transparent&hide_border=true&rank_icon=github" height="165"/>

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=AnjaliPriyaa&layout=compact&theme=transparent&hide_border=true&langs_count=8" height="165"/>

</div>

---

<div align="center">

## `> let's build something`

I like connecting with people working on **software engineering, infrastructure, distributed systems, platform engineering, open source, and AI systems.**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Anjali_Priya-0077B5?style=for-the-badge\&logo=linkedin\&logoColor=white)](https://www.linkedin.com/in/anjalipriya24/)
[![GitHub](https://img.shields.io/badge/GitHub-AnjaliPriyaa-181717?style=for-the-badge\&logo=github)](https://github.com/AnjaliPriyaa)
[![Medium](https://img.shields.io/badge/Medium-Writing-000000?style=for-the-badge\&logo=medium)](https://medium.com/@anjalipriya_)

<br/><br/>

```text id="1yd36h"
Software Engineer
     ↓
Build systems
     ↓
Understand systems
     ↓
Automate systems
     ↓
Make systems better
     ↓
repeat()
```

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=100&section=footer" width="100%"/>

</div>
