# Xena (Huijia) Xu

Mathematics major (minors in Statistics and Economics) at the University of Toronto Scarborough, class of 2028.
Business Systems Analyst in CIBC Capital Markets' Alternate Solutions Group Technology, working on FX and cross-border payments products. Investment intern at Blue Lion Capital, a financial advisory firm for early-stage AI companies. Based in Toronto.

## What I work on
- **Payments technology at CIBC (2026 –)**: business, functional and solution requirements for FX and cross-border payment platforms (300+ Jira stories across 7+ projects), user acceptance testing and release sign-off, Visio money-movement workflows, Power BI reporting. I also built my team's automation with GitHub Copilot and LLM agents: requirements drafting, Jira ticket creation, a release analyzer, meeting follow-ups and a weekly status dashboard.
- **Deal tooling at Blue Lion Capital (2026 –)**: built and run the firm's internal deal-management system (TypeScript/React, Python FastAPI, PostgreSQL with pgvector, LLM APIs). It archives meetings and files and writes to the investor CRM only after a person confirms the change. Code is private; happy to talk through the design.
- **Markets research**: sector investment theses and investment-committee assessments with valuation checks against comparable revenue multiples.

## Public projects
| Project | What it is | Stack |
|---|---|---|
| [efx-market-making-sim](https://github.com/xenaxu7/efx-market-making-sim) | Single-dealer eFX market-making simulator on real USDCAD minute data: inventory skew vs hedging, P&L split into spread capture, inventory MTM and hedge cost, a 96-point parameter grid and a "long 20mm, get flat" scenario. Client flow is synthetic and the README says exactly what the model ignores | Python, NumPy, pandas, Matplotlib, pytest |
| [fixed-income-toolkit](https://github.com/xenaxu7/fixed-income-toolkit) | Excel workbook with live formulas on Bank of Canada data: GoC bond price, yield and accrued (act/365), duration, convexity, DV01 hedge ratio, par-to-zero bootstrap compared with the Bank's zero curve, USDCAD forward points from CORRA vs SOFR. VBA Newton yield solver and bootstrap, plus a Python mirror tested against the recalculated sheet to 1e-8 | Excel, VBA, Python, openpyxl, LibreOffice |
| [remittance-cost-analysis](https://github.com/xenaxu7/remittance-cost-analysis) | World Bank Remittance Prices Worldwide data (2011-2025) for 15 Canada corridors loaded into SQLite: fee vs FX margin over time by provider type, bank vs MTO vs fintech gap by corridor, cross-check of RPW's reference rate against the Bank of Canada, Plotly dashboard | SQL (SQLite), pandas, Matplotlib, Plotly |
| [SP500-lstm-portfolio](https://github.com/xenaxu7/SP500-lstm-portfolio) | Walk-forward LSTM stock selection on 479 S&P 500 names: monthly re-ranking with six-monthly retraining, 5/20 bps costs, equal-weight, momentum and SPY benchmarks, information coefficient and a 500-draw random-basket test. The write-up explains why the headline return is a volatility tilt rather than skill | Python, TensorFlow/Keras, pandas, yfinance |
| [MIPS-Tetris-Game](https://github.com/xenaxu7/MIPS-Tetris-Game) | Complete Tetris in MIPS assembly for CSCB58 (rotation with wall kicks, gravity, line clears, collision) | MIPS, MARS |

## Tools
Python (pandas, NumPy, TensorFlow, Matplotlib, Plotly, pytest) · SQL (PostgreSQL, SQLite) · TypeScript/JavaScript (React, Node) · C · R · Git
Excel (Power Query, pivot tables, XLOOKUP, dynamic arrays) · Power BI · Visio · Jira · Confluence · SharePoint
LLM APIs (OpenAI, Anthropic, Gemini), prompt engineering, AI agents

## Outside work
Tournament director of the 49th Canadian Go Open (2026): 130+ players from several countries, 230+ attendees, five corporate sponsors. I have played Go competitively since I was three and coach 140+ students.

[LinkedIn](https://www.linkedin.com/in/xena-xu/) · Huijia.xu@mail.utoronto.ca
