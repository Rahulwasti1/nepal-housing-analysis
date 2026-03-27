# Nepal Housing Market Dashboard

---

## Requirements

```
pip install pandas numpy plotly jinja2
```

---

## How to Run

**Step 1** — Generate chart data:

```
python data_preparation.py
```

**Step 2** — Build the dashboard:

```
python generate_dashboard.py
```

**Step 3** — Open the output file in any browser:

```
dashboard.html
```

---

## Files

| File                               | Description                                             |
| ---------------------------------- | ------------------------------------------------------- |
| `Nepali_house_finally_cleaned.csv` | Dataset (2,128 rows)                                    |
| `data_preparation.py`              | Generates all charts and KPIs → saves `chart_data.json` |
| `generate_dashboard.py`            | Combines template + chart data → saves `dashboard.html` |
| `dashboard_template.html`          | HTML template (do not open directly)                    |
| `dashboard.html`                   | **Final dashboard — open this in browser**              |

---

## Notes

- All steps must be run from the same folder as the CSV file.
- `dashboard.html` is fully self-contained — no internet or Python needed to view it.
- Do not open `dashboard_template.html` directly in a browser.
