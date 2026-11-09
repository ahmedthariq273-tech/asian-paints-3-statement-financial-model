# Asian Paints Ltd. --- Integrated 3-Statement Financial Model

An Excel 2016 financial modelling portfolio project covering historical
financial analysis, a five-year forecast, integrated financial
statements, scenario analysis, sensitivity analysis, and Monte Carlo
simulation for **Asian Paints Limited (consolidated)**.

> **Purpose:** Educational and portfolio demonstration only. This
> project is not investment advice, a recommendation to trade, or an
> independent valuation opinion. Forecasts are assumption-driven and are
> not guarantees of future performance.

## Project at a glance

  Item                     Details
  ------------------------ --------------------------------------------------------
  Company                  Asian Paints Limited
  Reporting basis          Consolidated
  Historical period        FY2022A--FY2026A
  Forecast period          FY2027E--FY2031E
  Fiscal year-end          31 March
  Model currency / units   Indian rupees (₹), crore
  Spreadsheet platform     Microsoft Excel 2016
  Forecast horizon         5 years
  Simulation               5,000 Monte Carlo iterations across 8 selected drivers
  Prepared by              Ahmed Thariq M
  Academic context         MBA (PGPM) Finance, ISSM Business School

## Project objective

The objective was to build an integrated, driver-based financial model
that connects an understanding of the company's business with its
historical financial performance and forward-looking financial
statements.

The workbook is designed to demonstrate how operating assumptions flow
through the income statement, balance sheet and cash flow statement, and
how scenario, sensitivity and probabilistic analysis can support
financial planning and decision-making.

## Business understanding and key drivers

The model's business analysis considers the company's decorative and
home décor activities, international operations and industrial business.

The operating narrative considers factors such as:

-   Product and business mix.
-   Demand conditions, including housing and repainting activity.
-   Sales volume, pricing and realisation.
-   Raw-material and other operating costs.
-   Inventory, receivables and payables.
-   Capital expenditure and operating capacity.
-   Regional demand, competition and currency movements for
    international operations.

These are analytical drivers and considerations; they should not be
interpreted as a claim that every factor is separately modelled as an
independent forecast input.

## Workbook architecture

The workbook contains the following worksheets:

1.  **Cover Page** --- project overview, navigation, model status and
    key forecast outputs.
2.  **Business Model** --- business categories, revenue mix and
    operating overview.
3.  **Historical_Data** --- historical financial information.
4.  **Historical_Ratios** --- historical financial ratio analysis.
5.  **Forecast_Ratios** --- forecast ratio analysis.
6.  **Assumptions** --- key forecast assumptions.
7.  **Revenue_Model** --- revenue build-up.
8.  **Income_Statement** --- historical and forecast income statement.
9.  **Balance_Sheet** --- historical and forecast balance sheet.
10. **Cash_Flow** --- cash flow statement and cash flow analysis.
11. **Debt_Schedule** --- debt balances, repayments and interest
    calculations.
12. **Supporting_Schedules** --- supporting calculations for the
    integrated model.
13. **Scenario & Sensitivity** --- scenario selection and two-variable
    sensitivity analysis.
14. **Monte_Carlo** --- probabilistic simulation.
15. **Dashboard** --- financial performance dashboard.
16. **Monte_Carlo Snapshot** --- simulation results snapshot.
17. **Dashboard_Data** --- supporting data used by dashboard visuals.

## Modelling methodology

### 1. Historical analysis

Historical financial information is organised for FY2022A--FY2026A and
used as the basis for trend and ratio analysis.

### 2. Driver-based forecasting

Forecast assumptions feed the revenue model and supporting schedules.
The forecast period is FY2027E--FY2031E.

### 3. Integrated financial statements

The income statement, balance sheet and cash flow statement are linked
through supporting schedules, working-capital assumptions, investment
and financing calculations.

### 4. Scenario analysis

The workbook includes Optimistic, Base and Pessimistic scenario choices.
The dashboard snapshot documented in this repository presentation
reflects the **Pessimistic** scenario selected at the time of review.
Changing the scenario selector was tested and the dashboard outputs
changed.

### 5. Sensitivity analysis

Two-variable Excel Data Tables are used to examine the effect of changes
in selected assumptions on FY2031E EBITDA and free cash flow.

### 6. Monte Carlo simulation

The workbook includes 5,000 iterations using eight selected drivers:

  Driver                     Modelled range
  ------------------------ ----------------
  Product revenue growth            5%--11%
  Service revenue growth            7%--12%
  Other revenue growth               2%--7%
  EBITDA margin                    17%--20%
  Inventory days                   108--125
  Receivable days                    42--55
  Payable days                       65--75
  CapEx / Revenue                    4%--5%

The simulation analyses FY2031E Revenue, EBITDA, PAT and free cash flow,
working-capital outcomes, percentile statistics (P10, P50 and P90),
mean, standard deviation and FCF probability analysis. Press **F9** in
Excel to recalculate the simulation.

## Selected FY2031E dashboard snapshot

The following figures are the workbook dashboard values observed with
the **Pessimistic** scenario selected. Amounts are ₹ crore except ratios
and EPS.

  Metric                              FY2031E
  ------------------------ ------------------
  Revenue                    ₹45,415.69 crore
  EBITDA                      ₹7,720.67 crore
  EBITDA margin                         17.0%
  Profit after tax (PAT)      ₹5,071.58 crore
  Free cash flow (FCF)         -₹853.30 crore
  ROCE                                 17.19%
  EPS                                  ₹52.04

### Interpretation

The selected scenario shows positive forecast earnings alongside
negative FY2031E free cash flow. This makes cash conversion,
working-capital management and capital expenditure important areas for
further analysis.

These are model outputs under the selected assumptions, not predictions
or guarantees.

## Model checks and testing

The following checks were reported during workbook review:

-   The Cover Page master reconciliation displayed **MODEL OK**.
-   Balance sheet and cash flow reconciliations were reported as
    completed.
-   No circular references were reported during the model-building
    process.
-   The checked Monte Carlo output cells displayed numerical values in
    the user's Excel 2016 installation.
-   The user recalculated the Monte Carlo simulation using **F9**
    without observing calculation errors.
-   Scenario responsiveness was tested: changing the scenario selector
    changed dashboard outputs.

These are project testing observations, not an independent audit or
verification of every formula and source input.

## Important modelling treatments and limitations

-   Historical exceptional items are retained in reported PAT; forecast
    exceptional items are assumed to be zero.
-   EBITDA is presented before exceptional items.
-   Lease finance costs are calculated on opening lease liabilities
    using the rate in the Assumptions worksheet.
-   Dividend payout assumptions use 55%, with the cash flow and equity
    schedule applying their specified respective PAT bases.
-   The FY2026 final dividend is not separately modelled as a lagged
    payment.
-   No normalised PAT calculation is included.
-   Dividend timing and certain exceptional-item effects are simplified.
-   Forecasts depend on assumptions and model design choices. Actual
    outcomes may differ materially.

## Files in this repository

Suggested repository contents:

``` text
asian-paints-integrated-financial-model/
├── README.md
├── Asian_Paints_3_Statement_Financial_Model.xlsx
└── Asian_Paints_Integrated_Financial_Model_Pitch_Deck.pptx
```

Add the final, saved Excel workbook and the PowerPoint pitch deck to the
repository using the filenames above, or update the filenames in this
section to match the files you upload.

## Sources

The historical source set used for the project consists of Asian Paints
Limited annual / integrated reports:

-   Integrated Report 2021--22
-   Integrated Annual Report 2022--23
-   Integrated Annual Report 2023--24
-   Integrated Annual Report 2024--25
-   Integrated Annual Report 2025--26

The model's source scope was described as consolidated financial
statements from these reports. Earnings calls and investor presentations
were not used as sources for this project.

For public review, readers should consult the company's official
investor-relations website and the relevant annual reports to verify
reported historical figures.

## How to use the workbook

1.  Open the `.xlsx` file in desktop Microsoft Excel 2016 or a
    compatible later version.
2.  Start with the **Cover Page** for navigation, scope, status and key
    outputs.
3.  Review the **Business Model**, **Historical_Data** and ratio
    worksheets to understand the business and historical base.
4.  Review the **Assumptions** and **Revenue_Model** worksheets before
    interpreting forecast results.
5.  Use the scenario selector in `Scenario & Sensitivity!B4` to switch
    between Optimistic, Base and Pessimistic scenarios.
6.  Review the sensitivity tables for FY2031E EBITDA and free cash flow.
7.  Press **F9** to recalculate the Monte Carlo simulation.
8.  Review the Dashboard and Monte Carlo Snapshot for summary outputs.

Keep Excel calculation mode set to **Automatic** for recalculation of
formulas and sensitivity tables.

## Author

**Ahmed Thariq M**\
MBA (PGPM) Finance\
ISSM Business School, India\
LinkedIn: https://www.linkedin.com/in/ahmed-thariq16

## Disclaimer

This repository is an educational and portfolio project. It is not
investment advice, a solicitation, an offer, or a recommendation to buy
or sell any security. The model is based on historical reported
information and assumptions selected for learning and demonstration. No
representation is made that forecasts will be achieved or that the model
is free from errors. Users should independently verify data, assumptions
and calculations before relying on any output.
