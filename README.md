# UK Labour Market Analysis

A regional analysis of salary, rent affordability, gender pay gap, house prices, and job vacancies across 9 England regions using ONS data.

**Live dashboard:** [Power BI Dashboard](https://liveastonac-my.sharepoint.com/:u:/r/personal/250406630_aston_ac_u/Documents/uk_cost%20and%20labour%20analysis.pbix?csf=1&web=1&e=cbU6eB)

> ⚠️ Note: The link above requires an Aston University login. See screenshots below for a preview without needing access.
> 

## Salary & Affordability

- **Yorkshire and The Humber** has the best take-home pay after rent at **£20,920/yr** — £6,111 more than London.
- **London** pays the highest median salary (£38,293), but rent consumes **61.3%** of it, leaving only £14,809/yr.
- **North East** has the lowest rent burden at **26.9%** — the only region comfortably under the 30% safe threshold.
-
   <img width="594" height="335" alt="image" src="https://github.com/user-attachments/assets/bbfc4ce7-bf84-4b4d-97a3-0ebb606363b0" />


## Gender Pay Gap

- The national average gender pay gap is **28.5%** across all 9 English regions.
- **South East** has the largest gap at **31.5%** — women there earn roughly £12,892 less than men per year after rent.
- South East women spend **53.6%** of their salary on rent vs **36.0%** for men in the same region.
- **London** has the smallest gap at **21.5%** — still significant, but the lowest of all regions.

<img width="602" height="338" alt="image" src="https://github.com/user-attachments/assets/c09cd62a-26f5-4936-91dd-0477f1956561" />

## Rent Trends (2015–2024)

- Every region saw rent rise faster than wages over the 9-year period.
- **South West** had the highest rent growth at **35.4%** from 2015/16 to 2023/24.
- **London** had the lowest % growth at 19.1%, but started from the highest base (£1,643 → £1,957/month).

 <img width="596" height="332" alt="image" src="https://github.com/user-attachments/assets/2d457acf-11b1-44e1-b34f-2f235cac9d04" />


## Housing Market

- London's average house price in Feb 2024 was **£502,690** — 3.1× more expensive than the North East (£160,406).
- London house prices peaked at £542,387 in Aug 2022 before falling as interest rates rose.
- All regions showed a price decline in late 2022 and 2023 — the first UK-wide correction in over a decade.

## Job Market

- Total UK vacancies for the main sectors in Aug–Oct 2024 were **105,000** — down 36.3% from the post-COVID peak of 805,000 in 2022.
- **Health and Social Work** remains the largest sector at 29,000 vacancies despite the overall decline.
- Vacancies are still 22% above pre-pandemic levels, suggesting structural labour shortages continue.

---
<img width="598" height="335" alt="image" src="https://github.com/user-attachments/assets/58f77279-13f5-4147-98f6-76bb6b4a0840" />

## Tools & Data

Tools:
- Python — Pandas, Matplotlib, Seaborn, Scikit-learn
- Power BI — 5-page interactive dashboard

Data sources:
- ONS ASHE 2024
- ONS Private Rental Affordability
- UK House Price Index
- ONS VACS02 (Nov 2024)

## How to Run

```bash
git clone https://github.com/sanjaikanna1111/uk-labour-market-analysis/tree/main/uk_labour%20cost%20analysis.git
cd uk_market analysis
pip install -r requirements.txt
```

Then open the Jupyter notebooks in `/notebooks` or run the analysis scripts in `/src`.

## Repo Structure

```
uk-labour-market-analysis/
├── dashboard/ # Power BI .pbix file
        └──gender analysis dashboard
        └── housing market analysis
        └── uk labour market analysis overview
        └───uk rent trends
        └── analysis using python       
├── data/
      └── data processed/  #cleaned with added feautures           
      └── data raw/      # raw and cleaned ONS datasets                

├──notebook
       └── EDA of the data
```
