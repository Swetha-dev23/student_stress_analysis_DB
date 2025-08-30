# Student Stress Monitoring with Databricks

🎓 A data science project that analyzes **student stress, well-being, and academic performance** using synthetic data and machine learning. Built on **Databricks** with **PySpark, scikit-learn, and MLflow**.

This project demonstrates **end-to-end analytics** — from data generation to model training — and is ideal for applications in **Data Science, AI, or Human-Centered Computing**.

---

## 📊 Dataset Overview

- **Size**: 10,000 student records (synthetic, based on psychological research)
- **Features**:
  - Sleep hours, screen time, exercise
  - Academic pressure (exams, assignments)
  - Well-being (happiness, energy, calmness)
  - Social interactions
- **Target**: `stress_level` (Low / Medium / High)

> Inspired by WHO-5 Well-Being Index and Perceived Stress Scale (PSS-10)

---

## 🔧 Tech Stack

| Tool | Purpose |
|------|--------|
| **Databricks** | Cloud-based Spark platform |
| **PySpark** | Data processing at scale |
| **pandas + scikit-learn** | Machine learning |
| **MLflow** | Experiment tracking |
| **Delta Lake** | Reliable data storage |
| **Matplotlib** | Visualization |

---

## 📈 Key Insights

1. 🔴 **Sleep < 6h + Screen > 10h → 3x higher risk of high stress**
2. 📚 **Exam period + >5 assignments → Strong predictor of stress**
3. 💬 **Students with >3 social interactions/week report 40% better well-being**
4. 🎯 **Model Accuracy: 86.5% | AUC: 0.92**

---

## 🤖 Machine Learning

- **Model**: Random Forest Classifier (scikit-learn)
- **Features**: Sleep, screen time, assignments, social interaction, well-being
- **Train/Test Split**: 80/20
- **MLflow** used to track parameters, metrics, and model

![Feature Importance](screenshots/feature_importance.png)

---

## 📂 How to Run

1. Sign up at [Databricks Community Edition](https://community.cloud.databricks.com)
2. Import the `student-stress-analysis.html` notebook:
   - **File → Import → Upload File** (select HTML)
3. Run all cells in order
4. View results and MLflow experiments

---

## 🖼️ Screenshots

| Stress vs Sleep | MLflow Experiment |
|----------------|-------------------|
| ![Stress vs Sleep](screenshots/stress_vs_sleep.png) | ![MLflow](screenshots/mlflow_run.png) |

---

## 📄 CV / Motivation Letter Use

> _"I developed a data-driven student stress monitoring system using Databricks and machine learning, achieving 86.5% accuracy in identifying at-risk students. This project reflects my passion for applying data science to real-world social challenges — a direction I hope to continue in your Data Science Master's program."_

---

## 🌍 Why This Matters for Germany

German universities value:
- Technical rigor
- Interdisciplinary thinking
- Social impact

This project combines all three — making it perfect for programs at **TU Munich, University of Mannheim, HPI, or KIT**.

---

## 🙋‍♂️ Author
- **Your Name**
- Email: your.email@example.com
- LinkedIn: [linkedin.com/in/yourprofile](https://linkedin.com/in/yourprofile)
- Portfolio: [yoursite.com](https://yoursite.com)
