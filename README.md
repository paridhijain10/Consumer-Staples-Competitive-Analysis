# Consumer Staples Competitive & Financial Analysis

## Overview

A Python-based financial analysis engine that compares five major consumer staples companies across financial performance, profitability, capital efficiency, leverage, and relative valuation.

The project combines Python-based financial data analysis with an Excel analyst dashboard to identify relative strengths, weaknesses, valuation differences, and competitive positioning.

## Companies Analyzed

- Procter & Gamble (PG)
- Coca-Cola (KO)
- PepsiCo (PEP)
- Colgate-Palmolive (CL)
- Mondelez (MDLZ)

## Analysis

The project evaluates:

- Revenue and free cash flow growth
- EBIT and FCF margins
- ROIC and asset turnover
- Interest coverage and leverage
- P/E, EV/EBITDA and P/S multiples
- FCF yield
- Peer financial-quality ranking
- Growth vs. valuation
- ROIC vs. valuation
- Competitive positioning

## Financial Quality Ranking

Companies are ranked using an equal-weighted score across seven metrics:

1. Revenue Growth
2. EBIT Margin
3. ROIC
4. FCF Margin
5. Asset Turnover
6. Interest Coverage
7. Debt/EBITDA

ROE is excluded from the composite ranking because unusually low book equity can create economically misleading results for certain companies.

## Key Findings

- Colgate-Palmolive ranks highest on overall financial quality, supported by strong ROIC, margins, and capital efficiency.
- Procter & Gamble combines strong profitability with relatively low leverage and high interest coverage.
- Coca-Cola generates the strongest EBIT margin but trades at a premium valuation.
- PepsiCo offers the lowest EV/EBITDA multiple among the peer group but carries higher leverage.
- Mondelez has the strongest revenue growth but comparatively lower ROIC and profitability.

## Data & Methodology

Financial analysis is based on FY2025 company financial data.

Market and valuation data are based on market information available as of **September 4, 2026**.

Data source: Yahoo Finance.

ROIC is calculated as EBIT divided by year-end invested capital (equity + debt − cash) and is used as a simplified capital-efficiency measure.

## Tools

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- yfinance
- Microsoft Excel / Google Sheets

## Files

- `Competitive_Financial_Analysis.ipynb` — Python analysis engine
- `Consumer_Staples_Competitive_Analysis.xlsx` — Financial analysis and dashboard

## Disclaimer

This project is for educational and analytical purposes only and does not constitute investment advice.
