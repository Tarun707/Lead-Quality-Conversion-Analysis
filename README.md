# Lead Quality & Conversion Analysis

## Overview

This project looks at ~3,000 leads from a single publisher and advertiser to understand how lead quality and conversion are behaving, and where improvements can be made.

---

## Key Questions

1. Are lead quality and conversion rates changing over time?
2. What factors drive lead quality?
3. Can we improve conversion from 8% to 9.6%?

---

## What I Did

- Cleaned the dataset and handled missing values  
- Created features like lead quality, closed flag, and traffic type  
- Analyzed weekly trends and checked significance using regression  
- Segmented performance by channel, partner, campaign, and debt level  

---

## Key Findings

### 1. Trends Over Time

- Closed rate is declining over time (p ≈ 0.008)  
- Good rate is mostly flat (p ≈ 0.50, not significant)  
- Lead volume is also declining (p ≈ 0.018)  

So conversion is getting worse over time, even though lead quality itself hasn’t really changed.

---

### 2. Drivers of Lead Quality

- **Channel matters a lot:**
  - Search: ~9.5–11% closed rate  
  - Call Center: ~9.5%  
  - Display: ~6–7%  
  - Google Display specifically: ~5%  

- **Debt level is a strong driver:**
  - 70–90k: ~13.7% closed rate  
  - 10–15k: ~11.7%  
  - 7.5–10k: ~5%  
  - More than 100k: ~3.6%  

- **Campaign differences are large:**
  - Debt Holding Tank: ~14.5%  
  - Financial Services: ~12%  
  - DebtReductionInc (largest volume): ~6%  

Overall, performance varies a lot depending on traffic source, customer profile, and campaign.

---

## 3. Can We Improve Conversion (8% → 9.6%)?

### Is it achievable?

Yes — several segments are already above 9.6%:
- Google Search (~11%)  
- Debt Holding Tank (~14–15%)  
- Financial Services (~12%)  
- 70–90k debt (~13%)  

---

### Where are the opportunities?

- **Reduce Google Display traffic**  
  High volume but low performance (~5% closed rate), which pulls down overall average  

- **Focus on better debt segments**  
  Mid-range debt performs much better (~13–14%) compared to low debt (~5%)  

- **Shift budget to stronger campaigns**  
  Some campaigns perform 2x better than others  

---

### What does improvement look like?

At ~3,000 leads:
- Current: ~8% → ~240 conversions  
- Target: ~9.6% → ~288 conversions  
- Gap: ~48 additional conversions  

Given the gap between low- and high-performing segments (5% vs 11–14%), this looks achievable through better traffic mix rather than major changes.

---

## Tools Used

- Python (Pandas, NumPy)
- Matplotlib
- Linear regression (for trend analysis)
