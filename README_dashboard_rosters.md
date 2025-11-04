
# WFP–TPM Dashboard (Streamlit) — Named Rosters + Excel Export

Adds **named monitor rosters** with **capacity** and **base Woreda preference**, plus **Excel export** (multi‑sheet) and **PDF export**.

## Roster options
- **Single combined file**: `monitor_name`, `org` (`WFP`/`TPM`), `capacity`, `base_woreda` *(optional; `(any)` if flexible)*.
- **Separate files**: one for **WFP** and one for **TPM** with `monitor_name`, `capacity`, `base_woreda` *(optional)*.

## Data export
- **Excel export** (button: *Download Excel (allocations, coverage, monitor_load)*)
  - Sheets: `allocations`, `coverage`, and `monitor_load` (if rosters enabled).
- **PDF export** with KPIs, bar & pie charts, coverage table, and optional monitor-load page.

## Quick start
```bash
python -m venv .venv
source .venv/bin/activate   # Windows: .venv\Scripts\activate
pip install -r requirements_dashboard.txt
streamlit run dashboard_app.py
```
