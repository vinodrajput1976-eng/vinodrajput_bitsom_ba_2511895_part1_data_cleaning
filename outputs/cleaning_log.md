# Cleaning Log
Issues found: missing region, missing ship_mode, missing discounts, duplicate records, invalid dates, invalid discounts.
Actions: trimmed text, standardized case, parsed dates, filled Unknown values, calculated metrics.
Business Rules: missing region/ship mode -> Unknown; missing discount -> 0 if valid; invalid discounts flagged.
Records removed: 0
Records flagged: see report.
Limitations: automated standardization and date parsing assumptions.
