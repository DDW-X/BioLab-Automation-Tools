# HSAA Enzyme Kinetics Automation Pipeline 🧬

This project provides an automated workflow for analyzing **Human Salivary Alpha-Amylase (HSAA)** kinetics using **n8n**.

## 🚀 Features
- **Automated Data Ingestion:** Processes raw spectrophotometer data.
- **Biochemical Analysis:** Calculates $V_{max}$ and $K_m$ using **Lineweaver-Burk** transformation.
- **Quality Control:** Automatically flags assays with low calibration $R^2$.
- **Visualization:** Generates Michaelis-Menten saturation curves dynamically.
- **Reporting:** Outputs a scientifically formatted report in Persian/English.

## 🛠 Usage
1. Import `HSAA_Enzyme_Kinetics.json` into your n8n instance.
2. Trigger the workflow (Manual or Webhook).
3. Receive the analysis report instantly.

## 🔬 Mathematical Model
The workflow implements the linearized Michaelis-Menten equation:
$$\frac{1}{V_0} = \frac{K_m}{V_{max}[S]} + \frac{1}{V_{max}}$$

---
*Created by [Your Name] - Cybersecurity & Bio-Research Specialist*
