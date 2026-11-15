# AURORA-X — Adaptive Astronaut Cognitive Risk Monitoring

A responsive web application and interactive mission control cockpit for autonomous astronaut cognitive health and mission risk monitoring during deep-space travel.

---

## 🚀 How to Run the Website

### Option 1: Double-Click / Direct File Opening
You can directly open `index.html` in any web browser (Chrome, Edge, Firefox, Safari):
- File location: `C:\Users\m ramani\.gemini\antigravity\scratch\aurora-x\index.html`

### Option 2: Run a Local Dev Server
In your terminal / PowerShell, navigate to this directory and start a lightweight server:

```powershell
# Using Python
python -m http.server 8000

# Using Node.js / npx
npx serve .
```

Then open [http://localhost:8000](http://localhost:8000) in your browser.

---

## 🌟 Included Features & Modules

1. **Interactive ASTRA-Med Cockpit**:
   - **Real-Time Canvas Oscilloscope**: Live animated multi-channel EEG traces (Frontal θ, Parietal α, Sensorimotor β) with motion artifact filtering.
   - **Live Telemetry Gauges**: Heart Rate (BPM), SpO₂, θ/β Fatigue Ratio, QML Cognitive State (NE / CA / DA / SS), and BB84 QBER rate.
   - **Crew Member Profiles**: Switch between CDR Hayes, Dr. Patel, and Spc. Chen.
   - **Interactive Scenario Simulation**:
     - *Normal Activity*: Nominal rest and focus baselines.
     - *EVA Fatigue Spike*: Triggers θ/β surge (+91%), high error risk warning, and automated suit cooling (+12%).
     - *Channelized Attention*: Simulates tunnel vision, depressed HRV (19ms), and audio advisory alert.
     - *QKD Eavesdrop Intercept*: QBER spikes above 11% threshold, triggering transmission lockout and biometric privacy protection.
     - *Cabin Fallback Mode*: Demonstrates zero-wearable mode inside spacecraft without helmet EEG.
   - **AI Flight Surgeon Crew Chat**: Interactive clinical Q&A powered by Google Gemini AI logic.

2. **Full Marketing & Scientific Landing Page**:
   - Dynamic Starfield and Nebula background.
   - Animated counter metrics for deep-space mission challenges.
   - 4-Stage Intelligent Pipeline diagram.
   - Scientific Foundation citations (NASA, ESA, PubMed Central).
   - Multi-phase mission development roadmap.
