<div align="center">

# SHIVA KUMAR KAVALI

### AI/ML Engineer • Cloud & Distributed Systems • Backend Engineering

Building intelligent, scalable systems with Machine Learning, Backend Engineering, Cloud Infrastructure, and Distributed Systems.

[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/shiva-kumar-1319)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/shiva-kumar-kavali-b200342a7/)
[![LeetCode](https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black)](https://leetcode.com/u/shivakumarnaidu/)
[![Codeforces](https://img.shields.io/badge/Codeforces-1F8ACB?style=for-the-badge&logo=codeforces&logoColor=white)](https://codeforces.com/profile/Kavali_Shiva_Kumar_Naidu)
[![CodeChef](https://img.shields.io/badge/CodeChef-5B4638?style=for-the-badge&logo=codechef&logoColor=white)](https://www.codechef.com/users/shivakumar1319)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:shivakumar867df@gmail.com)

</div>

<br>

<div align="center">

| 🎓 B.Tech | 🤖 AI/ML | ☁️ Cloud |
|:---:|:---:|:---:|
| AI & ML, MVSREC | ML Engineering | Docker · Kubernetes |

| 💻 DSA | 🚀 Projects | 🏆 Achievements |
|:---:|:---:|:---:|
| 500+ LeetCode | Cloud + AI Systems | Amazon MLSS · Top 10 National |

</div>

<br>

## 🧑‍💻 About Me

I'm a B.Tech AI & Machine Learning student building production-style systems that sit at the intersection of ML, backend engineering, and cloud infrastructure. I like taking a system past the "it works on my machine" stage — wiring up observability, containerizing services, and thinking about failure modes, not just the happy path.

Recent focus areas:

- 🔁 Self-healing infrastructure — combining ML anomaly detection with automated Kubernetes remediation
- 🧠 Retrieval-augmented systems — document QA and research assistants built on LangChain, FAISS, and LLM APIs
- ☁️ Cloud-native architecture — microservices, message queues, Infrastructure as Code
- 🧮 Strengthening DSA and systems fundamentals through consistent competitive programming

<br>

## 🛠️ Tech Stack

**Languages**

![Python](https://skillicons.dev/icons?i=python) ![SQL](https://skillicons.dev/icons?i=mysql) ![JS](https://skillicons.dev/icons?i=js)

**AI / Machine Learning**

![PyTorch](https://skillicons.dev/icons?i=pytorch) ![TensorFlow](https://skillicons.dev/icons?i=tensorflow) ![Scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white) ![Pandas](https://skillicons.dev/icons?i=pandas) ![NumPy](https://skillicons.dev/icons?i=numpy) ![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black) ![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white) ![FAISS](https://img.shields.io/badge/FAISS-4285F4?style=flat-square&logo=meta&logoColor=white)

**Backend**

![FastAPI](https://skillicons.dev/icons?i=fastapi) ![Flask](https://skillicons.dev/icons?i=flask) ![PostgreSQL](https://skillicons.dev/icons?i=postgres) ![RabbitMQ](https://skillicons.dev/icons?i=rabbitmq)

**Cloud / DevOps**

![Docker](https://skillicons.dev/icons?i=docker) ![Kubernetes](https://skillicons.dev/icons?i=kubernetes) ![Terraform](https://skillicons.dev/icons?i=terraform) ![AWS](https://skillicons.dev/icons?i=aws) ![GitHubActions](https://skillicons.dev/icons?i=githubactions) ![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white) ![Grafana](https://skillicons.dev/icons?i=grafana)

**Development**

![Git](https://skillicons.dev/icons?i=git) ![GitHub](https://skillicons.dev/icons?i=github) ![Linux](https://skillicons.dev/icons?i=linux)

<br>

## 🚀 Featured Projects

<table>
<tr>
<td width="50%" valign="top">

### ☁️ CloudPulse
**Self-Healing Cloud-Native Microservices Platform**

`FastAPI` `PostgreSQL` `RabbitMQ` `Docker` `Kubernetes` `Terraform` `Prometheus` `Grafana` `Isolation Forest`

A microservices platform (auth, order, inventory services) where an ML anomaly detector watches Prometheus telemetry in real time. When latency spikes or error rates cross a threshold, a Remediation Controller validates safety guardrails (confidence threshold, cooldown window, rate limits) and calls the Kubernetes API to recycle or scale pods — closing the loop from detection to recovery automatically.

```
Microservices → RabbitMQ → Prometheus
   → ML Anomaly Detection (Isolation Forest)
   → Remediation Controller → Kubernetes API → Recovery
```

**[Repository →](https://github.com/shiva-kumar-1319/CloudPulse)**

</td>
<td width="50%" valign="top">

### 🧠 NeuralQuery
**AI Research Assistant**

`Flask` `PostgreSQL` `Gemini 2.0 Flash` `JWT` `REST`

A research assistant backend with JWT (HS256) authentication, bcrypt password hashing, and 10+ REST endpoints across a 4-table indexed schema, deployed on Render. Answers research queries via Gemini 2.0 Flash with ~79–85% accuracy across test queries.

⭐ 10+ REST API endpoints, 4-table schema with 7 indexes
⭐ JWT + bcrypt authentication
⭐ Deployed and reachable on Render

**[Repository →](https://github.com/shiva-kumar-1319)**

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 📄 IDQS — Intelligent Document Query System
**Multi-PDF Conversational Retrieval**

`LangChain` `FAISS` `flan-t5-base`

A document QA system built on LangChain's ConversationalRetrievalChain, using a FAISS vectorstore over `flan-t5-base` embeddings. Chunks documents with a CharacterTextSplitter (size 1000, overlap 200) and supports querying across up to 5 PDFs simultaneously — validated across 20–30 test queries.

⭐ Multi-document (up to 5 PDFs) conversational retrieval
⭐ Tuned chunking strategy for retrieval quality

**[Repository →](https://github.com/shiva-kumar-1319)**

</td>
<td width="50%" valign="top">

### 🐾 Animal Keypoint Estimation Suite
**Real-Time 2D Skeletal Keypoint Detection**

`YOLOv8` `RTMPose` `ONNX`

Browser-based real-time 2D skeletal keypoint detection for quadruped animals (cats, dogs, cows, horses, sheep), using a YOLOv8-nano + RTMPose-Medium ONNX pipeline with AP-10K → Animal-Pose 20-joint schema mapping.

⭐ Runs in-browser in real time
⭐ Generalized across 5 animal species via a shared joint schema

**[Repository →](https://github.com/shiva-kumar-1319)**

</td>
</tr>
</table>

<br>

## 🧠 Competitive Programming & DSA

<div align="center">

| 🟡 LeetCode | 🔵 Codeforces | 🟠 CodeChef |
|:---:|:---:|:---:|
| 500+ problems solved | ~1200 rating (peak ~1255, Pupil) | 3★ rated |
| [View Profile →](https://leetcode.com/u/shivakumarnaidu/) | [View Profile →](https://codeforces.com/profile/Kavali_Shiva_Kumar_Naidu) | [View Profile →](https://www.codechef.com/users/shivakumar1319) |

</div>

<br>

## 🏆 Achievements

**🏆 Amazon ML Summer School 2026**
Selected among the Top 3,000 participants nationwide. Focused on core machine learning concepts and applied technical learning.

**🏆 Visionary Hackathon 2.0 (Mercer Mettl / Xathon)**
Top 10 finish nationally — submitted AuraAssess, a WebXR-based project.

**📜 Certifications**
- AWS Academy AI-ML (AICTE EduSkills National Internship Program)
- Infosys Springboard — Natural Language Processing for Developers
- Oracle Java Foundations (Oct 2024)
- Oracle Database Programming with SQL (Nov 2024)

<br>

## 🔭 Currently Building

```
☁️  Cloud-native systems with ML-powered monitoring
☸️  Kubernetes automation and self-healing infrastructure
🧠  Applied Machine Learning for real-world backend systems
⚙️  Distributed systems fundamentals
```

## 📚 Currently Learning

`Distributed Systems` · `System Design` · `Kubernetes` · `MLOps` · `Cloud Architecture` · `Advanced ML` · `DSA`

<br>

## 📊 GitHub Stats

<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=shiva-kumar-1319&show_icons=true&theme=tokyonight&hide_border=true&count_private=true)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=shiva-kumar-1319&layout=compact&theme=tokyonight&hide_border=true)

![Streak Stats](https://github-readme-streak-stats.herokuapp.com/?user=shiva-kumar-1319&theme=tokyonight&hide_border=true)

</div>

<br>

## 🤝 Let's Connect

Interested in AI/ML, Cloud Engineering, Distributed Systems, Backend Engineering, Research, Internships, and collaborative projects.

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/shiva-kumar-kavali-b200342a7/)
[![Email](https://img.shields.io/badge/Email-Reach%20Out-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:shivakumar867df@gmail.com)

</div>
