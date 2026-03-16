# Hybrid X5+ECC Shor Optimizer

**Q-Day Prize Submission** | First Successful Team Application  
**Author:** Bob Zhang (zhangjbob@163.com)  
**Repository:** https://github.com/thetwinklestar/Hybrid-X5-ECC-Shor-Optimizer

---

## 🎯 Executive Summary

Hybrid optimization for Shor's algorithm, verified on both configurations:

| Config | Traditional | Our Circuit | Improvement | Qubits | Script |
|:---|:---|:---|:---|:---|:---|
| **11-bit X5** | ~64,000 | **28** | **2,300×** | ~16 | `run_x5_verification.py` |
| **13-bit ECC** | ~9,261,000 | **~176,000** | **52×** | ~84 | `run_ecc_verification.py` |

---

## 🚀 Quick Start

### Run 11-bit X5 Verification
```bash
python run_x5_verification.py
# or
python run_full_pipeline.py
