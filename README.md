# Insurance Claims Data Validator

Automated testing framework for validating insurance claims data quality.

## What It Does
- Validates claims data for missing values, duplicates, and invalid entries
- Checks business rules (valid amounts, dates, policy formats)
- Generates detailed validation reports

## Files
- `generate_sample_data.py` - Creates test dataset
- `test_claims_validator.py` - Validation framework
- `sample_claims_data.csv` - Sample data with intentional issues

## How to Run
```bash
python generate_sample_data.py
python test_claims_validator.py
```

## Technologies
Python, pandas, pytest
