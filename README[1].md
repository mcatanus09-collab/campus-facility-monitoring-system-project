# Campus Facility Monitoring System

A Streamlit decision-support dashboard for campus facility reservations, exploratory analysis,
and Decision Tree-based reservation outcome prediction.

## Run locally
```bash
pip install -r requirements.txt
streamlit run app.py
```

The app loads `facility_reservations.csv` from the project folder by default. You can also upload
a CSV or Excel file in the sidebar.

## Streamlit Cloud
- Repository: `mcatanus09-collab/campus-facility-monitoring-system`
- Branch: `main`
- Main file: `app.py`

Predictions are estimates for human review and must not automatically reject reservations.
