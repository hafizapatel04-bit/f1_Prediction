🏎️ F1 RACE PREDICTION

A machine learning project for analyzing Formula 1 race data and predicting driver race performance using historical F1 data.

📌 OVERVIEW

This project uses FastF1 to collect Formula 1 race data and applies machine learning techniques to analyze driver and race performance.

The pipeline covers:

Data Collection → Data Preprocessing → Feature Engineering → Model Training → Evaluation → Race Prediction

The goal is to use historical race information to build a data-driven prediction system for Formula 1 race outcomes.

🚀 FEATURES

🏁 Historical F1 race data collection using FastF1

📊 Data preprocessing and exploratory analysis

⚙️ Feature engineering from race and driver performance data

🤖 Machine learning-based race prediction

📈 Model evaluation and performance analysis

🏎️ Driver and race-performance analysis

📉 Prediction visualization

🛠️ TECH STACK

| Category | Technologies |

| Language | Python |

| F1 Data | FastF1 |

| Data Processing | Pandas, NumPy |

| Machine Learning | Scikit-learn, XGBoost, LightGBM |

| Visualization | Matplotlib, Seaborn |

| Development | Jupyter Notebook, Git, GitHub |

🔄 PROJECT WORKFLOW

                 F1 Historical Data
                         │
                         ▼
                   Data Collection
                       FastF1
                         │
                         ▼
                Data Preprocessing
                         │
                         ▼
                 Feature Engineering
                         │
                         ▼
                  Model Training
              ┌──────────┼──────────┐
              ▼          ▼          ▼
           Baseline   XGBoost    LightGBM
              │          │          │
              └──────────┼──────────┘
                         ▼
                   Model Evaluation
                         │
                         ▼
                   Race Prediction
                         │
                         ▼
                  Result Visualization

📊 DATA

The project uses Formula 1 data obtained through the FastF1 Python library, which provides access to historical F1 session, timing, telemetry, and race-related data.

The collected data is processed to create features suitable for machine learning.

⚙️ FEATURE ENGINEERING

The prediction pipeline can incorporate race-performance information such as:

Driver performance

Qualifying position

Previous race performance

Team performance

Race-specific characteristics

Historical performance trends

🤖 MACHINE LEARNING

The project evaluates machine learning approaches for predicting race performance.

Models used include:

Baseline model

Random Forest

XGBoost

LightGBM

Model performance is evaluated using appropriate regression/classification metrics depending on the prediction target.

💻 INSTALLATION

1. Clone the repository

git clone https://github.com/hafizapatel04-bit/f1_Prediction.git
cd f1_Prediction

2. Create a virtual environment

python -m venv venv

Activate it on Windows:

venv\Scripts\activate

On macOS/Linux:

source venv/bin/activate

3. Install dependencies

pip install -r requirements.txt

▶️ USAGE

Run the project's main notebook/script according to the repository structure.

For notebooks:

jupyter notebook

Then open the relevant notebook and execute the data collection, preprocessing, training, and prediction workflow.

📁 PROJECT STRUCTURE

f1_Prediction/
│
├── data/
├── notebooks/
├── src/
├── requirements.txt
├── README.md
└── ...

🔮 FUTURE IMPROVEMENTS

Add more seasons of historical data

Improve driver and constructor performance features

Implement time-based cross-validation

Compare additional machine learning models

Add SHAP-based model explainability

Generate probabilistic finishing-position predictions

Build an interactive Streamlit dashboard

Compare predicted results with actual race results

⚠️ LIMITATIONS

F1 race results are influenced by many unpredictable factors, including:

Safety Cars and red flags

Mechanical failures

Strategy decisions

Weather changes

Driver incidents

Penalties

Therefore, predictions should be treated as data-driven estimates rather than guaranteed race outcomes.

📚 DATA & LIBRARIES

This project uses the FastF1 Python library for Formula 1 data.

👤 AUTHOR

Hafiza Patel

GitHub: https://github.com/hafizapatel04-bit

Project: https://github.com/hafizapatel04-bit/f1_Prediction

📄 LICENSE

This project is intended for educational and research purposes.
