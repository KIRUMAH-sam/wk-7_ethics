# 🧠 AI Ethics Fairness Audit — COMPAS Dataset

This project performs a fairness audit on the COMPAS recidivism prediction system using **IBM's AI Fairness 360 (AIF360)**. The goal is to identify, measure, and mitigate racial bias in automated risk assessment systems.

---

## 📌 Project Objectives

- Analyze the COMPAS dataset for racial bias  
- Compute key fairness metrics  
- Visualize disparities between racial groups  
- Apply fairness mitigation techniques  
- Produce an ethics-grounded interpretation of results  

---

## 📂 Project Structure

```
📁 root
├── audit.ipynb          # Full fairness audit notebook
├── report.pdf              # Written report (Part 1–4)
├── data/                   # COMPAS dataset (if stored locally)
├── README.md               # This file
```

---

## 🛠️ Tools & Libraries

- **AIF360** — Bias detection & mitigation  
- **Pandas** — Data processing  
- **Matplotlib** — Visualizations  
- **Numpy** — Numerical operations  

---

## 📊 Fairness Metrics Computed

- **Disparate Impact**  
- **Mean Difference**  
- **False Positive Rate (FPR) Difference**  
- **Group-wise risk score comparison**  

---

## 🧪 How to Run the Notebook

1. Install required libraries:

```bash
pip install aif360 pandas numpy matplotlib
```

2. Launch Jupyter Notebook:

```bash
jupyter notebook
```

3. Open `audit.ipynb` and run all cells.

---

## 🎯 Key Findings (Summary)

- COMPAS exhibits **significant racial bias** against African-American defendants.
- **Disparate Impact < 0.8**, failing the 80% fairness rule.
- African-Americans face **much higher false positive rates**, meaning they are more often classified as "high risk" even when they do not reoffend.
- Bias mitigation using **Reweighing** improves fairness but does not fully eliminate disparities.

---

## 🧩 Ethical Principles Applied

- **Justice** — Ensuring fairness across demographic groups  
- **Non-maleficence** — Preventing harm caused by biased predictions  
- **Transparency** — Measuring algorithmic behavior  
- **Accountability** — Auditing and documenting bias  

---



