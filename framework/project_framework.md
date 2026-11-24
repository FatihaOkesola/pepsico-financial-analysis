# PepsiCo Financial Statement Analysis: Project Framework

**Fatiha Okesola** · November 2026

A financial statement analysis of PepsiCo, Inc. (NYSE: PEP) for fiscal years 2017 to 2025, built on the CFA Level II frameworks for financial statement analysis and the quality of financial reports.

## Contents

- [1. Purpose](#1-purpose)
- [2. Scope](#2-scope)
- [3. Data](#3-data)
- [4. Comparability](#4-comparability)
- [5. Analysis](#5-analysis)
- [6. Conventions](#6-conventions)

## 1. Purpose

The analysis answers one question:

> **What has driven PepsiCo's profitability from 2017 to 2025, how sustainable are its earnings, and is its financial position strong enough to support them?**

It follows the CFA framework for financial statement analysis, which starts from the purpose of the analysis and selects only the techniques that serve it. Each section of the analysis asks one question and ends with one conclusion that answers it.

Across the period, the analysis also tests which description fits PepsiCo's performance after 2019: a recovery, a structural improvement, a continuation of the pre-COVID trend, or no material overall disruption with effects differing by segment. Consolidated revenue rose in 2020, so a fall-and-recovery pattern is not assumed.

**Why PepsiCo.** Its 10-K filings disclose in detail the areas the CFA readings examine: segment results, pensions, goodwill and intangible assets, taxes, leases and foreign currency. It operates in more than 200 countries across beverages and convenient foods, and the period includes events that test earnings quality directly: COVID, the 2021–2022 cost inflation, the Russia-Ukraine conflict, the sale of Tropicana and related juice brands, and a large brand impairment in 2025.

## 2. Scope

| Item | Coverage |
| --- | --- |
| Company | PepsiCo, Inc. on its own; trends are read against PepsiCo's own history |
| Period | Fiscal years 2017 to 2025 |
| Standard | US GAAP, as reported in PepsiCo's annual reports on Form 10-K |
| Income statement and cash flow measures | From 2017 |
| Balance-sheet and accruals measures | From 2018, using the 2017 balance sheet as the opening balance |

The years are grouped by date. The findings, not the labels, decide what each group represents.

| Period | Role in the analysis |
| --- | --- |
| 2017–2019 | Pre-COVID reference period. Its direction (rising, flat or falling) matters as much as its level. Because 2017 and 2018 carry large tax items, operating margin and cash flow are the more reliable reference measures, not net margin |
| 2020 | The COVID year |
| 2021–2023 | The years after 2020 |
| 2024–2025 | The latest years |

## 3. Data

**Sources.** Financial statement data comes from SEC EDGAR's XBRL company facts for PepsiCo (CIK 0000077476). The 10-K filings themselves are the authority for context and judgement, and for figures that XBRL does not carry reliably.

**Selecting one value per year.** Each line item has several candidate values per year, because every 10-K repeats prior years and older filings include quarterly results. One value is selected by fixed rules:

1. Annual filings only (forms 10-K and 10-K/A).
2. For income statement and cash flow items, full-year periods only: the period must be longer than 350 days. PepsiCo's quarters run 83 days, or 111 days for the fourth quarter.
3. Each value is assigned to a fiscal year by its period end date, not by the filing's fiscal-year label.
4. Where a year is reported in more than one filing, the most recently filed value is used, so every year reflects PepsiCo's latest presentation. A tie is broken by the later accession number.
5. The accession number of the source filing is kept for every value.

**Validation.** Every extracted value is compared with the figure printed in the most recent 10-K that reports that year. All 210 values from 2017 to 2025 match. Segment revenue reconciles to consolidated revenue, and segment operating profit plus corporate unallocated expenses reconciles to consolidated operating profit, in every year on both segment structures.

**Figures taken from the filings directly.** Some figures are entered from the 10-Ks, with the filing and page recorded:

| Figure | Reason |
| --- | --- |
| Gross interest expense | The XBRL interest tag carries gross interest for 2017 and net interest from 2018 onwards, after PepsiCo moved to net presentation |
| Segment revenue and operating profit | Reported only in the segment note |
| Other pension and retiree medical benefits, and net interest expense | Needed to bridge operating profit to income before taxes |
| Foreign exchange effect on revenue growth | Stated in each year's MD&A reconciliation of reported to organic growth |
| One-off items and recurring charges | Stated in the notes and in PepsiCo's reconciliation of items affecting comparability |

## 4. Comparability

| Matter | Effect | Treatment |
| --- | --- | --- |
| Restated 2017 figures | From 2018 PepsiCo reports pension and retiree medical income below operating profit, lowering 2017 operating profit from $10,509 million as first reported to $10,276 million. Cash flows are reconciled to cash plus restricted cash, raising 2017 cash from operations by $36 million, the increase in restricted cash that year | The restated figures are used |
| Revenue recognition (2018) | Certain sales, use, value-added and excise taxes are excluded from net revenue from 2018, about $75 million in 2018 | Caveat on revenue growth involving 2017; no adjustment |
| US tax rate | The Tax Cuts and Jobs Act lowered the US corporate rate from 35% to 21% from 2018 | 2017 net margin carries a caveat |
| Leases (2019) | Operating leases came onto the balance sheet; right-of-use assets were $1,548 million at the end of 2019, about 2% of total assets | Noted; no adjustment |
| Week count | Fiscal 2022 contained 53 weeks | Noted where it affects year-on-year growth |
| Segment structure | Seven segments through fiscal 2024; six segments from fiscal 2025. The fiscal 2024 10-K reports 2022–2024 on seven segments and the fiscal 2025 10-K recasts 2023–2024 onto six | Two series: seven segments for 2017–2024, six for 2023–2025. Each structure is compared only with itself |

**Why the earlier years are not restated onto six segments.** PepsiCo's current six-segment structure is not a simple regrouping of its earlier seven-segment structure. Although North America can be mapped cleanly (PFNA equals FLNA plus QFNA, and PBNA is unchanged, as the 2023 and 2024 figures reported on both structures confirm), the international segments were reorganised by both geography and type of business. PepsiCo did not publish the historical profit splits needed to restate 2017–2022 reliably. This analysis therefore keeps PepsiCo's reported seven-segment structure through 2024 and uses the reported six-segment structure for 2023–2025, with the overlapping years providing context for the transition. Creating a single six-segment series would require estimates based partly on revenue shares rounded to the nearest 5%, and would introduce false precision.

## 5. Analysis

### Section 1: Business and operating performance

**Question:** What drives PepsiCo's profitability, and how has that changed?

- Business context: what PepsiCo sells, how it reaches customers, its segments and where its revenue comes from.
- Revenue growth each year, with the foreign exchange effect in percentage points.
- Segment revenue mix and segment operating margins, reported and normalised.
- Gross, operating and net margins from 2017 to 2025.
- Five-part DuPont analysis from 2018, on reported and normalised earnings:

| Factor | Formula |
| --- | --- |
| Tax burden (attributable basis) | Net income attributable to PepsiCo / income before income taxes |
| Interest burden | Income before income taxes / operating profit |
| EBIT margin | Operating profit / net revenue |
| Asset turnover | Net revenue / average total assets |
| Financial leverage | Average total assets / average PepsiCo shareholders' equity |

Return on equity is the product of the five factors. The first factor uses attributable net income, so it measures what reaches PepsiCo shareholders after tax and noncontrolling interests, not tax alone. The interest burden also absorbs other pension and retiree medical benefits income or expense, so its movements are read alongside that line.

### Section 2: Earnings quality

**Question:** Are reported earnings recurring, and are they backed by cash?

**Normalisation.** Only material one-off items identified in the filings are normalised:

| Year | Item | Line affected |
| --- | --- | --- |
| 2017 | Provisional net tax expense under the Tax Cuts and Jobs Act | Income tax |
| 2018 | Other net tax benefits from the reorganisation of international operations and tax audit conclusions | Income tax |
| 2021 | Charge related to cash tender offers on long-term debt | Net interest expense |
| 2022 | Gain associated with the Juice Transaction | Operating profit |
| 2022 | Russia-Ukraine conflict charges | Operating profit |
| 2025 | Rockstar brand impairment | Operating profit |

Gains are removed and charges are added back. A segment is adjusted only where the filing assigns the item to that segment; other items stay at the consolidated level. Each item records the reported figure, the affected segment, the amount and its source, the direction of the adjustment, the normalised figure and the reason it is treated as nonrecurring.

Normalised net income uses an after-tax bridge: net income attributable to PepsiCo, minus the after-tax effect of gains, plus the after-tax effect of charges. Only after-tax amounts disclosed in the filings are used. An item without a disclosed after-tax amount enters the operating view only.

**Recurring charges.** Restructuring and impairment charges are reported every year, and impairment and other charges every year from 2022. They are not normalised. Their pattern is assessed as an earnings-quality signal in its own right.

**Cash and accruals.**

- Cash from operations against consolidated net income, each year. Consolidated net income is used because cash from operations starts from it.
- Accruals ratios from 2018, where NOA is net operating assets:
  - Balance-sheet accruals ratio = (NOA this year − NOA last year) / average NOA
  - Cash-flow accruals ratio = [consolidated net income − (cash from operations + cash from investing)] / average NOA
  - NOA = (total assets − cash and short-term investments) − (total liabilities − total debt)
  - Both ratios follow the definitions in the CFA Level II reading *Integration of Financial Statement Analysis Techniques*. Net operating assets grow with capital investment as well as with working capital, so the cash-flow version deducts cash from investing as well as cash from operations; the two ratios then measure the same accruals, one from the balance sheet and one from the cash flow statement. The plain gap between earnings and operating cash flow is covered by the comparison of cash from operations with net income above.
- Persistence: whether normalised earnings move steadily or revert, read alongside the accruals results.
- Supplier finance, from 2023 when it is first disclosed: the confirmed obligation balance and its change, accounts payable, days payable outstanding and cash from operations, shown together. Any relationship between them is described as a signal, not a cause.

### Section 3: Financial position

**Question:** Can the balance sheet support current earnings and obligations?

| Measure | Formula |
| --- | --- |
| Current ratio | Current assets / current liabilities |
| Cash ratio | (Cash + short-term investments) / current liabilities |
| Debt to reported EBITDA | Total debt / (operating profit + depreciation and amortisation) |
| Interest coverage | Operating profit / gross interest expense |
| Cash from operations to debt | Cash from operations / total debt |

Reported EBITDA is a proxy: operating profit includes restructuring and impairment charges, so years with large charges understate EBITDA and overstate debt to EBITDA, and those years are read alongside the recurring-charges record. All five measures run from 2018. Interest coverage for 2021 is shown both as reported and without the tender-offer charge. Liquidity is read against PepsiCo's operating model: a current ratio below 1 may be consistent with that model and is not automatically a warning sign.

### Section 4: Conclusion

- Which description of the years after 2019 the evidence supports.
- What supports the business.
- What raises concern.
- What the data cannot show, and what additional data would be needed.
- What deserves further diligence.

## 6. Conventions

- Findings are described as signals that warrant further diligence or areas that merit closer examination. No finding is presented as an accusation of wrongdoing.
- Every quoted number names its source: the filing, the note or the calculation.
- Where the filings cannot answer a question, the analysis says so and states what would be needed.
- Figures are in US dollars, millions, unless stated otherwise. Fiscal years end on the last Saturday of December.
