# Anti-Detect Browser - Cross-Platform Fingerprint Spoofing

> A Chromium-based browser deeply customized for cross-platform OS fingerprint simulation, achieving near-perfect pass rates on mainstream browser fingerprinting detection platforms.

---

##  Core Features

- **Cross-Platform OS Emulation**: Supports fingerprint spoofing for Android, HarmonyOS, Windows, and macOS.
- **High Detection Pass Rates**: Fully passes FPJS Pro, largely passes CreepJS, and achieves 100% pass rate on Browserscan.
- **Development Environment**: Built on Linux with Chromium 153.

---

##  Fingerprint Detection Status

| Detection Platform | Status |
| :--- | :--- |
| **FPJS Pro** | 🟢 Fully Passed |
| **CreepJS** | 🟡 Largely Passed |
| **Browserscan** | 🟢 100% Passed |
| **PixelScan** | ⚠️ HarmonyOS not recognized (Theoretically fully compatible) |

---

##  Current Optimization Roadmap

### 1. TAM Score Reduction
- **macOS**: Current TAM score fluctuates between **0.64 ~ 0.75**. Further reduction is required.
- **Windows**: Current TAM score fluctuates between **0.30 ~ 0.45**. Optimization is ongoing to lower this metric.

### 2. WebGPU Support
- WebGPU is currently **uniformly disabled** on PC endpoints.
- **Next Step**: Categorize supported GPU models within the library to gradually enable and optimize WebGPU support.

### 3. iOS Kernel Adaptation
- Due to current kernel limitations, iOS emulation requires a separate development path using the iOS kernel.
- iOS system simulation is **not yet supported**.

---

##  Contact

For collaboration or technical inquiries, please contact via WeChat: **xingzhe11011**

---

##  Disclaimer

This project is intended solely for technical research and educational purposes. Do not use it for any illegal or unauthorized activities. Users assume full responsibility for their actions.
