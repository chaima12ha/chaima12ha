<h1 align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=28&pause=1000&color=2E6DB4&center=true&vCenter=true&width=700&lines=Hi+%F0%9F%91%8B+I'm+Chaima+HAJJI;DevOps+%26+Cloud+Engineer;Kubernetes+%7C+CI%2FCD+%7C+GitOps+%7C+DevSecOps;Kafka+%7C+AWS+%7C+Terraform+%7C+KEDA" alt="Typing SVG" />
</h1>

<h3 align="center">🚀 DevOps & Cloud Engineer — Kubernetes · CI/CD · GitOps · DevSecOps · Kafka · AWS · Terraform</h3>

<p align="center">
  <a href="https://www.linkedin.com/in/hajjichaima?utm_source=share_via&utm_content=profile&utm_medium=member_android">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <a href="https://gitlab.com/hajjichaima962">
    <img src="https://img.shields.io/badge/GitLab-FC6D26?style=for-the-badge&logo=gitlab&logoColor=white" />
  </a>
  <a href="https://github.com/chaima12ha">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />
  </a>
  <a href="mailto:hajjichaima962@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
  <img src="https://img.shields.io/badge/Sousse%2C%20Tunisie-1B3A6B?style=for-the-badge&logo=googlemaps&logoColor=white" />
</p>

---

## 👩‍💻 About Me

🎓 **Mastère Professionnel** en Cloud Computing & Applications Distribuées — ISET Riadh Sousse *(Soutenance juin 2026)*  
🎓 **Licence** Technologie de l'Informatique — Mention Bien — ISET Riadh Sousse *(2024)*  
☁️ Passionnée par l'**automatisation intelligente**, la **sécurité DevSecOps** et l'**observabilité**  
🔭 En cours : conception d'une **plateforme Kubernetes Multicluster Cloud-Native** (AWS EKS + On-Premise)  
📍 Sousse, Tunisie

---

## 🏗️ Projet de Mémoire — Plateforme Kubernetes Multicluster Cloud-Native

> **Stack complète** combinant orchestration multicluster, streaming événementiel et automatisation intelligente.  
> 🗓️ *2024 – Juin 2026 · ISET Riadh Sousse · Soutenance prévue juin 2026*

### 🗺️ Architecture Globale

![Architecture Globale](./architecture_globale.png)

> *Architecture hybride On-Premise + AWS : CI/CD (GitLab + Jenkins), Cluster Kubernetes On-Premise, Amazon EKS (KEDA Scaling), Amazon EC2 (Kafka Cluster), Monitoring (Prometheus + Grafana), Orchestration & Remédiation intelligente (n8n + Groq API + MCP Server), Radar (Dashboard Cluster), k9s (CLI)*

### 🔄 Flux en 3 Phases

![Pipeline 3 Phases](./pipeline_phases.png)

> **Phase 1 (1–6)** — Pipeline CI/CD : Push GitLab → Jenkins Build/Test → DockerHub/Nexus → ArgoCD → Déploiement cluster On-Premise  
> **Phase 2 (7–17)** — Scaling hybride : K6 → HPA (CPU/RAM) → Kafka EC2 → KEDA EKS → Scale up/down automatique  
> **Phase 3 (18–22)** — Auto-remédiation intelligente : n8n → Groq API (LLM) → Résumé incident → MCP Server → kubectl apply/patch

### 📋 Stack Technique

| Domaine | Technologies |
|---|---|
| **CI/CD GitOps** | Jenkins + ArgoCD + Docker + Nexus/DockerHub |
| **Orchestration** | Kubernetes On-Premise (Kubespray + Ansible) + AWS EKS |
| **Autoscaling** | HPA (CPU/RAM) + KEDA (événementiel Kafka LAG) |
| **Streaming** | Apache Kafka KRaft multibroker sur AWS EC2 |
| **IaC** | Terraform (AWS EKS, EC2, VPC, IAM) |
| **Tests de charge** | K6 (VUs, RPS, latence P95) |
| **Monitoring** | Prometheus + Grafana + Alertmanager (Email & Slack) |
| **DevSecOps** | Falco (runtime) + Trivy (scan images) + SonarQube (SAST) |
| **Sécurité K8s** | RBAC, Network Policies, RoleBinding, ServiceAccount |
| **IA & Remédiation** | n8n + Groq API (LLM) + MCP Server (Actions Kubernetes) |
| **Dashboard & CLI** | Radar (Tableau de bord Cluster) + k9s |

---

## 🎓 Projets Universitaires

### 🔒 Sécurisation et isolation d'une architecture microservices sur Kubernetes
> *Sept. 2025 · Kubernetes (Kind), kubectl, YAML, Network Policies, RBAC, ServiceAccounts, NGINX*

- ✅ Déploiement de 3 microservices via Deployments et Services (NodePort/ClusterIP)
- ✅ Configuration de **Network Policies** pour limiter les flux entre pods (moindre privilège)
- ✅ Implémentation d'un modèle **RBAC** avec ServiceAccount, Role et RoleBinding
- ✅ Création d'un kubeconfig sécurisé avec token et tests d'accès restreints
- 🏆 **Résultat** : Architecture résiliente, isolation fonctionnelle, conformité aux bonnes pratiques Kubernetes

---

### 🔁 Pipeline CI/CD complet — Jenkins + Docker + Kubernetes + ArgoCD
> *Sept. 2025 · Jenkins, Docker, Kubernetes, ArgoCD, GitLab, Helm, SSH, MetalLB, GitOps*

- ✅ **CI avec Jenkins** : Build et push d'images Docker à chaque commit via Jenkinsfile
- ✅ **CD avec ArgoCD** : Déploiement automatique dans un cluster Kubernetes via Helm, synchronisation Git → cluster
- ✅ **Sécurité** : credentials Jenkins, clés SSH, configuration LoadBalancer avec MetalLB
- ✅ **Monitoring** : supervision des déploiements via dashboard ArgoCD et logs Jenkins

---

### ☸️ Projets DevOps / Cloud, CI/CD, Kubernetes & ArgoCD
> *Sept. 2025 · Kubernetes, ArgoCD, Jenkins, Docker, K6, HPA*

- ✅ **k8s-argo-mon-app** : configs Kubernetes, HPA (Horizontal Pod Autoscaler) + tests K6, synchronisation via ArgoCD
- ✅ **L2TProject** : pipeline Jenkins avec Jenkinsfile — build, création d'image Docker, push vers registre

---

### ⚡ Optimisation du Traitement Distribué — MPI vs Spark
> *Sept. 2025 · Python, Apache Spark (PySpark), MPI (mpi4py), Pandas, Streamlit, Ubuntu, SSH*

- ✅ Comparaison MPI vs Spark sur le **New York Taxi Dataset** (500M+ lignes)
- ✅ Algorithmes parallèles pour agrégation, nettoyage et analyse statistique
- ✅ Visualisation interactive via **Streamlit** + monitoring via Spark UI
- 🏆 **Résultat** : Spark surpasse MPI sur gros volumes grâce au traitement en mémoire et à la tolérance aux pannes

---

## 💼 Expériences Professionnelles

**🏢 Ingénieure DevOps & Cloud — Stage facultatif** · *LANDOLSI TELECOM TECHNOLOGY (L2T), Sousse* · `Juin – Juil. 2025`  
Provisionnement IaC (Vagrant + Proxmox), déploiement cluster Kubernetes, pipelines CI/CD Jenkins & GitLab CI/CD, monitoring Prometheus/Grafana + alertes.

**🏢 Stage Fin d'Études — Développement Web** · *Agence Sweet Touch, Sousse* · `Fév. – Mai 2024`  
Plateforme web de gestion de services et formations — Laravel, JavaScript, Chart.js, Pusher (temps réel), Bootstrap.

**🏢 Stage Perfectionnement** · *DRÄXMAIER (UATS), Sousse* · `Jan. – Fév. 2023`  
Application web de gestion des stagiaires — PHP, MySQL, Bootstrap.

**🏢 Stage d'Initiation** · *DRÄXMAIER Group, Sousse* · `Jan. – Fév. 2022`  
Initiation aux conteneurs Docker et à la configuration des équipements réseau.

---

## 🛠️ Tech Stack

### ☸️ Orchestration & Containers
<p>
  <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"/>
  <img src="https://img.shields.io/badge/Helm-0F1689?style=for-the-badge&logo=helm&logoColor=white"/>
  <img src="https://img.shields.io/badge/Rancher-0075A8?style=for-the-badge&logo=rancher&logoColor=white"/>
</p>

### 🔁 CI/CD & GitOps
<p>
  <img src="https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&logo=jenkins&logoColor=white"/>
  <img src="https://img.shields.io/badge/GitLab_CI-FC6D26?style=for-the-badge&logo=gitlab&logoColor=white"/>
  <img src="https://img.shields.io/badge/ArgoCD-EF7B4D?style=for-the-badge&logo=argo&logoColor=white"/>
  <img src="https://img.shields.io/badge/Nexus-1B74A8?style=for-the-badge&logo=sonatype&logoColor=white"/>
</p>

### ☁️ Cloud & IaC
<p>
  <img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white"/>
  <img src="https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white"/>
  <img src="https://img.shields.io/badge/Ansible-EE0000?style=for-the-badge&logo=ansible&logoColor=white"/>
  <img src="https://img.shields.io/badge/Vagrant-1868F2?style=for-the-badge&logo=vagrant&logoColor=white"/>
  <img src="https://img.shields.io/badge/Proxmox-E57000?style=for-the-badge&logo=proxmox&logoColor=white"/>
</p>

### 📊 Monitoring & Observabilité
<p>
  <img src="https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white"/>
  <img src="https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white"/>
  <img src="https://img.shields.io/badge/Alertmanager-E6522C?style=for-the-badge&logo=prometheus&logoColor=white"/>
</p>

### 🔐 Sécurité DevSecOps
<p>
  <img src="https://img.shields.io/badge/SonarQube-4E9BCD?style=for-the-badge&logo=sonarqube&logoColor=white"/>
  <img src="https://img.shields.io/badge/Trivy-1904DA?style=for-the-badge&logo=aquasecurity&logoColor=white"/>
  <img src="https://img.shields.io/badge/Falco-00AEC7?style=for-the-badge&logo=falco&logoColor=white"/>
</p>

### 📨 Streaming & Scaling
<p>
  <img src="https://img.shields.io/badge/Apache_Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white"/>
  <img src="https://img.shields.io/badge/KEDA-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white"/>
</p>

### 🤖 IA & Automatisation
<p>
  <img src="https://img.shields.io/badge/n8n-EA4B71?style=for-the-badge&logo=n8n&logoColor=white"/>
  <img src="https://img.shields.io/badge/Groq_API-F55036?style=for-the-badge&logo=groq&logoColor=white"/>
  <img src="https://img.shields.io/badge/MCP_Server-412991?style=for-the-badge&logo=openai&logoColor=white"/>
</p>

### 💻 Développement
<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white"/>
  <img src="https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white"/>
  <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white"/>
  <img src="https://img.shields.io/badge/.NET-512BD4?style=for-the-badge&logo=dotnet&logoColor=white"/>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"/>
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white"/>
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white"/>
</p>

---

## 🏅 Certifications

| Certification | Organisme | Date |
|---|---|---|
| 🏆 AWS Academy Graduate — Cloud Developing Training Badge | Amazon Web Services | Oct. 2025 |
| 🏆 AWS Academy Graduate — Cloud Foundations | Amazon Web Services | Avr. 2025 |
| 🏆 AWS Academy Graduate — Cloud Security Foundations | Amazon Web Services | Mars 2025 |

---

## 🌍 Langues

| Langue | Niveau |
|---|---|
| 🇹🇳 Arabe | Langue maternelle |
| 🇫🇷 Français | Courant |
| 🇬🇧 Anglais | Intermédiaire |

---

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=chaima12ha&show_icons=true&theme=tokyonight&hide_border=true" height="150"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=chaima12ha&layout=compact&theme=tokyonight&hide_border=true" height="150"/>
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=chaima12ha&theme=tokyonight&hide_border=true" />
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=chaima12ha&label=Profile%20views&color=2E6DB4&style=flat" />
</p>
