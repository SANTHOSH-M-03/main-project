ai-threat-detection/
|
|-- data/
|   |-- raw/            # original downloaded CICIDS 2017 CSV files
|   |-- cleaned/        # after removing nulls, duplicates, infinities
|   |-- processed/      # normalized train/test splits (X_train, X_test, etc.)
|
|-- models/             # saved trained model files (.pkl / .keras)
|-- notebooks/          # all Jupyter notebooks (EDA, training, evaluation)
|-- src/                # production Python pipeline scripts
|   |-- __init__.py
|   |-- preprocess.py   # data cleaning and feature engineering
|   |-- train.py        # model training and saving
|   |-- detect.py       # real-time threat detection engine
|   |-- alert.py        # email and AWS SNS alert system
|
|-- logs/               # detection output logs (CSV / JSON)
|-- reports/            # weekly reports, charts, architecture diagram
|-- tests/              # test scripts for pipeline validation
|-- app.py              # Streamlit dashboard
|-- requirements.txt    # all Python dependencies
|-- .gitignore
|-- PROJECT_SCOPE.md    # project objectives and scope
