# 🛡️ Sentinel — AI-Assisted Hybrid Threat Intelligence Platform

<p align="center">

<strong>Narrative Analysis · Risk Scoring · Anomaly Detection · Interactive Threat Visualization</strong>

<br><br>

<a href="https://mariosvard.github.io/Sentinel-AI-Assisted-Hybrid-Threat-Intelligence-Platform/">
<img src="https://img.shields.io/badge/Live-Demo-success?style=for-the-badge" alt="Live Demo">
</a>
<a href="https://github.com/mariosvard/Sentinel-AI-Assisted-Hybrid-Threat-Intelligence-Platform">
<img src="https://img.shields.io/badge/GitHub-Repository-black?style=for-the-badge&logo=github" alt="GitHub">
</a>
<a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript">
<img src="https://img.shields.io/badge/JavaScript-ES6+-yellow?style=for-the-badge&logo=javascript" alt="JavaScript">
</a>
<a href="https://d3js.org/">
<img src="https://img.shields.io/badge/D3.js-Visualization-orange?style=for-the-badge&logo=d3.js" alt="D3.js">
</a>
<a href="https://pages.github.com/">
<img src="https://img.shields.io/badge/Deployed-GitHub%20Pages-blue?style=for-the-badge&logo=github" alt="GitHub Pages">
</a>

</p>

---

## 🚀 Live Demo

### [▶️ Launch Sentinel](https://mariosvard.github.io/Sentinel-AI-Assisted-Hybrid-Threat-Intelligence-Platform/)

Sentinel is an **AI-assisted Hybrid Threat Intelligence proof-of-concept** designed to support the identification, prioritization, and investigation of potentially coordinated or suspicious activity across heterogeneous intelligence signals.

The platform uses **synthetic intelligence scenarios** and focuses on transparent, explainable analytical logic rather than autonomous attribution or operational decision-making.

---

## 📌 Overview

Hybrid threats can involve combinations of:

- Coordinated narrative amplification
- Unusual engagement patterns
- Bot-like account behavior
- Suspicious URLs
- Repeated or coordinated indicators
- Sentiment-related signals
- Cross-platform activity

These signals can be difficult to interpret when examined independently.

**Sentinel combines these signals into a unified analytical workflow** that allows an analyst to explore, filter, prioritize, and visualize potentially relevant intelligence.

### Core Workflow

```text
Intelligence Dataset
        ↓
Feature Extraction
        ↓
Threat Signal Analysis
        ↓
Risk Scoring
        ↓
Interactive Filtering & Visualization
        ↓
Human Analyst Interpretation
```

---

# 🎯 Objectives

Sentinel is designed to support analysts in:

- 🔎 Identifying potentially suspicious activity
- ⚠️ Prioritizing higher-risk intelligence records
- 📈 Detecting unusual engagement patterns
- 🧩 Combining heterogeneous threat indicators
- 🧠 Exploring narrative and sentiment signals
- 🕸️ Investigating relationships between narratives, accounts, and indicators
- 📊 Understanding temporal activity patterns
- 👨‍💻 Supporting human-led Threat Intelligence analysis

The primary objective is **early triage and situational awareness**, rather than automated attribution.

---

# 🧠 Key Capabilities

## 1. Risk Scoring

Sentinel calculates a transparent composite risk score from multiple intelligence signals.

The current model considers:

- Bot score
- Engagement anomaly
- Sentiment weight
- Suspicious keyword score
- URL indicator
- Coordination flag

Conceptually:

```text
Risk Score =
    Bot Signal
  + Engagement Anomaly
  + Sentiment Weight
  + Suspicious Keyword Signal
  + URL Indicator
  + Coordination Signal
```

The resulting score is used for **analytical prioritization and triage**.

A high score should not be interpreted as proof that an account, narrative, or piece of content is malicious.

---

## 2. Threat-Level Analysis

The calculated risk score is translated into threat-level information that enables analysts to quickly identify records requiring closer examination.

This provides a high-level overview of potentially relevant intelligence.

---

## 3. Sentiment Analysis

Sentinel incorporates a lightweight **keyword-based NLP simulation** for sentiment-related signals.

This allows sentiment to become one component of the broader threat-analysis workflow while maintaining a transparent and interpretable methodology.

---

## 4. Anomaly Analysis

The platform incorporates engagement-related anomaly signals to identify potentially unusual activity patterns.

Examples include:

- Unusual engagement spikes
- Abnormal interaction levels
- Potentially coordinated amplification
- Bot-like behavioral patterns

---

## 5. Narrative Analysis

Sentinel allows intelligence records to be examined in relation to recurring narratives.

This shifts analysis from isolated records toward broader patterns:

```text
Individual Records
        ↓
Narratives
        ↓
Accounts
        ↓
Indicators
        ↓
Potentially Coordinated Activity
```

---

## 6. Relationship Visualization

The platform provides relationship-oriented visualization connecting:

- Platforms
- Narratives
- Accounts
- Hashtags
- URLs
- Intelligence indicators

This allows analysts to explore potentially meaningful relationships across the intelligence dataset.

---

## 7. Interactive Filtering

Sentinel provides interactive filtering that allows analysts to dynamically explore the intelligence dataset.

This supports investigation by platform and other available analytical dimensions.

---

# 🏗️ System Architecture

```text
                    ┌────────────────────┐
                    │  Synthetic Dataset │
                    └─────────┬──────────┘
                              │
                              ▼
                    ┌────────────────────┐
                    │ Feature Extraction │
                    └─────────┬──────────┘
                              │
                              ▼
              ┌───────────────────────────────┐
              │ Threat Signal Analysis        │
              │                               │
              │ • Bot Score                   │
              │ • Engagement Anomaly          │
              │ • Sentiment                   │
              │ • Keywords                    │
              │ • URL Indicators              │
              │ • Coordination Signals        │
              └───────────────┬───────────────┘
                              │
                              ▼
                    ┌────────────────────┐
                    │   Risk Scoring     │
                    └─────────┬──────────┘
                              │
                              ▼
                    ┌────────────────────┐
                    │ Crossfilter        │
                    │ Interactive        │
                    │ Filtering           │
                    └─────────┬──────────┘
                              │
                              ▼
              ┌───────────────────────────────┐
              │ Threat Intelligence Dashboard│
              │                               │
              │ • Threat Levels              │
              │ • Sentiment                   │
              │ • Activity Timeline           │
              │ • Risk Distribution           │
              │ • Relationship Graph          │
              │ • Analyst Summary             │
              └───────────────┬───────────────┘
                              │
                              ▼
                    ┌────────────────────┐
                    │ Human Analyst      │
                    │ Interpretation     │
                    └────────────────────┘
```

---

# 🔄 Analytical Workflow

The Sentinel workflow can be summarized as:

```text
DATA
 │
 ▼
Feature Extraction
 │
 ▼
Threat Signals
 │
 ├── Bot Behavior
 ├── Engagement Anomaly
 ├── Sentiment
 ├── Suspicious Keywords
 ├── URL Indicators
 └── Coordination
 │
 ▼
Composite Risk Score
 │
 ▼
Threat Prioritization
 │
 ▼
Interactive Investigation
 │
 ▼
Human Analyst Review
```

---

# 📊 Dashboard

The Sentinel dashboard provides several complementary analytical views.

### Platform Distribution

Allows analysts to examine intelligence according to platform.

### Threat Level

Displays threat-level information derived from the calculated risk score.

### Sentiment

Provides a sentiment-oriented view based on keyword analysis.

### Activity Timeline

Helps identify changes in activity over time and potential periods of increased activity.

### Risk Score Distribution

Shows the distribution of calculated risk scores across intelligence records.

### Relationship Graph

Visualizes relationships between:

```text
Platform
    │
    ├── Narrative
    │      │
    │      ├── Account
    │      └── Account
    │
    └── Indicators
           ├── Hashtag
           └── URL
```

### Analyst Summary

Provides a high-level analytical overview of the available intelligence.

---

# 🧮 Risk Scoring Methodology

Sentinel intentionally uses a **transparent and explainable scoring methodology**.

The current proof-of-concept combines multiple intelligence signals into a composite risk score.

The conceptual model is:

```text
Risk Score =
    Bot Signal
  + Engagement Anomaly
  + Sentiment Weight
  + Suspicious Keyword Signal
  + URL Indicator
  + Coordination Signal
```

Each signal contributes to the overall analytical prioritization of an intelligence record.

The resulting score helps an analyst determine **which records deserve closer examination first**.

It is not intended to establish attribution or determine malicious intent automatically.

---

# 🤖 AI Approach

## Current Implementation

The current version implements **AI-assisted analytical simulation** through transparent rule-based logic.

Current analytical components include:

- Rule-based risk scoring
- Keyword-based NLP simulation
- Engagement anomaly signals
- Bot-like behavioral indicators
- Coordination indicators
- Interactive analytical prioritization

This approach deliberately prioritizes:

- Interpretability
- Transparency
- Reproducibility
- Analyst oversight

---

## Why Rule-Based AI?

For a proof-of-concept Threat Intelligence platform, transparent rules provide several useful properties:

- Explainability
- Reproducibility
- Easy inspection of individual signals
- Clear relationship between evidence and risk score
- Easy modification of analytical rules
- No dependence on opaque model predictions

The current architecture can later be extended with trained machine-learning and NLP models.

---

# 🔬 AI / ML Extension Architecture

The current rule-based approach can be extended toward a more advanced AI pipeline:

```text
                    Intelligence Data
                           │
                           ▼
                  Feature Extraction
                           │
             ┌─────────────┼─────────────┐
             ▼             ▼             ▼
        Behavioral       NLP          Network
         Features      Features       Features
             │             │             │
             └─────────────┼─────────────┘
                           │
                           ▼
                    ML / AI Models
                           │
                           ▼
                    Risk Prediction
                           │
                           ▼
                Explainable Results
                           │
                           ▼
                    Human Analyst
```

---

# 🧠 Potential AI Components

Future versions of Sentinel can incorporate advanced AI and ML techniques.

## Machine Learning

Potential applications include:

- Supervised threat classification
- Unsupervised anomaly detection
- Behavioral clustering
- Risk prediction
- Time-series anomaly detection

## Natural Language Processing

Potential applications include:

- Transformer-based sentiment analysis
- Named Entity Recognition
- Narrative classification
- Semantic similarity
- Automated narrative clustering
- Topic modeling
- Stance detection

## Large Language Models

Potential applications include:

- Intelligence summarization
- Analyst question answering
- Narrative explanation
- Evidence extraction
- Threat-report generation
- Analyst decision support

## Graph Intelligence

Potential extensions include:

- Graph-based threat analysis
- Community detection
- Entity relationship modeling
- Graph Neural Networks
- Network-based anomaly detection

> These capabilities represent future research and development directions and are **not part of the current proof-of-concept implementation**.

---

# 🕸️ Threat Intelligence Graph

A future graph-oriented implementation could represent intelligence as a heterogeneous graph:

```text
             ┌─────────────┐
             │   Account   │
             └──────┬──────┘
                    │
                    │ posts
                    ▼
             ┌─────────────┐
             │  Narrative  │
             └──────┬──────┘
                    │
             associated with
                    │
                    ▼
             ┌─────────────┐
             │  Indicator  │
             └──────┬──────┘
                    │
              references
                    │
                    ▼
             ┌─────────────┐
             │     URL     │
             └─────────────┘
```

This provides a foundation for future graph-based Threat Intelligence analysis.

---

# 🛠️ Technology Stack

| Technology | Role |
|---|---|
| HTML5 | Application structure |
| CSS3 | Interface and dashboard styling |
| JavaScript | Application logic |
| D3.js | Data visualization |
| dc.js | Interactive charts |
| Crossfilter | Multidimensional filtering |
| GitHub Pages | Deployment |

---

# 💻 Technical Design

Sentinel is implemented as a lightweight client-side web application.

The current architecture avoids unnecessary backend infrastructure and allows the proof-of-concept to run directly in a modern web browser.

### Main Components

```text
Browser
  │
  ├── HTML
  │
  ├── CSS
  │
  └── JavaScript
        │
        ├── Data Processing
        ├── Feature Extraction
        ├── Risk Scoring
        ├── Filtering
        └── Visualization
```

---

# 📂 Repository Structure

```text
Sentinel-AI-Assisted-Hybrid-Threat-Intelligence-Platform/
│
├── index.html
└── README.md
```

The current proof-of-concept is intentionally lightweight and client-side.

---

# ⚙️ Running Locally

Because Sentinel is implemented as a client-side web application, it can be run locally with a simple static web server.

## Clone the repository

```bash
git clone https://github.com/mariosvard/Sentinel-AI-Assisted-Hybrid-Threat-Intelligence-Platform.git
```

## Enter the project

```bash
cd Sentinel-AI-Assisted-Hybrid-Threat-Intelligence-Platform
```

## Run with Python

```bash
python -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

---

# 📸 Screenshots

Screenshots can be added to the repository to demonstrate the main analytical views.

## Main Dashboard

```markdown
![Sentinel Dashboard](assets/sentinel-dashboard.png)
```

## Risk & Threat Analysis

```markdown
![Risk Analysis](assets/risk-analysis.png)
```

## Relationship Graph

```markdown
![Threat Relationship Graph](assets/relationship-graph.png)
```

> Replace the example paths above with the actual screenshot filenames after adding the images to the repository.

---

# 🔐 Ethics, Safety & Responsible AI

Sentinel is designed as a **research and educational proof-of-concept**.

The platform:

- Uses synthetic intelligence scenarios
- Does not access private accounts
- Does not access classified intelligence
- Does not perform surveillance
- Does not perform real-world attribution
- Does not access live social-media APIs
- Does not make autonomous operational decisions

The system is intended to support **analyst review rather than replace human judgment**.

Risk scores represent analytical signals and should not be interpreted as definitive evidence of malicious behavior.

---

# 👨‍💻 Human-in-the-Loop Design

A central design principle of Sentinel is **Human-in-the-Loop Threat Intelligence**.

```text
AI-Assisted Analysis
        │
        ▼
Risk Prioritization
        │
        ▼
Evidence Visualization
        │
        ▼
Human Analyst
        │
        ▼
Final Interpretation
```

The system therefore focuses on:

**Assist → Explain → Prioritize → Visualize**

rather than:

**Automate → Decide → Attribute**

---

# ⚠️ Limitations

The current proof-of-concept has several important limitations:

1. The intelligence scenarios are synthetic.
2. The current risk model is rule-based.
3. Sentiment analysis uses keyword-based NLP simulation.
4. The system does not ingest live intelligence feeds.
5. No real-world attribution is performed.
6. The system is not intended for operational intelligence deployment.
7. Risk scores should not be interpreted as ground truth.
8. The current implementation does not include a trained machine-learning model.
9. The current implementation does not use an LLM.
10. The current implementation does not perform autonomous threat decisions.

These limitations define clear opportunities for future research and development.

---

# 📌 Current Status

**Status: Proof of Concept / Research Prototype**

## Implemented

- [x] Threat Intelligence dashboard
- [x] Synthetic intelligence scenarios
- [x] Feature extraction
- [x] Rule-based risk scoring
- [x] Sentiment simulation
- [x] Engagement anomaly signals
- [x] Bot-like behavioral indicators
- [x] Coordination indicators
- [x] Interactive filtering
- [x] Risk visualization
- [x] Threat-level analysis
- [x] Relationship visualization
- [x] Analyst prioritization
- [x] GitHub Pages deployment

## Future Development

- [ ] Machine-learning anomaly detection
- [ ] ML-based threat classification
- [ ] Transformer-based NLP
- [ ] Automated narrative clustering
- [ ] Entity extraction
- [ ] LLM-assisted intelligence analysis
- [ ] Graph-based threat analysis
- [ ] Explainable AI
- [ ] Uncertainty estimation
- [ ] STIX/TAXII integration
- [ ] MITRE ATT&CK integration
- [ ] Real-time intelligence ingestion
- [ ] Privacy-preserving Threat Intelligence
- [ ] Multi-agent Threat Intelligence

---

# 🔮 Development Roadmap

## Phase 1 — Proof of Concept

**Current**

```text
Synthetic Data
      ↓
Rule-Based Signals
      ↓
Risk Scoring
      ↓
Interactive Dashboard
      ↓
Human Analyst
```

---

## Phase 2 — Machine Learning

```text
Intelligence Data
      ↓
Feature Engineering
      ↓
ML Models
      ↓
Anomaly Detection
      ↓
Risk Prediction
      ↓
Analyst Review
```

Potential models:

- Random Forest
- Gradient Boosting
- Isolation Forest
- Autoencoders
- Clustering algorithms
- Time-series anomaly detection

---

## Phase 3 — Advanced NLP

```text
Text
 ↓
Transformer Model
 ↓
Entities + Topics + Sentiment
 ↓
Narrative Detection
 ↓
Threat Intelligence
```

Potential capabilities:

- Named Entity Recognition
- Semantic similarity
- Narrative clustering
- Topic modeling
- Sentiment classification
- Stance detection

---

## Phase 4 — LLM-Assisted Intelligence

Potential capabilities:

- Intelligence summarization
- Natural-language investigation
- Evidence extraction
- Analyst copilot
- Explainable recommendations
- Automated report generation

The LLM should operate as an **analyst-support component**, not as an autonomous decision maker.

---

## Phase 5 — Threat Intelligence Integration

Potential integrations include:

- STIX
- TAXII
- MITRE ATT&CK
- OSINT feeds
- Threat intelligence APIs
- Structured cyber threat intelligence

---

## Phase 6 — Trustworthy AI

Future development can incorporate:

- Explainable AI
- Uncertainty estimation
- Confidence calibration
- Bias analysis
- Human oversight
- Auditability
- Privacy-preserving analytics
- Secure AI pipelines
- AI safety mechanisms

---

# 🔬 Research Direction

Sentinel explores the intersection of:

**Artificial Intelligence × Cybersecurity × Threat Intelligence × Human-AI Collaboration**

The broader research question is:

> **How can AI-assisted systems help human analysts identify, prioritize, and investigate complex threat signals while remaining transparent, explainable, and subject to human oversight?**

This makes Sentinel a potential foundation for future research into:

- Trustworthy AI for cybersecurity
- AI-assisted Threat Intelligence
- Human-AI decision support
- Explainable threat detection
- Privacy-preserving intelligence analysis
- AI safety and governance
- Multi-agent Threat Intelligence systems

---

# 🧪 Research Questions

The platform can support future investigation of questions such as:

### RQ1 — Threat Detection

How effectively can AI models identify anomalous or coordinated threat-related activity?

### RQ2 — Explainability

Can analysts understand and validate AI-generated threat scores?

### RQ3 — Human-AI Collaboration

Does AI-assisted prioritization improve analyst efficiency without increasing automation bias?

### RQ4 — Uncertainty

How should uncertainty be represented when intelligence signals are incomplete or contradictory?

### RQ5 — Privacy

How can organizations collaborate on Threat Intelligence while minimizing exposure of sensitive information?

### RQ6 — Multi-Agent Intelligence

Can multiple specialized AI agents collaboratively analyze heterogeneous threat signals while maintaining human oversight?

---

# 📈 Evaluation Framework

Future ML-based versions of Sentinel could be evaluated using:

## Detection Performance

- Precision
- Recall
- F1-score
- ROC-AUC
- PR-AUC

## Anomaly Detection

- False Positive Rate
- False Negative Rate
- Detection Rate
- Precision@K

## Analyst Support

- Investigation time
- Prioritization accuracy
- Analyst agreement
- Cognitive workload
- Human-AI decision quality

## Trustworthy AI

- Calibration
- Explanation fidelity
- Uncertainty quality
- Robustness
- Bias and fairness analysis

---

# 🌍 Potential Applications

A mature version of Sentinel could potentially support research and experimentation in areas such as:

- Cyber Threat Intelligence
- Information Operations Analysis
- Disinformation Research
- Coordinated Activity Detection
- OSINT Analytics
- Security Operations
- Incident Triage
- Narrative Monitoring
- Hybrid Threat Research
- AI-assisted Security Analysis

The current project is **not intended for operational deployment**.

---

# 🔐 Privacy-Preserving Intelligence

An important future direction is combining Threat Intelligence with privacy-preserving AI.

Potential techniques include:

- Differential Privacy
- Federated Learning
- Secure Multi-Party Computation
- Privacy-preserving analytics
- Synthetic data generation

This could enable collaborative threat analysis while reducing the need to share sensitive raw intelligence.

---

# 🤝 Human-AI Collaboration

Sentinel is built around the principle that AI should **augment analysts rather than replace them**.

The intended interaction model is:

```text
                 ┌─────────────────┐
                 │ Intelligence    │
                 │ Data            │
                 └────────┬────────┘
                          │
                          ▼
                 ┌─────────────────┐
                 │ AI-Assisted     │
                 │ Analysis        │
                 └────────┬────────┘
                          │
                          ▼
                 ┌─────────────────┐
                 │ Explainable     │
                 │ Risk Signals    │
                 └────────┬────────┘
                          │
                          ▼
                 ┌─────────────────┐
                 │ Human Analyst   │
                 └────────┬────────┘
                          │
                          ▼
                 ┌─────────────────┐
                 │ Final           │
                 │ Interpretation  │
                 └─────────────────┘
```

This design emphasizes:

> **Human judgment remains the final layer of interpretation.**

---

# 📚 Broader Research Context

Sentinel connects several research areas:

```text
              Artificial Intelligence
                       │
          ┌────────────┼────────────┐
          │            │            │
          ▼            ▼            ▼
       Machine       NLP         Graph AI
       Learning
          │            │            │
          └────────────┼────────────┘
                       │
                       ▼
               Threat Intelligence
                       │
                       ▼
               Human-AI Collaboration
                       │
                       ▼
                 Trustworthy AI
```

This interdisciplinary direction makes the platform suitable as a foundation for further experimentation and academic research.

---

# 🧭 Design Principles

Sentinel follows several core principles:

### 1. Explainability

Threat signals should be understandable.

### 2. Transparency

The relationship between evidence and risk should be visible.

### 3. Human Oversight

Final interpretation remains with the analyst.

### 4. Privacy Awareness

Threat Intelligence systems should minimize unnecessary exposure of sensitive data.

### 5. Responsible AI

AI-assisted systems should avoid presenting uncertain predictions as facts.

### 6. Reproducibility

Analytical methods should be inspectable and reproducible.

---

# 🖥️ Example Analyst Workflow

A typical investigation can follow:

```text
1. Review overall threat distribution
             ↓
2. Identify high-risk records
             ↓
3. Filter by platform or indicator
             ↓
4. Examine sentiment and activity
             ↓
5. Investigate narratives
             ↓
6. Explore account relationships
             ↓
7. Review supporting indicators
             ↓
8. Analyst interpretation
```

This workflow is designed for **triage and investigation**, not automated attribution.

---

# 📊 Why Sentinel?

Traditional dashboards often show individual indicators separately.

Sentinel attempts to provide a more integrated analytical view.

### Traditional Approach

```text
Indicator A
Indicator B
Indicator C
Indicator D
     ↓
Analyst manually connects them
```

### Sentinel Approach

```text
Indicators
    +
Behavior
    +
Sentiment
    +
Narratives
    +
Coordination
    ↓
Risk Prioritization
    ↓
Interactive Investigation
    ↓
Human Analyst
```

---

# 📸 Demonstration

The Sentinel interface can be used to demonstrate:

- Threat-level analysis
- Risk-score prioritization
- Sentiment analysis
- Activity patterns
- Narrative analysis
- Relationship exploration
- High-risk intelligence records
- Interactive filtering

For a stronger GitHub presentation, screenshots of the live dashboard should be added to the repository.

---

# 📝 Important Disclaimer

Sentinel is a **research and educational proof-of-concept**.

The system does not establish malicious intent, attribution, or responsibility.

A high risk score indicates that a record contains a combination of signals considered potentially relevant by the analytical model.

It should **not** be treated as definitive evidence of malicious activity.

All intelligence scenarios used by the current demonstration are synthetic.

---

# 📦 Installation Requirements

No backend installation is required for the current proof-of-concept.

You only need:

- A modern web browser
- Python 3.x (optional, for local serving)
- Git (optional, for cloning the repository)

---

# 🚀 Deployment

The current application is deployed using **GitHub Pages**.

Deployment workflow:

```text
GitHub Repository
        ↓
index.html
        ↓
GitHub Pages
        ↓
Public Web Application
```

Live deployment:

[https://mariosvard.github.io/Sentinel-AI-Assisted-Hybrid-Threat-Intelligence-Platform/](https://mariosvard.github.io/Sentinel-AI-Assisted-Hybrid-Threat-Intelligence-Platform/)

---

# 🔗 Project Links

- 🚀 **[Live Demo](https://mariosvard.github.io/Sentinel-AI-Assisted-Hybrid-Threat-Intelligence-Platform/)**
- 💻 **[GitHub Repository](https://github.com/mariosvard/Sentinel-AI-Assisted-Hybrid-Threat-Intelligence-Platform)**
- 🌐 **[Author Portfolio](https://mariosvard.github.io/mariosvardalachakis/)**
- 🔗 **[GitHub Profile](https://github.com/mariosggg)**

---

# 👤 Author

## Marios Vardalachakis

**Software Engineer | AI & Intelligent Systems Researcher**

Research interests include:

- Artificial Intelligence
- Intelligent Systems
- Cybersecurity
- Privacy-Preserving AI
- Trustworthy AI
- Threat Intelligence
- Human-AI Collaboration
- Data Anonymization
- Machine Learning

### Portfolio

🌐 [https://mariosvard.github.io/mariosvardalachakis/](https://mariosvard.github.io/mariosvardalachakis/)

### GitHub

💻 [https://github.com/mariosggg](https://github.com/mariosggg)

---

# 📄 License

This project is intended for **research, educational, and demonstration purposes**.

See the repository for applicable licensing information.

---

<p align="center">

## 🛡️ Sentinel

<strong>Assist analysts. Visualize evidence. Prioritize intelligence. Preserve human judgment.</strong>

</p>
