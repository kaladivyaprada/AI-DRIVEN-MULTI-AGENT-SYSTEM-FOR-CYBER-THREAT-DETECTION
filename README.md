````md id="6lj0z0"
<div align="center">

# 🛡️ SENTINEL GRAPH
## ⚡ AI-Driven Multi-Agent System for Cyber Threat Detection

<img src="https://img.shields.io/badge/CyberSecurity-AI%20Driven-red?style=for-the-badge"/>
<img src="https://img.shields.io/badge/n8n-Automation-orange?style=for-the-badge"/>
<img src="https://img.shields.io/badge/LangGraph-Stateful%20Agents-blue?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Multi-Agent-System-green?style=for-the-badge"/>
<img src="https://img.shields.io/badge/RealTime-Threat%20Detection-purple?style=for-the-badge"/>

### 🚨 Intelligent Threat Correlation • Autonomous Agents • Real-Time Defense

---

### 🧠 Detect • Correlate • Analyze • Respond

</div>

---

# 🌌 PROJECT OVERVIEW

Modern cyber attacks are no longer isolated incidents.

A single attack can spread through:
- 🌐 Networks
- 💻 Systems
- 📱 Applications
- 🔐 Authentication Services
- 📂 Sensitive Resources

Traditional monitoring systems analyze logs separately, making it difficult to identify coordinated cyber attacks.

This leads to:
- ❌ Delayed detection
- ❌ High alert noise
- ❌ Missed attack patterns
- ❌ Increased manual monitoring effort

---

# 💡 THE SOLUTION

## 🛡️ Sentinel Graph

Sentinel Graph is an **AI-powered multi-agent cybersecurity platform** that:

✅ Monitors multiple log sources simultaneously  
✅ Correlates suspicious events in real time  
✅ Uses intelligent AI agents for analysis  
✅ Detects coordinated cyber attacks  
✅ Automates alerts and response workflows  

---

# ⚡ CORE TECHNOLOGIES

| Technology | Purpose |
|---|---|
| 🔶 n8n | Workflow Automation & Agent Orchestration |
| 🧠 LangGraph | Stateful Multi-Agent Execution |
| 🔍 LangSmith | Agent Observability & Tracing |
| 🌐 Suricata IDS | Network Threat Monitoring |
| 🐳 Docker | Sandboxed Response Execution |
| 🗄️ SQLite / PostgreSQL | Persistent State Storage |
| 🤖 Scikit-learn | AI Threat Detection |
| 🐍 Python | ML & Agent Logic |

---

# 🧠 CORE IDEA

## “Multiple Intelligent Agents Working Together as One Cyber Defense Brain.”

Instead of a monolithic security system, Sentinel Graph uses specialized autonomous agents.

Each agent:
- Monitors one security domain
- Makes independent decisions
- Shares intelligence with other agents
- Collaborates to detect hidden threats

---

# ⚙️ SYSTEM ARCHITECTURE

```text
                    ┌───────────────────────────┐
                    │     Log Sources           │
                    │───────────────────────────│
                    │ 🌐 Network Logs           │
                    │ 💻 System Logs            │
                    │ 📱 Application Logs       │
                    └────────────┬──────────────┘
                                 │
                                 ▼
                 ┌──────────────────────────────┐
                 │      Preprocessing Layer     │
                 │──────────────────────────────│
                 │ ✔ Cleaning                   │
                 │ ✔ Normalization              │
                 │ ✔ Feature Extraction         │
                 └────────────┬─────────────────┘
                              │
                              ▼
             ┌────────────────────────────────────┐
             │       Multi-Agent Monitoring       │
             │────────────────────────────────────│
             │ 🌐 Network Agent                  │
             │ 💻 System Agent                   │
             │ 📱 Application Agent              │
             └────────────┬──────────────────────┘
                          │
                          ▼
             ┌────────────────────────────────────┐
             │      Event Correlation Engine      │
             │────────────────────────────────────│
             │ Detect Multi-Stage Attacks         │
             │ Correlate Cross-Source Events      │
             └────────────┬──────────────────────┘
                          │
                          ▼
             ┌────────────────────────────────────┐
             │      AI Threat Detection Layer     │
             │────────────────────────────────────│
             │ ✔ ML Threat Scoring                │
             │ ✔ Anomaly Detection                │
             │ ✔ Risk Classification              │
             └────────────┬──────────────────────┘
                          │
                          ▼
             ┌────────────────────────────────────┐
             │   Automated Alert & Response       │
             │────────────────────────────────────│
             │ 📧 Email Alerts                    │
             │ ⚡ n8n Workflows                   │
             │ 🚫 Containment Actions             │
             └────────────────────────────────────┘
````

---

# 🤖 MULTI-AGENT SYSTEM

---

## 🌐 Network Agent

Responsible for:

* Detecting port scans
* Monitoring malicious IPs
* Identifying abnormal traffic
* Detecting suspicious packets

---

## 💻 System Agent

Responsible for:

* Login monitoring
* Privilege escalation detection
* File access tracking
* Suspicious process detection

---

## 📱 Application Agent

Responsible for:

* SQL injection detection
* Failed login monitoring
* API abuse detection
* Session anomaly tracking

---

## 🔗 Correlation Agent

Combines related events from:

* Network logs
* System logs
* Application logs

Detects:

* Coordinated attacks
* Multi-stage intrusions
* Hidden attack sequences

---

## 🧠 Analyst Agent

Uses AI/ML models to:

* Calculate threat scores
* Detect anomalies
* Predict malicious behavior
* Prioritize incidents

---

## 🚨 Response Agent

Automatically:

* Generates alerts
* Sends notifications
* Triggers workflows
* Executes containment actions

---

# 🔥 WHY n8n?

Unlike traditional cybersecurity systems that rely heavily on backend coding, Sentinel Graph uses:

# ⚡ n8n Workflow Automation

This enables:

✅ Visual workflow orchestration
✅ Real-time event pipelines
✅ Automated workflow execution
✅ API integrations
✅ Low-code scalability
✅ Faster deployment

---

# 🧩 LANGGRAPH STATEFUL ORCHESTRATION

LangGraph acts as the system’s intelligent orchestration brain.

---

## 🔹 STATE

Stores:

* Current logs
* Threat history
* Agent decisions
* Risk scores
* Event memory

This shared state allows all agents to collaborate intelligently.

---

## 🔹 NODES

Each node represents an AI agent.

Examples:

* Network Monitor Node
* Correlation Node
* Analyst Node
* Response Node

---

## 🔹 EDGES

Edges define workflow routing logic.

```text
Benign Event → Ignore
Suspicious Event → Correlation Engine
Critical Threat → Response Agent
```

---

# 🔗 EVENT CORRELATION ENGINE

The platform correlates suspicious activities from multiple sources.

## Example Attack Flow

```text
Port Scan
   ↓
Failed Login Attempts
   ↓
Privilege Escalation
   ↓
Unauthorized File Access
   ↓
🚨 Multi-Stage Attack Detected
```

---

# 🧠 AI THREAT DETECTION

The AI engine performs:

✅ Threat Classification
✅ Risk Scoring
✅ Anomaly Detection
✅ Pattern Recognition
✅ Behavioral Analysis

---

# 📡 REAL-TIME VISUALIZATION

## 🖥️ LangGraph Studio Frontend

Sentinel Graph includes an interactive frontend where:

### 🔴 Live Agent Activity

Nodes glow as agents process threats in real time.

---

### 🧠 Streaming Reasoning

Users can watch:

* Why a threat was flagged
* Which events triggered detection
* How the agents made decisions

---

### ⏪ Time Travel Debugging

Developers can:

* Rewind executions
* Modify agent logic
* Replay attack scenarios

---

# 🛡️ SECURITY & SAFETY

---

## 🐳 Sandboxed Execution

Automated response actions run inside Docker containers.

This prevents:

* Unsafe automation
* Host system damage
* Accidental containment errors

---

## 💾 Persistent Memory

The system stores:

* Threat history
* Workflow checkpoints
* Agent execution states

Using:

* SQLite
* PostgreSQL

---

## 🔍 FULL OBSERVABILITY

Integrated with:

# 🔍 LangSmith

Provides:

* Agent tracing
* Workflow monitoring
* Threat auditing
* Forensic analysis

---

# ⚡ AUTOMATED RESPONSE SYSTEM

| Threat Level | Automated Response           |
| ------------ | ---------------------------- |
| 🟢 Low       | Log Event                    |
| 🟡 Medium    | Alert Security Team          |
| 🔴 High      | Trigger n8n Workflow         |
| 🚨 Critical  | Human Approval + Containment |

---

# 📂 PROJECT STRUCTURE

```text
Sentinel-Graph/
│
├── agents/
│   ├── network_agent
│   ├── system_agent
│   ├── app_agent
│   ├── analyst_agent
│   └── response_agent
│
├── workflows/
│   ├── n8n_flows
│   ├── automation_rules
│   └── alert_workflows
│
├── correlation_engine/
│
├── ml_models/
│
├── logs/
│
├── docker/
│
├── frontend/
│
└── README.md
```

---

# 🚀 EXECUTION PIPELINE

```text
1️⃣ Log Collection
        ↓
2️⃣ Data Preprocessing
        ↓
3️⃣ Multi-Agent Monitoring
        ↓
4️⃣ Event Correlation
        ↓
5️⃣ AI Threat Analysis
        ↓
6️⃣ Alert Generation
        ↓
7️⃣ Automated Response
```

---

# 🔍 DETECTED THREATS

Sentinel Graph can detect:

✅ Brute Force Attacks
✅ SQL Injection Attempts
✅ Malware Activity
✅ Unauthorized Access
✅ Privilege Escalation
✅ Insider Threats
✅ Suspicious Network Traffic
✅ Multi-Stage Coordinated Attacks

---

# 🎨 INTERACTIVE DASHBOARD FEATURES

📡 Real-Time Threat Feed
🧠 Agent Decision Streams
📊 Threat Severity Charts
🔗 Correlation Graphs
⚡ Workflow Status
🚨 Alert Notifications

---

# ☁️ DEPLOYMENT OPTIONS

---

## 🖥️ Self Hosting

Deploy using:

* Docker Containers
* LangGraph Server
* Local Infrastructure

---

## ☁️ Production Deployment

Supports:

* Distributed Agents
* Enterprise Monitoring
* Cloud Infrastructure
* Horizontal Scaling

---

# 🔮 FUTURE ENHANCEMENTS

🚀 Deep Learning Integration
🚀 Zero-Day Threat Detection
🚀 Cloud Security Monitoring
🚀 Kubernetes Deployment
🚀 SOAR Integration
🚀 IoT Threat Monitoring
🚀 AI Threat Prediction
🚀 Real-Time Analytics Dashboard

---

# 👨‍💻 TEAM MEMBERS

| Name          | USN        |
| ------------- | ---------- |
| Chaitra N     | 1SI23AD009 |
| Greeshma S    | 1SI23AD013 |
| Pooja Prakash | 1SI23AD036 |
| Divyaprada G  | 1SI24AD401 |

---

# 🎓 INSTITUTION

## Siddaganga Institute of Technology, Tumakuru

Department of Artificial Intelligence & Data Science Engineering
Academic Year: 2025-26
