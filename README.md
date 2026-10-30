
<div align="center">

# ⚙️ CNC AERO-HEALTH MONITOR

### `INTELLIGENT MACHINE HEALTH & PREDICTIVE MAINTENANCE`

<img src="https://img.shields.io/badge/INDUSTRY-4.0-00E5FF?style=for-the-badge&labelColor=07111F"/>
<img src="https://img.shields.io/badge/AI-GOWER%20%2B%20KNN-A78BFA?style=for-the-badge&labelColor=07111F"/>
<img src="https://img.shields.io/badge/MACHINE%20FLEET-10K-22C55E?style=for-the-badge&labelColor=07111F"/>

**MONITOR. ANALYSE. PREDICT. PREVENT.**

A smart industrial analytics interface designed to transform machine telemetry into actionable health intelligence.

[🚀 EXPLORE PROJECT](https://vaishnvikedar6-jpg.github.io/CNC/)

</div>

---

# ◈ 01 — SYSTEM OVERVIEW

<div align="center">

| <sub>01 / MONITORING</sub> | <sub>02 / INTELLIGENCE</sub> | <sub>03 / PREDICTION</sub> |
|:---:|:---:|:---:|
| 🖥️ | 🧬 | 🧠 |
| **Machine Fleet** | **Gower Engine** | **KNN Classifier** |
| Telemetry Analysis | Similarity Intelligence | Condition Prediction |

</div>

CNC Aero-Health Monitor is a predictive maintenance dashboard that explores CNC machine operating parameters, identifies similar machine profiles and supports machine-condition assessment.

It brings together:

- Machine telemetry exploration
- Mixed-attribute similarity analysis
- K-Nearest Neighbors classification
- Machine health assessment
- Predictive maintenance insights
- Remaining Useful Life (RUL) related information

> The objective is to move from reactive maintenance towards intelligent, data-driven machine monitoring.

---

# ◈ 02 — THE DIGITAL CONTROL ROOM

### A unified machine intelligence environment

| CONTROL MODULE | FUNCTION |
|---|---|
| ◉ Fleet Intelligence | Machine fleet overview and health information |
| ◉ Machine Explorer | Individual machine parameters and records |
| ◉ Similarity Lab | Gower similarity matrix and machine comparison |
| ◉ Predictive Engine | KNN-based condition classification |
| ◉ Maintenance Centre | Engineering insights and maintenance support |

---

# ◈ 03 — SYSTEM ARCHITECTURE

```mermaid
flowchart TB
    A["⚙️ CNC MACHINE FLEET"] --> B["Machine Telemetry"]
    B --> C["Data Preparation"]
    C --> D["Mixed Attribute Processing"]
    D --> E["Gower Similarity Engine"]
    E --> F["Nearest Neighbour Selection"]
    F --> G["KNN Classification"]
    G --> H{"Machine Condition"}
    H --> I["🟢 NORMAL"]
    H --> J["🟠 WARNING"]
    H --> K["🔴 CRITICAL"]
    I --> L["Machine Health Insights"]
    J --> L
    K --> L
    L --> M["Maintenance Decision Support"]

    style A fill:#123B55,color:#fff,stroke:#38BDF8
    style E fill:#312E81,color:#fff,stroke:#A78BFA
    style G fill:#164E63,color:#fff,stroke:#22D3EE
    style H fill:#713F12,color:#fff,stroke:#FBBF24
    style M fill:#14532D,color:#fff,stroke:#22C55E
```

---

# ◈ 04 — THE GOWER SIMILARITY ENGINE

### Understanding machines beyond numerical distance

Traditional distance metrics are not always suitable for datasets containing different attribute types.

Gower Similarity provides a way to compare mixed data:

- Numerical attributes
- Categorical attributes
- Binary attributes
- Ordinal attributes

### Mathematical Foundation

\[
S(i,j)=
\frac{\sum_k w_{ijk}s_{ijk}}
{\sum_k w_{ijk}}
\]

Where:

| Symbol | Meaning |
|---|---|
| \(S(i,j)\) | Overall similarity between machines |
| \(s_{ijk}\) | Similarity for attribute k |
| \(w_{ijk}\) | Attribute availability weight |
| \(k\) | Individual machine attribute |

<details>
<summary><b>⚡ How to interpret similarity?</b></summary>

- Score close to 1: Highly similar machine profiles.
- Score close to 0: Very different machine profiles.
- Attribute-level comparison helps explain why two machines are similar.

</details>

---

# ◈ 05 — K-NEAREST NEIGHBORS ENGINE

### Machine condition classification

The KNN classifier uses neighbouring machine records to estimate the condition of a selected machine.

```mermaid
flowchart TD
    A["Input Machine Parameters"] --> B["Compare With Fleet"]
    B --> C["Calculate Similarity"]
    C --> D["Select K Nearest Neighbours"]
    D --> E["Neighbour Voting"]
    E --> F{"Predicted Condition"}
    F --> G["NORMAL"]
    F --> H["WARNING"]
    F --> I["CRITICAL"]

    style A fill:#123B55,color:#fff,stroke:#38BDF8
    style D fill:#312E81,color:#fff,stroke:#A78BFA
    style E fill:#164E63,color:#fff,stroke:#22D3EE
    style G fill:#14532D,color:#fff,stroke:#22C55E
    style H fill:#713F12,color:#fff,stroke:#FBBF24
    style I fill:#7F1D1D,color:#fff,stroke:#EF4444
```

### Condition Intelligence

| CONDITION | INDICATOR | INTERPRETATION |
|---|---|---|
| 🟢 NORMAL | Healthy | Normal operating pattern |
| 🟠 WARNING | Attention | Potential abnormal behaviour |
| 🔴 CRITICAL | High Priority | Requires immediate inspection |

---

# ◈ 06 — MACHINE HEALTH PARAMETERS

The monitoring environment focuses on important machine-operating signals.

| PARAMETER | ENGINEERING SIGNIFICANCE |
|---|---|
| Temperature | Thermal operating behaviour |
| Rotational Speed | Spindle performance |
| Torque | Mechanical load |
| Tool Wear | Tool degradation |
| Power | Energy consumption |
| Vibration | Mechanical behaviour |
| Failure Information | Historical condition reference |

These parameters help explore patterns associated with machine operating conditions.

---

# ◈ 07 — PREDICTIVE MAINTENANCE INTELLIGENCE

### From machine signals to maintenance decisions

```mermaid
flowchart LR
    A["Machine Signals"] --> B["Health Assessment"]
    B --> C["Abnormal Pattern Detection"]
    C --> D["Maintenance Priority"]
    D --> E["Inspection"]
    E --> F["Maintenance Action"]

    style A fill:#123B55,color:#fff
    style B fill:#312E81,color:#fff
    style C fill:#713F12,color:#fff
    style D fill:#7F1D1D,color:#fff
    style F fill:#14532D,color:#fff
```

### Key Maintenance Insights

- Identify machines requiring closer inspection.
- Explore similar historical machine profiles.
- Monitor tool-wear and thermal parameters.
- Prioritise abnormal operating patterns.
- Support maintenance planning.

### Remaining Useful Life (RUL)

Remaining Useful Life represents the estimated operating time before a machine or component reaches its end-of-life condition.

RUL forecasting is an important direction for extending this system with validated time-series degradation models.

---

# ◈ 08 — DATA & ANALYTICS WORKFLOW

```mermaid
flowchart TB
    A["Machine Fleet Dataset"] --> B["Data Exploration"]
    B --> C["Attribute Identification"]
    C --> D["Similarity Computation"]
    D --> E["Machine Comparison"]
    E --> F["Condition Classification"]
    F --> G["Visual Analytics"]
    G --> H["Maintenance Insights"]

    style A fill:#0C4A6E,color:#fff
    style D fill:#312E81,color:#fff
    style F fill:#164E63,color:#fff
    style H fill:#14532D,color:#fff
```

---

# ◈ 09 — TECHNOLOGY STACK

<div align="center">

<img src="https://skillicons.dev/icons?i=html,css,js,git,github,vscode"/>

</div>

| TECHNOLOGY | ROLE |
|---|---|
| HTML5 | Application structure |
| CSS3 | Dashboard styling |
| JavaScript | Interactive application logic |
| Gower Similarity | Mixed-data similarity analysis |
| KNN | Classification methodology |
| SVG / Canvas | Visual analytics |

---

# ◈ 10 — APPLICATION FEATURES

| FEATURE | CAPABILITY |
|---|---|
| Fleet Dashboard | Fleet-level monitoring |
| Machine Search | Machine record exploration |
| Similarity Matrix | Machine-to-machine comparison |
| KNN Prediction | Condition classification |
| Health Indicators | Condition visualisation |
| Theme Switching | Dark / Light interface |
| CSV Export | Export filtered records |
| Maintenance View | Maintenance-oriented insights |

---

# ◈ 11 — GET STARTED

### Step 1 — Clone Repository

```bash
git clone https://github.com/vaishnvikedar6-jpg/CNC.git
```

### Step 2 — Enter Project Directory

```bash
cd CNC
```

### Step 3 — Launch

Open `index.html` in your browser.

Alternatively, open the folder in VS Code and use Live Server.

---

# ◈ 12 — PROJECT STRUCTURE

```text
CNC/
│
├── index.html
├── CNC Health Monitor.html
└── README.md
```

---

# ◈ 13 — FUTURE ROADMAP

```mermaid
flowchart TD
    A["Current Dashboard"] --> B["Live IoT Integration"]
    B --> C["Backend & Database"]
    C --> D["Real-Time Sensor Monitoring"]
    D --> E["Degradation Forecasting"]
    E --> F["Automated Maintenance Alerts"]

    style A fill:#164E63,color:#fff
    style B fill:#312E81,color:#fff
    style C fill:#312E81,color:#fff
    style D fill:#123B55,color:#fff
    style E fill:#713F12,color:#fff
    style F fill:#14532D,color:#fff
```

### Planned Enhancements

- Real-time CNC sensor integration
- IoT-based machine communication
- Backend API and persistent storage
- Time-series machine degradation forecasting
- Validated RUL prediction
- Automated maintenance notifications

---

<div align="center">

# ⚡ THE FUTURE IS PREDICTIVE.

### MACHINES THAT SPEAK. DATA THAT THINKS.

**MONITOR → ANALYSE → PREDICT → PREVENT**

[⚙️ EXPLORE CNC AERO-HEALTH MONITOR](https://github.com/vaishnvikedar6-jpg/CNC)

<sub>Built for intelligent manufacturing and predictive maintenance.</sub>

</div>
