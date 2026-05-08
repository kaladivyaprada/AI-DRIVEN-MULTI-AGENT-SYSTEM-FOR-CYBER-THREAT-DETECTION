# 🛡️ SENTINEL GRAPH

## ⚡ AI-Driven Multi-Agent System for Real-Time Cyber Threat Detection

<div align="center">

![CyberSecurity](https://img.shields.io/badge/CyberSecurity-AI%20Driven-red?style=for-the-badge)
![n8n](https://img.shields.io/badge/Automation-n8n-orange?style=for-the-badge)
![LangGraph](https://img.shields.io/badge/Framework-LangGraph-blue?style=for-the-badge)
![Agents](https://img.shields.io/badge/Multi-Agent%20System-green?style=for-the-badge)
![RealTime](https://img.shields.io/badge/Monitoring-RealTime-purple?style=for-the-badge)

# 🚨 Intelligent Threat Correlation • Autonomous Agents • Real-Time Defense

</div>

---

# 🌌 PROJECT OVERVIEW

Modern cyber attacks are no longer isolated events.

A single attack can move through:

* 🌐 Network Infrastructure
* 💻 Host Systems
* 📱 Applications
* 🔐 Authentication Layers
* 📂 Sensitive Resources

Traditional SIEM systems often analyze these logs separately.
As a result:

❌ Threats remain hidden
❌ Detection becomes slow
❌ Alerts become noisy
❌ Security teams become overloaded

---

# 💡 THE SOLUTION

## Sentinel Graph

An AI-powered, stateful, multi-agent cybersecurity platform that:

✅ Monitors multiple log sources simultaneously
✅ Correlates suspicious events in real time
✅ Uses AI agents for intelligent analysis
✅ Detects coordinated cyber attacks
✅ Automates alerting and response workflows

---

# ⚡ CORE TECHNOLOGIES

| Technology          | Purpose                                   |
| ------------------- | ----------------------------------------- |
| n8n                 | Workflow Automation & Agent Orchestration |
| LangGraph           | Stateful Multi-Agent Execution            |
| LangSmith           | Observability & Agent Tracing             |
| Suricata IDS        | Network Threat Monitoring                 |
| Docker              | Sandboxed Response Execution              |
| SQLite / PostgreSQL | Persistent State Storage                  |
| Scikit-learn        | AI Threat Detection                       |
| Python              | Agent & ML Logic                          |

---

# 🧠 CORE IDEA

## “Multiple Intelligent Agents Working Together as One Cyber Defense Brain.”

Instead of one monolithic security system, Sentinel Graph uses specialized autonomous agents.

Each agent:

* Monitors one security domain
* Makes independent decisions
* Shares intelligence with other agents
* Collaborates to identify hidden attack patterns

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
```

---

# 🤖 MULTI-AGENT SYSTEM

## 🌐 Network Agent

Responsible for:

* Detecting port scans
* Monitoring malicious IPs
* Identifying traffic anomalies
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

Unlike traditional cybersecurity systems that require heavy backend coding, Sentinel Graph uses:

# ⚡ n8n Workflow Automation

This enables:

✅ Visual agent orchestration
✅ Real-time event pipelines
✅ Automated workflow execution
✅ API integrations
✅ Low-code scalability
✅ Faster deployment

---

# 🧩 LANGGRAPH STATEFUL ORCHESTRATION

LangGraph acts as the system’s “brain.”

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

Edges define routing logic.

Example:

```text
Benign Event → Ignore
Suspicious Event → Correlation Engine
Critical Threat → Response Agent
```

---

# 🔗 EVENT CORRELATION ENGINE

The platform correlates suspicious events from multiple sources.

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
✅ Behavior Analysis

---

# 📡 REAL-TIME VISUALIZATION

## LangGraph Studio Frontend

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

## 🐳 Sandboxed Execution

Automated response actions run inside Docker containers.

This prevents:

* Host system damage
* Unsafe automation
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

# LangSmith

Provides:

* Agent tracing
* Workflow monitoring
* Threat auditing
* Forensic analysis

---

# ⚡ AUTOMATED RESPONSE SYSTEM

| Threat Level | Automated Response           |
| ------------ | ---------------------------- |
| Low          | Log Event                    |
| Medium       | Alert Security Team          |
| High         | Trigger n8n Workflow         |
| Critical     | Human Approval + Containment |

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


## Real-Time AI Cyber Defense Powered by Multi-Agent Intelligence

⚡ Detect • Correlate • Analyze • Respond ⚡

</div>
