# Inverse Analysis and Hybrid Reinforced Concrete (HRC) Design Software

**Version:** Beta  
**Developer:** Devansh Patel  
**Contact:** dpatel52@asu.edu  
**Platform:** MATLAB Standalone Application (No MATLAB license required)

---

## 🔍 Overview

This software provides a standalone graphical interface for performing inverse analysis, moment-curvature simulation, and design of fiber-reinforced concrete (FRC), ultra-high-performance concrete (UHPC), and hybrid reinforced concrete (HRC) sections.

Built using closed-form analytical models, the software is capable of:
- Simulating the complete flexural response of FRC/UHPC beams
- Performing inverse analysis using EN 14651 or ASTM C1609 test data
- Modeling tension, compression, and reinforcement behavior using parametric stress-strain laws
- Real-time visualization of stress/strain distribution, moment-curvature, and load-deflection plots
- Generating PDF and Excel reports for documentation and design use

---

## 📥 Installation

This application is distributed as a **standalone MATLAB executable**, and **does not require a MATLAB license**.

### ⚠️ Important Notes:
- During installation, the software will **download MATLAB Runtime** (~1 GB) from the web. Installation time may vary depending on your internet speed.
- You may encounter a **Microsoft Defender SmartScreen warning**. This is expected for new applications not yet digitally signed.  
  Click **“More Info” → “Run Anyway”** to proceed.
- The software is safe and poses no security risk.

If you face any installation issues, contact: **dpatel52@asu.edu**

---

## 🚀 Features

- Supports both **US Customary** and **SI unit systems**
- Input and visualization of:
  - Geometry
  - Tension model (quad-linear)
  - Compression model (bilinear)
  - Reinforcement model (bilinear)
- Output plots:
  - Moment-Curvature
  - Load-Deflection
  - Moment vs. Beta
  - Stress and Force Distribution
- Inverse analysis from experimental flexural data
- Export results to:
  - PDF reports
  - Excel files (.xlsx)
- Save/load full project workspaces (.mat)

---

## 🧪 Inverse Analysis Support

Upload your experimental data in `.xlsx` format:  
- **Column 1:** Deflection (mm or inches)  
- **Column 2:** Load (N or lbf)  

Supported test methods:
- ASTM C1609  
- EN 14651
---

## 📖 Citation

If you use this tool in your research or publication, please cite:

> Patel, D. (2024). [*Validation of Generalized Moment-Curvature Model for Limit State Design of Reinforced UHPC Flexure Members*](https://doi.org/10.1061/JSENDH.STENG-12235), Journal of Structural Engineering.

---

## 💬 Support & Collaboration

For feature requests, bug reports, or collaboration inquiries, please contact:  
**dpatel52@asu.edu**

---

## ⚠️ Disclaimer

This software is provided as-is for research and educational purposes. While efforts have been made to ensure accuracy and reliability, the developer is not liable for any outcomes resulting from its use. Users should verify results independently before applying them to design decisions.

