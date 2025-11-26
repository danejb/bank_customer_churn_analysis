# Project Summary: Bank Customer Churn Analysis

## Executive Summary

***Problem:*** Bank losing customers at unsustainable rate (20.38% annually)
***Analysis:*** Examined 10,000 customer records to indentify when and why churn occurs
***Key Discovery:*** Year 0-1 customers face 23% churn-highest risk period (onboarding problem)
***Recommendation:*** Prioritize Year 0-1 improvements (highest ROI) while studying Years 4-7 success factors
***Impact:*** Reducing churn by 5% could save $119,000+ annually

---

## Methodology

### Data Source
- ***Dataset:*** 10,000 Bank Customer records from Kaggle
- ***Fields:*** Age, Tenure, Geography, Gender, Products, Balance, Churn Status, etc.
- ***Period:*** Historical snapshot (tenure ranges 0-10 years)

### Analysis Approach

**Step 1: Calculate Overall Churn**
- Result: 20.38% of customers have churned
- Benchmark: Industry average is 15-25% (we're middle of pack)

**Step 2: Analyze by Lifecycle (Tenure)**
- Grouped customers by years with bank
- Calculated churn % for each year
- Found: Year 0-1 is crisis (23%), Years 4-7 are stable (17%)

**Step 3: Analyze by Demographics (Age)**
- Grouped customers by age groups
- Found: Different ages have different churn patterns
- Implication: Need demographic-specific strategies

**Step 4: Visualization & Communication**
- Built interactive Tableau dashboard
- Created 4 key visualizations
- Prepared for stakeholder communication

---

## Key Fundings

### Finding 1: Overall Churn Rate = 20.38%

**The Metric:**
- 2,038 customers out of 10,000 have churned
- 1 in 5 customers have left

**Why It Matters:**
- Baseline for measuring progress
- Industry average is 15-25% (we're middle)
- Industry leaders are at 15-17% (opportunity)

**Business Impact:**
- Annual revenue loss: $203,800 (at $100 LTV per customer)
- Replacement cost via acquisition: $509,500+ (5-7x churn cost)
- Total annual cost: ~$713,300

---

### Finding 2: Year 0-1 Customers Have HIGHEST Churn (23%)

**The Discovery:**
- New customers in first year: 23% churn (HIGHEST)
- Churn drops to 19% in Year 1-2
- This shows "survivor bias"—those surviving Year 1 become sticky

**Root Cause Analysis:**
- Onboarding experience is broken
- First-time user pain points exist
- Product education gaps
- Unclear value proposition to new customers

**Why It Matters:**
- Year 1 is make-or-break period
- This is THE highest impact intervention point
- Fixing this has massive leverage on overall churn

**Business Opportunity:**
- Reduce Year 0-1 churn from 23% → 18% (5% improvement)
- Retain additional 50 customers per 1,000-customer cohort
- Save $5,000+ per cohort (revenue + acquisition avoidance)
- Improve overall churn to 18.5% (vs current 20.38%)

---

### Finding 3: Years 4-7 Show STABILITY (17.22%)

**The Discovery:**
- Mid-tenure customers have lowest churn (17.22%)
- Most stable period in customer lifecycle
- Suggests engagement mechanisms are working well

**Root Cause Analysis:**
- Customers have proven product value
- Established usage habits
- Switching costs are higher
- Loyalty is established

**Why It Matters:**
- Shows what SUCCESS looks like
- Proof that retention mechanisms CAN work
- Blueprint for early-year strategies

**Business Opportunity:**
- Study what drives Year 4-7 retention
- Apply those strategies to Year 0-1 customers
- Get new customers to "sticky" phase faster
- Improve Year 0-1 churn through early engagement

---

### Finding 4: Year 9+ Customers Become VULNERABLE (21.75%)

**The Discovery:**
- Long-term customers (9+ years) show INCREASING churn
- Rise from 17.22% (Year 4-7) to 21.75% (Year 9+)
- Loyalty alone doesn't guarantee lifetime retention

**Root Cause Analysis:**
- Competing products become attractive after long tenure
- Product features may feel stale/outdated
- Changing financial needs (retirement, life stage)
- Bank taking them for granted (complacency)

**Why It Matters:**
- Long-term customers have high lifetime value
- Losing them is expensive to replace
- Competitive vulnerability window
- Shows need for ongoing engagement

**Business Opportunity:**
- Create loyalty recognition program
- Offer exclusive benefits for 9+ year customers
- Develop life-stage specific products
- Implement proactive relationship management
- Reduce Year 9+ churn from 21.75% → 17%

---

### Finding 5: Age Groups Show DIFFERENT Patterns

**The Discovery:**
- Different ages have different churn rates
- One-size-fits-all retention won't work
- Life stage (not just age) drives behavior

**Root Cause Analysis:**

| Age Group | Characteristics | Drivers |
|:----:|----|----|
| 18-24 | High mobility, career changes | Price-sensitive, mobile-first |
| 25-34 | Growing careers, stability-seeking | Investment features, digital tools |
| 35-44 | Family, mortgage, high switching costs | Stability important, family accounts |
| 45-54 | Established, relationship-focused | Premium service, wealth management |
| 55+ | Retirement-planning, security | Service quality, simplicity important |

**Why It Matters:**
- Enables targeted product development
- Personalized retention messaging works better
- Different communication channels by age
- Different product features by life stage

**Business Opportunity:**
- Develop age-specific retention strategies
- Create life-stage appropriate products
- Test different messaging by demographic
- Higher conversion on targeted offers

---

## Business Impact

### Current Annual Cost
| Item | Amount |
|---|---|
| Customers Lost (per 10k) | 2,038 |
| Revenue Loss @ $100 LTV | $203,800 |
| Acquisition Cost @ $250 CAC | $509,500 |
| **Total Annual Cost** | **$713,300** |

### Projected Annual Benefit (After Recommendations)
| Item | Amount |
|---|---|
| Target Churn | 17% (vs 20.38%) |
| Additional Customers Retained | 340/year |
| Revenue Saved | $34,000 |
| Acquisition Cost Avoided | $85,000 |
| **Total Annual Benefit** | **$119,000+** |

### ROI Analysis
- **Investment:** Moderate (process improvements, product enhancements)
- **Return:** $119,000+ annually
- **Payback Period:** 6-12 months
- **Conclusion:** Highly attractive investment

---

## Success Metrics

| Metric | Current | Target | Timeline |
|---|:---:|:---:|---|
| Overall Churn | 20.38% | 17% | 12 months |
| Year 0-1 Churn | 23% | 18% | 6 months |
| Year 9+ Churn | 21.75% | 17% | 9 months |
| Retention Rate | 79.62% | 83% | 12 months |
| Annual Savings | — | $119,000+ | 12 months |

---

## Conclusion

Customer churn is NOT random—it follows predictable, addressable patterns.

**The Key Insight:** Different customer lifecycle stages have different churn rates. By focusing retention efforts on critical periods (especially Year 0-1) and tailoring strategies by demographics, Wing Bank can significantly improve customer retention and profitability.

**The Opportunity:** Move from 20.38% to 17% churn through targeted, data-driven interventions.

**The Business Case:** Modest investment with significant ROI ($119,000+ annually) and competitive advantage.

**The Next Step:** Prioritize Year 0-1 onboarding improvement and begin implementation.

---

**Report Date:** November 2025