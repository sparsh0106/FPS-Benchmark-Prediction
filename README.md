
# 🎮 FPS Prediction Using CPU-GPU Specs and Game Settings

This repository contains a machine learning project that predicts the **Frames Per Second (FPS)** performance of various games based on a system's CPU, GPU, and game configuration. The model leverages hardware specs and setting information to forecast gaming performance, useful for gamers, system builders, and hardware reviewers.

Dataset link - [FPS Benchmark](https://www.kaggle.com/datasets/ulrikthygepedersen/fps-benchmark) - Uploaded by [Ulrik Thyge Pedersen](https://www.kaggle.com/ulrikthygepedersen)

---

## 📌 Project Highlights

- 🔍 **Data Preprocessing:** Cleaned and stripped byte-string artifacts, handled missing values, and converted categorical variables using one-hot encoding.
- 🧠 **Feature Engineering:** Extracted CPU/GPU brands, dropped irrelevant or redundant columns, and normalized the FPS target variable.
- 📊 **Exploratory Analysis:** Correlation analysis performed to find the most influential features on FPS.
- ⚙️ **Modeling Techniques:**
  - Linear Regression
  - Random Forest Regressor
  - XGBoost Regressor
- 🧪 **Hyperparameter Tuning:** GridSearchCV used for optimal parameter selection.

---

## 📁 Dataset

The dataset (`fps_benchmark.csv`) contains system hardware specifications and corresponding FPS results across various games and settings.

Features include:
- `CpuBrand`, `GpuBrand`
- GPU architecture, memory type, interface, DirectX/OpenGL/Vulkan support
- Game titles and settings
- CPU clock speeds and process size

---

## 📦 Requirements

Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn xgboost
