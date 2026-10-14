# Example data

These 10 rows are synthetic and anonymized. They are included so you
can see what a realistic "leads log" looks like once you start filling
in the templates from `../templates/`. The city codes (C1, C2, R1, R2,
M1, M2) are placeholders, not real locations.

Columns mirror the `templates/leads-log.csv` schema, with one addition:

- `revenue_usd` - the realized revenue from this lead, in USD-equivalent.
  It is the field you will use when you want to measure the actual
  ROI of a given source.
