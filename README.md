# FPS Prediction from Hardware Specifications

A Jupyter notebook for exploring game performance data and predicting frames per second from CPU, GPU, and game-setting features. The notebook cleans the tabular data, engineers hardware features, and compares regression models.

## Dataset

The notebook expects a file named `fps_benchmark.csv` in the repository root. Download the [FPS Benchmark dataset on Kaggle](https://www.kaggle.com/datasets/ulrikthygepedersen/fps-benchmark), review its license, and place the CSV at that path before running the notebook. The dataset is not included here.

## Run locally

```bash
git clone https://github.com/sparsh0106/FPS-Benchmark-Prediction.git
cd FPS-Benchmark-Prediction
python -m pip install pandas numpy matplotlib seaborn scikit-learn xgboost jupyter
jupyter notebook main.ipynb
```

## Scope

This is an educational benchmark on one dataset. Predictions are estimates for the data represented in the notebook and are not guaranteed FPS measurements for a particular computer.
