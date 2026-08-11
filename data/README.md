# Data

Python scripts for SEC EDGAR XBRL extraction and yfinance market data.

## Files

| File | Description |
|---|---|
| `data_extraction.ipynb` | SEC EDGAR XBRL extraction script — pulls income statement and balance sheet data for FY2019-2025. Outputs to Raw Data sheet in PepsiCo_FSA.xlsx |

## Notes
- All financial data extracted in USD millions
- Source: SEC EDGAR XBRL API (data.sec.gov)
- Fiscal year labelling corrected to use period end date rather than EDGAR fy tag
- Run cells individually — do not use Run All due to network request timing
