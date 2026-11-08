# SentinelAI Core: Host-Based Threat & Log Intelligence Agent

> **GenHacks 2026 Submission** | Track: *AI, Agentic Systems, Cybersecurity, and Dev Tools*

## 🚀 Overview
**SentinelAI Core** is a lightweight, intelligent host-based security utility designed to ingest system audit telemetry, analyze high-frequency access patterns, and detect behavioral anomalies under strict execution constraints. Built entirely for cloud-native execution environments (such as Google Colab) using pure Python.

## 🔑 Key Features
* **Automated Log Ingestion:** Parses and standardizes system telemetry feeds.
* **Behavioral Threat Detection:** Uses algorithmic heuristics and lightweight AI scoring to flag suspicious host activities.
* **Structured JSON Telemetry:** Exports audit logs (`sentinel_audit_report.json`) for downstream security information and event management (SIEM) pipelines.

## 🛠️ Tech Stack & Requirements
* **Language:** Python 3.x
* **Runtime:** Google Colab / Standard Host Python Environment
* **License:** MIT License

## ⚙️ Build and Run Instructions (Google Colab)
1. Open the Python script (`sentinel_ai_core.py`) in Google Colab.
2. Run the cell to initialize the threat-detection pipeline.
3. Review the real-time console output and verify the generated `sentinel_audit_report.json` telemetry artifact.
