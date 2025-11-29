# AI Agents Assignment – AutoParts Inc Simulation  
This repository contains my AI Agents assignment, including short answer responses, a case study analysis, and a working simulation of an AI multi-agent system built using **n8n**.

---

## 📌 Project Overview  
This project demonstrates how AI Agents can be integrated into a real manufacturing workflow. The case study focuses on **AutoParts Inc**, a mid-sized automotive parts manufacturer facing:

- 15% defect rate in precision components  
- Frequent machine downtime  
- Rising labor costs  
- Pressure for faster and more customized deliveries  

To address these challenges, the project implements **three AI agents**:

1. **Quality Inspection Agent (Computer Vision Simulation)**  
2. **Predictive Maintenance Agent (Sensor-Based AI)**  
3. **Workforce Optimization & Notification Agent**

A full end-to-end simulation is created in **n8n**, demonstrating real-time defect detection, anomaly prediction, and workforce recommendations.

---

## 🚀 n8n Workflow Simulation  

### 🔗 Workflow JSON  
The workflow JSON file is available in this repository under:  
`/workflow/AutoParts_AI_Agent_Simulation.json`

You can import it directly into **n8n**:

1. Open n8n  
2. Click **Import**  
3. Paste the JSON  
4. Run the workflow  

### 🧠 Agent Functions Simulated  
| Agent | Role | Output |
|-------|-------|---------|
| **Quality Inspection Agent** | Simulates computer-vision defect detection | Flags defective batches |
| **Predictive Maintenance Agent** | Uses random sensor values to emulate anomalies | Schedules maintenance |
| **Workforce Agent** | Decides optimal human intervention | Sends manager notifications |

You’ll receive a final system update:  
- "High Priority: Defects found + Machine issue"  
- or "All systems normal"  
depending on system state.

---

## 📈 Expected ROI  
The multi-agent system is designed to deliver:

- Up to **70% reduction** in defects and downtime  
- Faster order fulfillment  
- Lower labor costs  
- Improved product quality  
- Employee empowerment and reduced manual workload  

A detailed ROI breakdown is included inside the PDF assignment.

---

## ⚠️ Risks & Mitigation  
| Risk Type | Examples | Mitigation |
|-----------|----------|------------|
| Technical | Data drift, bad sensors | Model updates, routine audits |
| Organizational | Employee resistance | Training & change management |
| Ethical | Worker surveillance | Privacy protections, transparency |

---

## 📁 Repository Structure
/README.md
/assignment/
└── AI_Agent_Assignment.pdf  (generated after PDF step)
/workflow/
└── AutoParts_AI_Agent_Simulation.json
---

## 📝 Author  
**Egrah Nyanchama Savai**  
Assignment for **AI Agents Module**  
2025

---
