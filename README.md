# Medical Insurance Charges Predictor

A Streamlit app that predicts medical insurance charges from personal details such as age, BMI, number of children, smoking status and region, using a pre-trained machine learning model.

**Live app:** [insurance-damian.streamlit.app](https://insurance-damian.streamlit.app/)

## Project files

- **app.py**: Streamlit interface and prediction logic.
- **insruance_charges.pkl**: the trained model used for predictions.
- **hospital.jpg**, **logo.png**: images shown in the app.
- **pyproject.toml** / **uv.lock**: project dependencies, managed with uv.

## Run locally

This project uses [uv](https://docs.astral.sh/uv/).

```bash
uv sync
uv run streamlit run app.py
```

The app opens at http://localhost:8501.

## Built with

- Python
- Streamlit
- scikit-learn
- pandas

## Disclaimer

For educational purposes only. Predictions are estimates and are not real insurance quotes.

## Author

Damian Oyinmiene Ozobokeme, SAIT
