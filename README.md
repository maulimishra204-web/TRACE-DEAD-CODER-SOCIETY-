# TRACE
## Threat Actor Correlation & Attribution Engine

> An intelligence-driven platform for correlating publicly available digital traces to identify potential relationships between anonymous or pseudonymous threat-actor identities.

---

## 🏆 Smart India Hackathon

**Hackathon:** Smart India Hackathon (SIH) 2026  
**Category:** Software  
**Domain:** Cybersecurity & Blockchain

---

## 📌 Problem Statement

Threat actors operating through anonymous or pseudonymous platforms often use multiple accounts, aliases, and identities while conducting malicious activities.

These identities may be scattered across different platforms, making it difficult for cybersecurity analysts and investigators to determine whether seemingly unrelated accounts are connected to the same threat actor.

Traditional investigations often require manually collecting and comparing large amounts of fragmented information.

### Our Objective

TRACE aims to provide a unified platform that can analyze legally obtained and publicly available digital indicators and identify meaningful relationships between different online identities.

The system generates correlation insights and evidence-based indicators to assist cybersecurity investigations.

> **TRACE does not directly reveal or claim the real-world identity of an individual. It provides potential correlations and investigative leads for analyst review.**

---

# 💡 Our Solution

**TRACE (Threat Actor Correlation & Attribution Engine)** is a cybersecurity intelligence platform designed to connect fragmented digital traces associated with suspicious online identities.

The platform analyzes multiple indicators and determines whether different identities show meaningful similarities or relationships.

### Key indicators include:

- Usernames and aliases
- Email identifiers
- Cryptocurrency addresses
- Contact identifiers
- Writing patterns
- Posting behavior
- Activity timestamps
- Platform activity
- Shared infrastructure
- Other publicly available indicators

These indicators are processed and combined to generate a **correlation score** between entities.

---

# 🔍 Example

Consider a hypothetical threat actor using different identities:

```text
Username A → Platform 1
Username B → Platform 2
Username C → Marketplace
```
Individually, these accounts may appear unrelated.

TRACE can analyze their available indicators:
```text
Username similarity        ✓
Writing characteristics    ✓
Activity timing            ✓
Contact identifier         ✓
Cryptocurrency address     ✓
Platform behavior         ✓
```
The system can then generate an insight such as:
```text
Potential Correlation
Confidence Score: 87%
```
along with this evidence that contributed to the correlation.

---
# 🔄 System Workflow
          Digital Sources
                │
                ▼
        Data Collection
                │
                ▼
       Data Normalization
                │
                ▼
      Indicator Extraction
                │
                ▼
       Entity Correlation
                │
                ▼
      Relationship Graph
                │
                ▼
       Correlation Score
                │
                ▼
       Analyst Dashboard
                │
                ▼
      Investigation Report

---
## ✨ Key Features
**1. Threat Actor Profiles**
Create a unified profile containing the known indicators, aliases, and activity associated with a suspicious online identity.

**2. Identity Correlation**
Compare multiple online identities and identify potential relationships based on common indicators.

**3. Indicator Extraction**
Identify useful digital indicators such as:
```text
Usernames
Email identifiers
Cryptocurrency addresses
Domains
Contact identifiers
Platform references
Activity metadata
```
**4. Relationship Graph**
Visualize connections between different entities.
along with the evidence that contributed to the correlation.
```text
                 Threat Actor
                      │
          ┌───────────┼───────────┐
          ▼           ▼           ▼
       Username      Email      Crypto
          │           │           │
          ▼           ▼           ▼
       Platform    Account    Transaction
```

This helps investigators understand relationships that may not be obvious when examining individual records.

**5. Correlation Scoring**
The system assigns a correlation score based on the strength and number of matching indicators.

**6. Evidence-Based Analysis**
Instead of simply stating that two identities are connected, TRACE presents the indicators that contributed to the detected correlation.

**7. Investigation Dashboard**
A centralized dashboard provides:
```
Threat actor profiles
Connected identities
Digital indicators
Correlation scores
Relationship graphs
Investigation information
Evidence summaries
```
---
## Correlation Engine
TRACE follows a multi-indicator correlation approach.
```
                 Identity A
                     │
       ┌─────────────┼─────────────┐
       ▼             ▼             ▼
   Username        Email       Behaviour
       │             │             │
       └─────────────┼─────────────┘
                     ▼
             Correlation Engine
                     │
                     ▼
               Evidence Score
                     │
                     ▼
              Potential Link
                     │
                     ▼
               Analyst Review
```

The correlation score is intended to support human investigation rather than automatically establish definitive attribution.

---
# Prototype Modules

**Dashboard**
Provides an overview of investigations, threat actors, indicators, and detected relationships.

**Actor Investigation**
Allows analysts to inspect information associated with an individual threat-actor profile.

**Entity Correlation**
Displays potential relationships between different identities.

**Relationship Graph**
Provides a visual representation of connections between entities.

**Evidence Panel**
Displays the indicators contributing to a potential correlation.

**Investigation Reports**
Provides structured investigation information that can be reviewed by analysts.

---
## Technology Stack

### Frontend
HTML5
CSS3
JavaScript

### Backend
Python
Flask
REST APIs

### Database
SQL Database
### Data Processing
Data normalization
Pattern extraction
Entity matching
Correlation analysis

### Visualization
Interactive dashboards
Relationship graphs
Data visualization

### Development Tools
Visual Studio Code
Git
GitHub

---
