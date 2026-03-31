# Lead Quality & Conversion Analysis

## Overview

This project looks at a dataset of around 3,000 leads from a single publisher and advertiser. The goal was to understand how lead quality is changing over time, what factors affect it, and whether we can improve conversion rates.

---

## Key Questions

1. Are lead quality and conversion rates improving or declining over time?
2. What factors (channel, campaign, customer profile) affect lead quality?
3. Can we improve conversion from 8% to 9.6%?

---

## What I Did

- Cleaned the dataset and handled missing values  
- Created useful columns like lead quality, closed flag, and traffic type  
- Analyzed weekly trends using simple regression  
- Broke down performance by channel, partner, campaign, and debt level  

---

## Key Findings

### Trends Over Time

- Conversion rate is going down over time (and it’s statistically significant)  
- Lead quality is mostly stable  
- Overall traffic volume is also declining  

So even though the quality of leads hasn’t changed much, fewer of them are converting.

---

### What Drives Lead Quality

- Search and Call Center traffic perform better than Display  
- Google Display brings the most volume but has the worst performance  
- Mid-range debt segments (10–15k, 70–90k) convert better  
- Some campaigns perform much better than others  

Overall, channel mix, customer profile, and campaign setup make a big difference.

---

## Can We Improve Conversion?

Target: 8% → 9.6%

This looks achievable because some segments already perform above this level.

### Opportunities

- Reduce low-performing Display traffic and shift towards Search  
- Focus more on mid-range debt segments  
- Scale better-performing campaigns instead of generic ones  

At current volume (~3,000 leads), we need ~48 more conversions to hit the target. Given the performance gap across segments, this seems realistic through better traffic mix.

---

## Tools Used

- Python (Pandas, NumPy)
- Matplotlib
- Basic statistical testing (linear regression)
