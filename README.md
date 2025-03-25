# Hybrid Quantum-Classical Neural Network for Stock Prediction (HQNN-FSP) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)]([https://colab.research.google.com/drive/1AEPsaRdVnWaS_a9bELVf3rPc8MUt6qU2?usp=sharing])

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Python 3.10+](https://img.shields.io/badge/python-3.10+-blue.svg)](https://www.python.org/downloads/)
[![Qiskit](https://img.shields.io/badge/Qiskit-1.0+-blue.svg)](https://qiskit.org)

**Implementation Status**: Early Development (Paper WIP)  
**Current Focus**: Quantum Data Encoding (Sec. III.B of Paper)  

## 📌 Project Overview
This repository implements *"HQNN-FSP: A Hybrid Classical-Quantum Neural Network for Regression-Based Financial Stock Prediction"* (Choudhary et al.).  

**Goal**: Reproduce and extend the paper's hybrid quantum-classical architecture for stock market forecasting.

---

## 🚀 Current Progress
### ✅ Implemented Features
- **Quantum Data Encoding** (Sec. III.B):
  - Angle encoding with `RY`/`RZ` rotations
  - Technical indicator preprocessing (RSI, MACD)
  - Bloch sphere visualization 

### 📝 Next Steps (Paper Sections to Implement)
| Section | Task | Status |
|---------|------|--------|
| III.C   | HybridQNN1 (Classical → Quantum) | ⏳ Pending |
| III.D   | HybridQNN2 (Joint Optimization) | ⏳ Pending |
| IV      | Benchmarking vs Classical Models | ⏳ Pending |

---

## 🛠️ Installation
```bash
git clone https://github.com/yourusername/Hybrid-QNN-Finance.git
cd Hybrid-QNN-Finance
pip install -r requirements.txt
