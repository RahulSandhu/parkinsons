<div align="justify">

# Parkinson's Disease Modeling API

This repository contains the complete workflow for modeling Parkinson’s disease
progression using K-Nearest Neighbors (KNN) and integrating the final model
into a minimal API for real-time prediction. The project includes code for data
processing, model training, and API deployment.

## 📝 Project

```
├── data/                   # Raw, processed, and dummy datasets
│   ├── dummy/              # Example data for testing the API
│   ├── processed/          # Cleaned dataset
│   └── raw/                # Original dataset 
├── images/                 # All generated visualizations
│   ├── api/                # API-related flowcharts or screenshots
│   ├── feature_selection/  # Feature selection visualizations
│   └── logos/              # Logos
├── misc/                   # Additional files
│   ├── guide.pdf           # Project guide
│   └── refs.bib            # References for report
├── report/                 # Final project report
├── results/                # Output folders with metrics, logs, and model files
├── src/                    # Source code for modeling and API
│   ├── api/                # FastAPI implementation for model inference
│   ├── main.py             # Model generation
│   ├── model/              # Model training and inference logic
│   └── processing/         # Feature selection and data preprocessing
├── videos/                 # Walktrough demo video
├── LICENSE                 # License file
├── pyproject.toml          # Python project configuration
├── requirements.txt        # Python dependencies
└── README.md               # Project overview
```

## 🚀 Setup

1. **Clone the repository**

   ```bash
   git clone https://github.com/RahulSandhu/parkinsons
   cd parkinsons
   ```

2. **Create and activate a virtual environment**

   ```bash
   python3 -m venv venv
   source venv/bin/activate
   ```

3. **Install dependencies**

   ```bash
   pip install -r requirements.txt
   ```

## 🖥️ Source

* `src/api/`: FastAPI app and endpoint logic
* `src/main.py`: Entrypoint to launch the API server
* `src/model/`: KNN model training, saving, and loading functions
* `src/processing/`: Data preprocessing, feature engineering, and selection

## 📁 Data

* `data/raw/`: Original Parkinson’s disease dataset (e.g., extracted from
external sources)
* `data/processed/`: Cleaned and transformed data used for modeling
* `data/dummy/`: Synthetic examples used for testing the API

## 📊 Results

* `results/YYYY-MM-DD_HH-MM-SS/`: Timestamped directories containing evaluation
results, model files, and logs
* Best performance achieved by normalized KNN model with 97% accuracy at k = 4

## 📈 Figures

All visual outputs from the project are saved in the `images/` directory:

* Feature selection visualizations
* API diagrams and testing examples
* Project logos

## 📚 License

This project is licensed under the terms of the [LICENSE](LICENSE) file.

## 🎓 Acknowledgements

* Dataset used for modeling Parkinson’s disease
* Developed as part of the Health Data Science Master’s program at Universitat
Rovira i Virgili (URV)

</div>
