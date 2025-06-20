# GhostSenseAI

# 👻 GhostSenseAI

**GhostSenseAI** is an experimental framework for detecting potential paranormal anomalies using artificial intelligence.

It combines EMF sensors, ambient temperature data, and audio anomaly detection with a lightweight machine learning model to flag unexplained environmental patterns.

> “Truth wears EMF for a cloak.”

## 📡 What It Does (v0.1 Prototype)
- Connects to low-cost EMF + temp sensors
- Collects and visualizes environmental data
- Uses an AI model to detect irregularities
- Flags “anomalous” events with optional log recording

## 🧠 Future Features (Planned)
- Ultrasonic pattern classification
- Historical anomaly mapping
- Cloud-based ghost event sharing network

## 🛠️ Tech Stack (Targeted)
- Python (sensor reading + processing)
- Streamlit or Flask (UI prototype)
- Scikit-learn or basic LSTM/Transformer model
- USB/Serial sensor interface (optional mock input supported)

## 📁 Data Format
GhostSenseAI records data in simple JSON logs:

```json
{
  "timestamp": "2025-06-20T22:15:43",
  "location": "Old House Basement",
  "emf_mv": 624.3,
  "temp_c": 19.2,
  "anomaly_flagged": true,
  "notes": "Sudden spike with audio distortion."
}
