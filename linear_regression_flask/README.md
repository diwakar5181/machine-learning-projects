# Forest Fire Weather Index Predictor

A Flask web application that predicts the **Fire Weather Index (FWI)** from weather and fire-behaviour measurements in the Algerian Forest Fires dataset. The app uses a trained Ridge Regression model and a saved `StandardScaler` to apply the same preprocessing used during training.

## Features

- Browser form for entering nine model inputs
- Ridge Regression prediction served by Flask
- Persisted model and feature scaler in `models/`
- Training and experimentation notebook in `notebooks/RidgeLassoEllasticNet.ipynb`

## Project structure

```text
linear_regression_flask/
├── data/raw/Algerian_forest_fires_dataset.csv  # Source dataset
├── models/
│   ├── ridge.pkl                               # Trained Ridge model
│   └── scaler.pkl                              # Fitted StandardScaler
├── notebooks/RidgeLassoEllasticNet.ipynb       # Model development notebook
├── src/application.py                           # Flask application
├── templates/                                  # HTML pages
└── requirements.txt                            # Python dependencies
```

## Setup and run

From the project directory:

```bash
cd linear_regression_flask
python -m venv .venv
source .venv/bin/activate        # Windows: .venv\\Scripts\\activate
pip install -r requirements.txt
python src/application.py
```

Then open [http://localhost:8080](http://localhost:8080) in a browser.

## Input fields

Submit numeric values for the following features:

| Field | Meaning |
| --- | --- |
| `Temperature` | Air temperature |
| `RH` | Relative humidity |
| `Ws` | Wind speed |
| `Rain` | Rainfall |
| `FFMC` | Fine Fuel Moisture Code |
| `DMC` | Duff Moisture Code |
| `ISI` | Initial Spread Index |
| `Classes` | Fire/no-fire class encoded numerically |
| `Region` | Dataset region encoded numerically |

The application standardizes these values with `scaler.pkl` before passing them to `ridge.pkl`, then displays the predicted FWI.

## Routes

| Route | Methods | Purpose |
| --- | --- | --- |
| `/` | `GET` | Displays the landing page. |
| `/predictdata` | `GET`, `POST` | Shows the prediction form and processes submitted values. |

## Development

The saved artifacts are already included, so retraining is not required to run the app. To explore or retrain the model, use `notebooks/RidgeLassoEllasticNet.ipynb` with the CSV in `data/raw/`.
