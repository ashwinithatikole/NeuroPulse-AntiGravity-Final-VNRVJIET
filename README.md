# NeuroPulse: Edge-AI Seizure Detection (Team AntiGravity)

## 📌 Project Overview
NeuroPulse is a high-performance, low-power seizure detection engine designed for real-time edge processing on FPGA. Developed by **Team AntiGravity**, this system implements an optimized 1D-CNN architecture specialized for the CHB-MIT Scalp EEG dataset. Our implementation focuses on achieving ultra-low latency and minimal resource consumption for next-generation wearable medical devices.

---

## 📊 Performance Metrics (Verified)
The following metrics represent the finalized hardware implementation on a Xilinx Zynq-7000 series FPGA.

| Metric | Value |
| :--- | :--- |
| **Latency** | **145 ns** |
| **Total On-Chip Power** | **108 mW** |
| **LUT Usage** | **0.20%** |
| **Timing Slack** | **3.106 ns** |

---

## 🖼️ Visual Proof

### Simulation Waveform
![Simulation Waveform](./docs/results/waveform.png)
*Behaviourial simulation showing SEIZURE_DETECTED trigger and signal synchronization.*

### Power Analysis
![Power Analysis](./docs/results/power.png)
*Xilinx Vivado Power Report showing industry-leading efficiency.*

### RTL Schematic
![RTL Schematic](./docs/results/schematic.png)
*Detailed hardware architecture featuring optimized MAC units and activation layers.*

### Utilization Report
![Utilization Report](./docs/results/utilization.png)
*Resource utilization audit confirming minimal footprint.*

---

## 📂 Repository Structure
```bash
├── const/          # Xilinx Vivado Constraints (.xdc)
├── sim/            # Simulation Testbenches
├── src/            # Core RTL Verilog Source Code
└── docs/results/   # Verified Hardware Metrics & Proof
```

---

## 🤝 Team Info
**T.Ashwini
R.Tanuja**
VNR VJIET

---

## 🛡️ License
This project is licensed under the MIT License - see the LICENSE file for details.
