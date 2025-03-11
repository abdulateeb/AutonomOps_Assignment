# Agentic War Room

## Overview
This project is designed to process metrics and logs, detect anomalies, perform root cause analysis, and provide recommendations. It integrates anomaly detection, correlation analysis, and visualization to assist in proactive issue resolution.

## Features
- **Data Loading**: Load metrics and logs from structured sources.
- **Anomaly Detection**: Identify outliers using AI-based techniques.
- **Root Cause Analysis**: Determine correlations and possible root causes of anomalies.
- **Generative AI Integration**: Use Google Gemini API to generate detailed explanations and recommendations.
- **Visualization**: Generate summary charts, heatmaps, and timelines to illustrate anomalies.
- **Flask API**: Expose processing as an API endpoint for easy access.

## Project Structure

agentic_war_room/
├── 📂 modules/                  
│   ├── __init__.py
│   ├── anomaly_detection.py     
│   ├── correlation.py           
│   ├── data_loader.py        
│   ├── genai_analysis.py      
│   ├── root_cause_analysis.py 
│   ├── visualization.py         
├── 📂 reports/
│   └── detailed_anomalies_report.csv 
├── 📂 utils/                       
│   └── logger.py                     
├── 📦 venv/                        
├── 🔑 .env                         
├── 📜 requirements.txt             
├── 💻 app.py                       
└── 📑 README.md