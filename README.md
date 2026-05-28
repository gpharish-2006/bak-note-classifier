# Bank Note Authentication Classifier
A machine learning service to classify banknotes as genuine or counterfeit using the UCI Banknote Authentication dataset from Kaggle.

# Setup & Installation
## Install uv if not already available

```bash
pip install uv
```

## Initialize the project

```bash
git clone https://github.com/gpharish-2006/bank-note-classifier.git

cd bank-note-classifier

uv init
```

## Create a virtual environment
```bash
uv venv
```

## Activate the virtual environment
```bash
source .venv/bin/activate  # Linux/macOS

.venv\Scripts\activate   # Windows
```

## Install dependencies
```bash
uv add -r requirements.txt
```

# Running the Application
## Run directly
```bash
python app.py
```

## Or with Uvicorn for auto-reload (development)
```bash
uvicorn app:app --reload
```

The API will be accessible at http://127.0.0.1:8000
