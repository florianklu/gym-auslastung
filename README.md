# Gym Utilization Dataset

A dataset containing historical utilization data for fitness studios.

## Data Fields
Timestamps are in ISO 8601 format with UTC offset (e.g. `2026-01-01 15:00:00+01:00`)

### Hourly Utilization (`*_hourly_utilization.csv`)

- `start`: Start timestamp of the 1-hour interval.
- `end`: End timestamp of the 1-hour interval.
- `mean`: Time-weighted average capacity utilization percentage calculated over the 1-hour window.

---

## Studios
### FitX Paderborn-Südring
`FitX_Paderborn_hourly_utilization.csv`
- Opened in December 2024
- Dataset starts on `10-02-2025`
- Data for several weeks in June 2025 is missing
- Raw data points are randomly collected every 10 to 20 minutes

---

## Example Jupyter Notebook

The Jupyter notebook `gym_statistics.ipynb` contains some visulizations for the FitX Paderborn. Built with `pandas` and `matplotlib`.