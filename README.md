python -m venv venv          # optional but recommended
source venv/bin/activate     # macOS/Linux
# .venvScriptsactivate     # Windows PowerShell
pip install --upgrade pip
pip install scikit-learn matplotlib seaborn jupyter
iris-classifier/
├── data/ # (empty – Iris is loaded from scikit‑learn)
├── notebooks/
│ └── iris_model.ipynb # walk‑through notebook
├── src/
│ └── train.py # reproducible CLI script
├── tests/
│ └── test_train.py # basic pytest
├── outputs/ # created automatically (model & figures)
├── .gitignore
├── LICENSE
├── README.md
└── requirements.txt
