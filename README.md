# Hybrid Ransomware Detection System

This project implements a hybrid approach to ransomware detection using:
- ✅ Convolutional Neural Networks (CNN) for known threats
- ✅ Autoencoders for anomaly-based detection (zero-day)
- ✅ Deep Reinforcement Learning (DRL) for adaptive responses

## 🔧 Features
- Real-time simulation using Flask + Watchdog
- Google Colab training notebook included
- Dataset integration scripts for CIC-IDS2018, CTU-13, and ransomware logs

## 📁 Structure
```
Hybrid-Ransomware-Detection/
├── api/                  # Flask API for model inference
├── monitor/              # Watchdog-based file system simulation
├── data/scripts/         # Dataset parsing & feature extraction
├── notebook/             # Google Colab notebook
├── models/               # Trained models (optional)
├── README.md             # This file
└── requirements.txt      # Dependencies
```

## 📊 Datasets
- CIC-IDS2018: https://www.unb.ca/cic/datasets/ids-2018.html
- CTU-13: https://www.stratosphereips.org/datasets-ctu13
- Ransomware logs: e.g., VirusTotal, Stratosphere, HEC-Ransomware
