# Physics-Guided Synthetic Data for Ti-6Al-4V CNC Turning

This repository provides experimental and physics-guided synthetic datasets for CNC turning of the Ti-6Al-4V titanium alloy, widely used in biomedical implants such as femoral prostheses. The repository also includes Python scripts for synthetic data generation, statistical validation, and machine learning analysis.

The dataset was developed to address the limitations of small experimental samples in machining research, enabling robust data-driven modeling while preserving physically meaningful machining behavior.

---

## 📁 Repository Contents


---

## 🧪 Dataset Description

### Experimental Dataset
- **Samples:** 19
- **Design:** Central Composite Design (CCD)
- **Process:** CNC turning of Ti-6Al-4V under dry cutting conditions
- **Input variables:**
  - Cutting speed ($V_c$)
  - Feed rate ($f$)
  - Depth of cut ($a_p$)
- **Output variables:**
  - Surface roughness ($Ra$)
  - Cutting force components ($F_c$, $F_z$)

### Synthetic Dataset
- **Samples:** 1,710
- **Method:** Physics-guided synthetic data generation
- **Key features:**
  - Preserves marginal distributions and correlations
  - Constrained by machining physics and empirical trends
  - Statistically validated against experimental data

### Combined Dataset
- **Total samples:** 1,729
- Suitable for machine learning, statistical modeling, and optimization studies

---

## ⚙️ Methodology Overview

1. Experimental data acquisition using CNC turning tests
2. Identification of empirical and physical machining trends
3. Physics-guided synthetic data generation
4. Statistical validation (t-test, F-test, Kolmogorov–Smirnov test)
5. Correlation structure comparison
6. Machine learning validation (cross-validation and generalization)

---

## 🤖 Machine Learning Applications

The dataset supports:
- Surface roughness prediction
- Cutting force modeling
- Feature importance analysis
- Comparison of models trained on experimental vs. synthetic data

The repository includes scripts compatible with tree-based models (e.g., LightGBM) and standard regression workflows.

---

## ▶️ How to Run

1. Clone the repository:
```bash
git clone https://github.com/your-username/Physics_Guided_Synthetic_Data_for_Ti6Al4V_CNC_Turning.git
cd Physics_Guided_Synthetic_Data_for_Ti6Al4V_CNC_Turning


