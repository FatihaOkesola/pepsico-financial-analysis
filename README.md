# PepsiCo Financial Statement Analysis

Profitability drivers, earnings quality and financial position of PepsiCo, Inc. (NYSE: PEP), fiscal years 2017–2025, using CFA Level II financial statement analysis frameworks.

## Question

What has driven PepsiCo's profitability from 2017 to 2025, how sustainable are its earnings, and is its financial position strong enough to support them?

## Data

All figures come from PepsiCo's annual reports on Form 10-K, filed with the SEC. Financial statement data is extracted from SEC EDGAR's XBRL company facts and validated against the printed 10-Ks: all 210 extracted values from 2017 to 2025 match the filings. Segment results, gross interest expense, one-off items and the foreign exchange effect on revenue growth come from the notes and MD&A of the filings. Every value records the filing it came from.

## Repository

| Folder | Contents |
| --- | --- |
| `data/` | `01_data_extraction.ipynb`: extraction, validation against the filings, segment reconciliation and export |
| `analysis/` | `PepsiCo_FSA.xlsx`: verified data and the analysis workbook |

## Status

Data extraction and validation complete. Analysis in progress.
