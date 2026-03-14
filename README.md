# Investment Banking Research: M&A Valuation & Deal Analysis

> **Global M&A Industry Analysis (2025–2026) and a full Investment Banking case study on the Dell / EMC $67 billion acquisition (2016)**

---

## 📌 Project Overview

This project was built as part of an independent investment banking research initiative during an MBA with a specialisation in Finance and Analytics. It covers two interconnected deliverables:

1. **Global M&A Industry Analysis (2025–2026)** — a market-wide research model analysing $3.8 trillion in deal activity across sectors, deal structures, and valuation frameworks
2. **Dell / EMC $67bn Acquisition Case Study (2016)** — a reverse-engineered deal analysis covering SOTP valuation, LBO financing structure, precedent transaction benchmarking, and post-merger performance tracking

---

## 🗂️ Repository Structure

```
ma-valuation-deal-analysis/
│
├── dell_emc_analysis.py           # Dell/EMC case study — Python analysis & visualisation
├── ma_analysis.py                 # Global M&A industry analysis — Python script
│
├── Dell_EMC_Financial_Model.xlsx  # 4-sheet Excel model: Deal Overview, Financials,
│                                  # Valuation Analysis, Post-Merger Performance
├── MA_Financial_Model_2026.xlsx   # 4-sheet Excel model: Dashboard, DCF Model,
│                                  # Comparable Companies, Deal Screening
│
├── dell_emc_case_study_charts.png # 9-panel visual output — Dell/EMC case study
├── ma_analysis_charts.png         # 9-panel visual output — Industry analysis
│
└── README.md
```

---

## 🔍 Part 1: Global M&A Industry Analysis (2025–2026)

### What it covers
- Global deal value trend analysis (2018–2026E): $2.9T → $3.8T → $4.3–4.8T projected
- Sector-by-sector breakdown: Technology & AI, Banking, Healthcare, Energy, Wealth Management
- Participation trends: PE contribution (16% → 21%), tech share (22% → 31%), cross-border activity
- DCF sensitivity analysis across WACC (8–12%) and terminal growth rate (2–4%) scenarios
- Comparable companies analysis: 8-company SaaS/software comps with EV/Revenue and EV/EBITDA multiples
- Deal screening framework: composite scoring model (Strategic Fit × 40%, Financial Strength × 35%, Integration Risk × 25%)

### Key findings
| Metric | 2024 | 2025 | 2026E |
|--------|------|------|-------|
| Global Deal Value | $3.1T | $3.8T | $4.3–4.8T |
| Megadeals (>$5bn) | 68 | 89 | 100+ |
| Technology Sector Share | 28% | 31% | 33%+ |
| PE Contribution | 18% | 21% | 25%+ |

### Tools & methods
- **Python**: `pandas`, `numpy`, `matplotlib` — trend analysis, DCF sensitivity heatmap, scatter plots, composite scoring
- **Excel**: DCF model (5-year FCF projection, Gordon Growth + EV/EBITDA terminal value), comparable companies with statistical summary, deal screening tracker

---

## 🏦 Part 2: Dell / EMC $67bn Acquisition — Case Study

### Deal snapshot
| Parameter | Detail |
|-----------|--------|
| Acquirer | Dell Inc. (Denali Holding Inc.) |
| Target | EMC Corporation (NYSE: EMC) |
| Deal Value | **$67 billion** |
| Announcement | October 12, 2015 |
| Close | September 7, 2016 |
| Structure | Cash ($24.05/share) + VMware Tracking Stock (0.11146 DVMT/share) |
| Acquisition Premium | ~28% |
| Advisors (Dell) | J.P. Morgan, Evercore |
| Advisors (EMC) | Goldman Sachs, Lazard |

### Valuation analysis performed

**Transaction multiples**
| Multiple | Value | Benchmark |
|----------|-------|-----------|
| EV / LTM Revenue | 2.7x | 1.5x–4.0x (enterprise IT) |
| EV / LTM EBITDA | 12.2x | 8x–14x (enterprise IT) |
| Acquisition Premium | 28% | 20–40% (large-cap M&A) |

**Sum-of-the-Parts (SOTP) — justifying $67bn**
| Component | Value ($bn) |
|-----------|------------|
| VMware — 80% stake | $40.0 |
| EMC Information Infrastructure | $18.5 |
| RSA Security | $2.5 |
| Pivotal | $1.5 |
| Virtustream | $1.2 |
| Net Debt Adjustment | ($0.2) |
| **SOTP Total** | **$63.5** |
| Actual Deal Price | $67.0 |
| Strategic Premium | ~$3.5 |

> **Key insight:** At $67bn, Dell was effectively acquiring EMC's storage and security businesses at ~1.4x revenue — below standalone fair value — with VMware's $40bn stake anchoring most of the deal price.

**Financing structure**
| Source | Amount |
|--------|--------|
| New Senior Debt (Term Loans & Notes) | $45.9bn |
| EMC Cash Reserves | $9.0bn |
| VMware Tracking Stock (non-cash) | $9.0bn |
| Dell / Silver Lake Equity | $4.4bn |
| Other | $1.3bn |
| **Total** | **$67.0bn** |

### Post-merger performance
| Fiscal Year | Revenue | Total Debt |
|-------------|---------|------------|
| FY2016 (partial) | $62.0bn | $52.0bn |
| FY2017 | $79.0bn | $46.0bn |
| FY2019 | $91.0bn | $40.0bn |
| FY2022 (post-VMware spin) | $101.2bn | $22.0bn |

> Dell paid down **$30bn in debt** over 6 years. The 2021 VMware spin-off — which included a $12bn special dividend — was the single largest deleveraging event.

### Integration scorecard
| Dimension | Score | Verdict |
|-----------|-------|---------|
| Strategic Transformation | 5/5 | ✅ Achieved |
| Cost Synergies | 5/5 | ✅ Exceeded target |
| VMware Value Capture | 5/5 | ✅ Excellent |
| Revenue Synergies | 4/5 | ✅ Achieved |
| Debt Management | 4/5 | ✅ Achieved |
| Cultural Integration | 4/5 | ✅ Achieved |
| Enterprise Storage Market | 3/5 | ⚠️ Mixed |
| Cloud Transition | 3/5 | ⚠️ Partial |
| **Overall** | **4.1/5** | **✅ Successful** |

---

## 📊 Visual Outputs

### Industry Analysis — 9-Panel Chart
![M&A Industry Analysis Charts](ma_analysis_charts.png)

### Dell / EMC Case Study — 9-Panel Chart
![Dell EMC Case Study Charts](dell_emc_case_study_charts.png)

---

## 🛠️ How to Run

**Requirements**
```bash
pip install pandas numpy matplotlib openpyxl
```

**Run industry analysis**
```bash
python ma_analysis.py
```

**Run Dell/EMC case study**
```bash
python dell_emc_analysis.py
```

Both scripts print a full analytical summary to the terminal and save chart outputs as `.png` files.

---

## 📚 Data Sources

- Morgan Stanley: *Global M&A Activity Outlook 2026* (January 2026)
- PwC: *Global M&A Industry Trends: 2026 Outlook* (January 2026)
- McKinsey & Company: *Financial Services M&A Bounces Back* (February 2026)
- Goldman Sachs: *2026 Global M&A Outlook*
- J.P. Morgan: *Global Dealmaking Trends & 2025 IB Recap*
- EMC Corporation 10-K Annual Report (FY2015) — SEC EDGAR
- Dell Technologies Press Release: *Dell and EMC Merger Complete* (September 7, 2016)
- Barclays Investment Bank: *The Profile of M&A in 2026*
- DealRoom: *M&A Statistics by Sector* (February 2026)

---

## 👤 Author

**Harshit Kumar**
MBA Candidate | Finance & Analytics Specialisation
https://www.linkedin.com/in/harshit-kumar-3280a31ba | vatsharsh1004@gmail.com
