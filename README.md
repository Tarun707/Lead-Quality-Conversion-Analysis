# Lead Quality & Conversion Analysis

## 📌 Problem Statement

This project analyzes a subset of lead generation data for a single publisher and advertiser. The goal is to understand lead quality trends, identify key drivers of performance, and evaluate opportunities to improve conversion rates.

---

## ❓ Key Questions

1. Are we seeing any lead quality trends over time? Are they statistically significant?  
2. What are the key drivers of lead quality across channels, customer segments, and campaigns?  
3. Can we improve lead quality by 20% (from 8% to 9.6%) and unlock higher CPL?

---

## 📊 Dataset Overview

- ~3,000 lead records  
- Includes information on:
  - Traffic source (Search, Display, Call Center)
  - Partner and campaign details
  - Customer attributes (Debt Level, State)
  - Quality indicators (Good leads, Closed leads)

---

## 🔍 Approach

- Cleaned and preprocessed data (handled missing values, standardized fields)
- Created key features:
  - LeadQuality (Good vs Bad)
  - ClosedFlag (conversion)
  - TrafficType (Search / Display / Call Center)
- Performed:
  - Weekly time-series analysis
  - Statistical testing using linear regression (p-values)
  - Multi-dimensional segmentation (channel, partner, campaign, debt level)

---

## 📈 Key Insights

### Q1: Trends Over Time

- Closed rate is declining over time and the trend is statistically significant  
- Good rate remains relatively stable with no significant trend  
- Lead volume is declining and statistically significant  

👉 Overall: Conversion performance is worsening despite stable lead quality

---

### Q2: Drivers of Lead Quality

- Traffic source is a major driver:
  - Search and Call Center outperform Display
  - Google Display generates high volume but low quality  

- Debt level is a strong factor:
  - Mid-range segments (10–15k, 70–90k) perform best  
  - Very low and very high debt segments underperform  

- Campaign structure matters:
  - Targeted campaigns outperform large generic campaigns  

👉 Overall: Lead quality is driven by channel mix, customer profile, and campaign strategy

---

## 🚀 Q3: Improving Conversion (8% → 9.6%)

### Is It Achievable?

Yes — several segments already exceed the target:
- Google Search (~11%)
- Debt Holding Tank (~14–15%)
- Financial Services (~12%)
- 70–90k debt segment (~13%)

---

### Opportunities

#### 1. Reduce Low-Performing Display Traffic
- Google Display has ~5% closed rate but drives large volume  
- Shifting traffic to higher-performing Search can improve overall conversion  

#### 2. Target Better Debt Segments
- Mid-range debt performs significantly better (~13–14%)  
- Low debt segments (~5%) drag down performance  

#### 3. Scale High-Performing Campaigns
- Strong campaigns (Debt Holding Tank, Financial Services) outperform generic ones  
- Reallocating budget can improve efficiency  

---

### Overall Assessment

- Only ~1.6 percentage point improvement is needed  
- At ~3,000 leads:
  - Current: ~240 conversions  
  - Target: ~288 conversions  
  - Gap: ~48 additional conversions  

👉 This can be achieved through traffic mix optimization without major structural changes

---

## 🛠️ Tools Used

- Python (Pandas, NumPy)
- Matplotlib
- Statistical Analysis (Linear Regression)

---

## 📌 Key Takeaway

Performance issues are not due to overall lead quality, but due to **traffic mix inefficiencies**. Optimizing channel allocation, targeting, and campaign strategy can realistically improve conversion rates and unlock higher revenue.
