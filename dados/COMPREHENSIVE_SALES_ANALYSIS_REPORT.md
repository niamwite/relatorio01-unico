# COMPREHENSIVE SALES ANALYSIS REPORT
## Unico Investment - Business Intelligence Dashboard

**Generated:** February 8, 2026
**Database:** Supabase PostgreSQL
**Analysis Period:** Historical data through 2026
**Total Records Analyzed:** 43,591 deals + 30,856 leads

---

## EXECUTIVE SUMMARY

### Key Metrics Overview

| Metric | Value | Status |
|--------|-------|--------|
| **Total Pipeline** | 43,591 deals | |
| **Won Deals** | 990 (2.3%) | 🔴 CRITICAL |
| **Lost Deals** | 28,400 (65.2%) | 🔴 HIGH |
| **In Progress** | 14,201 (32.6%) | ⚠️ WARNING |
| **Win Rate** | 3.4% | 🔴 CRITICAL |
| **Total Pipeline Value** | R$ 1.26 billion | |
| **Avg Deal Size** | R$ 1.32 million | |
| **Median Deal Size** | R$ 543,000 | |

### Critical Findings

1. **CRITICAL: Extremely Low Win Rate (3.4%)** - Industry standard is 15-25%
2. **HIGH: Pipeline Bloat (32.6% stuck)** - 14,201 deals not progressing
3. **HIGH: No Loss Reason Tracking** - Cannot understand why deals are lost
4. **WARNING: Revenue Decline** - Month-over-month average growth: -10.7%

---

## 1. PIPELINE HEALTH ANALYSIS

### 1.1 Overall Conversion Funnel

```
Total Leads (30,856)
    ↓ [3.2% conversion]
Won Deals (990)
    ↓
Lost Deals (28,400)
    ↓
In Progress (14,201)
```

**Lead-to-Deal Conversion Rate: 3.21%**
- Status: ⚠️ ACCEPTABLE (industry average: 2-5%)

### 1.2 Win Rate Analysis

| Stage | Deals | % of Total |
|-------|-------|------------|
| **Won** | 990 | 2.3% |
| **Lost** | 28,400 | 65.2% |
| **In Progress** | 14,201 | 32.6% |

**Win Rate: 3.4%** (Won / Won + Lost)

🔴 **CRITICAL ISSUE:** Win rate is 4-7x below industry standard (15-25%)

### 1.3 Lost Deals by Stage

| Stage | Count | % of Lost |
|-------|-------|-----------|
| TENTANDO CONTATO (Trying to Contact) | 28,399 | 99.99% |
| EM ATENDIMENTO (In Service) | 1 | 0.01% |

**Insight:** 99.99% of lost deals happen at first contact attempt. This indicates:
- Poor lead quality
- Wrong contact information
- Lack of interest from prospects
- Ineffective initial outreach

### 1.4 Time to Close Analysis

| Metric | Days |
|--------|------|
| **Mean** | 46.7 days |
| **Median** | 23.0 days |
| **Fast Closers** (Q1) | ≤11 days |
| **Slow Closers** (Q3) | ≥48 days |
| **Fastest Deal** | -1 day* |
| **Longest Deal** | 963 days (2.6 years!) |

*\*Negative day indicates data error*

**Key Insight:** Huge variance in closing speed (11 days vs 48+ days)
- **250 deals** closed quickly (≤11 days)
- **253 deals** took very long (≥48 days)

**Recommendation:** Study fast closers to replicate success patterns

---

## 2. SALES TEAM PERFORMANCE

### 2.1 Top Performers by Deal Count

| Rank | Salesperson | Deals | Team |
|------|-------------|-------|------|
| 🥇 | **Lucimara- HAKA** | 73 | HAKA |
| 🥈 | Barbara Costa - Bravus | 40 | BRAVUS |
| 🥉 | Carolina Bravus | 38 | BRAVUS |
| 4 | FERNANDA SOUZA MIGLIARI - HAKA | 37 | HAKA |
| 5 | Leonora \| HAKA | 34 | HAKA |
| 6 | Daiane Diniz - Haka | 29 | HAKA |
| 7 | Brunna Cavalheiro - Bravus | 26 | BRAVUS |
| 8 | Ane Borges - Haka | 26 | HAKA |
| 9 | PABLLO - HAKA | 26 | HAKA |
| 10 | MICAELY REGINA VALE ITALIANO - HAKA | 25 | HAKA |

### 2.2 Top Performers by Total Value

| Rank | Salesperson | Total Value | Avg Deal |
|------|-------------|-------------|----------|
| 🥇 | **Camila Valadares - LOTUS** | R$ 171M | R$ 10.7M |
| 🥈 | **Lucimara- HAKA** | R$ 157M | R$ 2.1M |
| 🥉 | **Leonora \| HAKA** | R$ 60.7M | R$ 1.8M |
| 4 | Larissa - Haka | R$ 57.0M | - |
| 5 | MICAELY REGINA VALE ITALIANO - HAKA | R$ 56.0M | R$ 2.2M |

**Insight:** Camila Valadares closes fewer deals (16) but with highest average size (R$ 10.7M)

### 2.3 Performance Distribution

| Metric | Value |
|--------|-------|
| **Total Salespeople** | 110 |
| **Average Deals/Person** | 9.0 |
| **Median Deals/Person** | 5.0 |
| **Top 10% Handle** | 378 deals (38.2% of total) |

### 2.4 Pareto Analysis (80/20 Rule)

- **43 salespeople (39.1%)** generate **80%** of won deals
- **Remaining 67 salespeople (60.9%)** generate only **20%**

🔴 **CRITICAL FINDING:** Extreme performance inequality
- Top performers are carrying the team
- Bottom 60% of salespeople are underperforming

**Recommendation:** Implement mentorship program where top performers teach bottom performers

---

## 3. DEAL SIZE ANALYSIS

### 3.1 Deal Size Statistics

| Metric | Value |
|--------|-------|
| **Mean** | R$ 1,318,834 |
| **Median** | R$ 543,000 |
| **Mode** | R$ 300,000 |
| **Std Dev** | R$ 5,394,001 |
| **Min** | R$ 1,020 |
| **Max** | R$ 147,000,000 |

### 3.2 Deal Size Distribution

| Size Range | Count | % | Total Value |
|------------|-------|---|-------------|
| < R$ 100k | 30 | 3.1% | R$ 1.5M |
| R$ 100k-300k | 232 | 24.2% | R$ 46.4M |
| R$ 300k-500k | 194 | 20.3% | R$ 72.8M |
| R$ 500k-1M | 246 | 25.7% | R$ 167.6M |
| **> R$ 1M** | **256** | **26.7%** | **R$ 975.6M** |

**Insight:** Large deals (>R$ 1M) represent:
- 26.7% of deals by count
- **77.2% of total value**

### 3.3 Large Deals Analysis (≥ R$ 1M)

| Metric | Value |
|--------|-------|
| **Count** | 281 deals (29.3%) |
| **Total Value** | R$ 975.6M |
| **Average** | R$ 3.47M |

### 3.4 Value Concentration Risk

- **Top 10 deals** = R$ 327.4M (**25.9%** of total pipeline value)
- 🔴 **WARNING:** High concentration risk
- Loss of top 10 deals would impact 26% of revenue

**Recommendation:** Diversify pipeline with more mid-size deals

---

## 4. TEMPORAL ANALYSIS

### 4.1 Sales by Day of Week

| Day | Deals | % |
|-----|-------|---|
| **Monday** | **243** | **24.5%** |
| Tuesday | 190 | 19.2% |
| Wednesday | 153 | 15.5% |
| Thursday | 157 | 15.9% |
| Friday | 128 | 12.9% |
| Saturday | 43 | 4.3% |
| Sunday | 76 | 7.7% |

**Insight:** Monday is clearly the best day (24.5% of deals)
- **Recommendation:** Schedule important calls and meetings on Mondays

### 4.2 Monthly Trend (Last 12 Months)

| Month | Deals | Trend |
|-------|-------|-------|
| 2025-02 | 31 | |
| 2025-03 | 41 | +32% |
| 2025-04 | 27 | -34% |
| 2025-05 | 31 | +15% |
| 2025-06 | 44 | +42% |
| 2025-07 | 31 | -30% |
| 2025-08 | 29 | -6% |
| 2025-09 | 40 | +38% |
| 2025-10 | 24 | -40% |
| 2025-11 | 26 | +8% |
| 2025-12 | 9 | -65% |
| 2026-01 | 2 | -78% |

🔴 **CRITICAL:** Strong downward trend in recent months
- **Month-over-Month Average Growth: -10.7%**
- December-January showed massive decline (-77.8%)

### 4.3 Hourly Pattern

| Hour | Deals | % | Insight |
|------|-------|---|---------|
| **08:00** | **141** | **14.2%** | **Peak hour** |
| 09:00 | 116 | 11.7% | Strong |
| 07:00 | 67 | 6.8% | Building |
| 16:00 | 67 | 6.8% | Afternoon peak |

**Best Hours:** 07:00-09:00 (32.7% of daily deals)

**Recommendation:** Focus sales activities between 07:00-10:00

---

## 5. LEAD SOURCE & QUALITY ANALYSIS

### 5.1 Lead Volume

| Metric | Value |
|--------|-------|
| **Total Leads** | 30,856 |
| **Date Range** | 2025-10-01 to 2026-02-08 |
| **Duration** | ~4 months |

### 5.2 Desired Credit Amount

| Range | Count | % |
|-------|-------|---|
| **R$ 300k-600k** | **22,530** | **73.0%** |
| R$ 600k-1M | 4,289 | 13.9% |
| R$ 1M-5M | 2,381 | 7.7% |
| > R$ 10M | 898 | 2.9% |
| R$ 5M-10M | 758 | 2.5% |

**Insight:** 73% of leads want R$ 300k-600k
- This is below your average deal size (R$ 543k median)
- May indicate lead quality mismatch

### 5.3 Monthly Revenue (Faturamento)

| Range | Count | % |
|-------|-------|---|
| **R$ 50k-70k** | **13,126** | **42.5%** |
| > R$ 100k | 7,593 | 24.6% |
| R$ 50k-70k | 3,696 | 12.0% |
| R$ 70k-90k | 2,950 | 9.6% |

**Insight:** Majority of leads (42.5%) report R$ 50k-70k monthly revenue
- Questionable capacity for R$ 300k+ loans

### 5.4 Urgency Levels

| Urgency | Count | % |
|---------|-------|---|
| **Imediatamente** (Immediately) | **25,604** | **83.0%** |
| 3-6 months | 5,252 | 17.0% |

**Insight:** 83% claim "immediate" urgency
- This is suspiciously high
- May indicate lead quality issues or desperation

### 5.5 Loan Purposes

| Purpose | Count | % |
|---------|-------|---|
| **Expansão do negócio** (Business expansion) | **21,672** | **70.2%** |
| Troca de dívida (Debt refinancing) | 4,697 | 15.2% |
| Investimentos em maquinários/tecnologias | 4,487 | 14.5% |

**Insight:** Clear pattern - growth financing is dominant (70%)

### 5.6 Traffic Sources

| Source | Count | % |
|--------|-------|---|
| **Paid** | **30,848** | **100.0%** |
| Organic | 8 | 0.0% |

🔴 **CRITICAL:** 100% paid traffic = dependency on ads
- Zero organic growth
- Vulnerable to ad cost increases

**Recommendation:** Invest in SEO, content marketing, and inbound strategies

---

## 6. MONTE CARLO SIMULATIONS - 2025 FORECAST

### 6.1 Historical Data

| Year | Deals | Growth |
|------|-------|--------|
| 2021 | 2 | |
| 2022 | 3 | +50% |
| 2023 | 266 | +8,767% |
| 2024 | 346 | +30% |
| 2025 | 377 | +9% |
| 2026 | 2 | -99% (incomplete) |

### 6.2 Monthly Statistics

| Metric | Value |
|--------|-------|
| **Mean Deals/Month** | 82.5 |
| **Std Deviation** | 31.3 |
| **Coefficient of Variation** | 37.9% |

### 6.3 2025 Forecast - Total Deals

| Percentile | Deals |
|------------|-------|
| **Mean** | **18,286** |
| **Median** | 18,262 |
| **80% CI** | [15,746 - 20,854] |
| **90% CI** | [15,041 - 21,557] |
| **95% CI** | [14,413 - 22,186] |

**Note:** Forecast based on historical patterns with growth adjustments
- Current downward trend (-10.7% MoM) not fully factored

### 6.4 2025 Monthly Forecast

| Month | Mean | Median | P10 | P90 |
|-------|------|--------|-----|-----|
| January | 1,347 | 1,351 | 610 | 2,091 |
| February | 1,121 | 1,110 | 370 | 1,850 |
| March | 1,256 | 1,258 | 518 | 2,017 |
| April | 994 | 980 | 240 | 1,702 |
| May | 1,093 | 1,092 | 351 | 1,832 |
| June | 1,310 | 1,314 | 573 | 2,054 |
| **July** | **1,715** | **1,721** | **962** | **2,461** |
| **August** | **2,013** | **2,017** | **1,277** | **2,757** |
| **September** | **2,273** | **2,276** | **1,536** | **3,016** |
| **October** | **2,666** | **2,665** | **1,924** | **3,405** |
| November | 1,772 | 1,776 | 1,017 | 2,517 |
| December | 728 | 703 | 0 | 1,443 |

**Seasonal Pattern:** Strongest months predicted for August-October

### 6.5 2025 Value Forecast

| Percentile | Value |
|------------|-------|
| **Mean** | **R$ 51.5 billion** |
| **Median** | R$ 51.5 billion |
| **80% CI** | R$ 44.4B - R$ 58.8B |
| **90% CI** | R$ 42.3B - R$ 60.9B |

---

## 7. STRATEGIC BUSINESS RECOMMENDATIONS

### 🔴 CRITICAL PRIORITY

#### Recommendation #1: Fix Lead Qualification
**Issue:** Extremely low win rate (3.4% vs industry 15-25%)
**Impact:** Losing 28,400 deals vs winning only 990

**Actions:**
1. **Implement Lead Scoring Model:**
   - Score leads 0-100 based on: revenue, urgency, credit amount, capacity
   - Only accept leads with score ≥ 60
   - Auto-reject low-quality leads

2. **Verify Lead Capacity:**
   - Request proof of revenue before investing time
   - Cross-check requested amount vs reported revenue
   - Flag suspicious "immediate" urgency claims

3. **Improve Initial Contact:**
   - 99.99% of deals lost at "Tentando Contato" stage
   - Script and training for first call
   - Multi-channel outreach (phone, WhatsApp, email)

**Expected Improvement:** Win rate could increase to 8-12% (3-4x current)

---

### 🟠 HIGH PRIORITY

#### Recommendation #2: Fix Pipeline Bloat
**Issue:** 32.6% of deals (14,201) stuck in progress
**Impact:** Wasted resources, clogged pipeline

**Actions:**
1. **Implement Deal Aging Rules:**
   - Auto-close deals inactive for 30+ days
   - Alert at 14 days of inactivity
   - Require next-step date for all active deals

2. **Pipeline Velocity Metrics:**
   - Track average time in each stage
   - Set stage duration limits
   - Identify bottlenecks

3. **Regular Pipeline Cleanup:**
   - Monthly review of stagnant deals
   - Force advance or close decision

**Expected Improvement:** Pipeline velocity could increase 40%

---

#### Recommendation #3: Implement Loss Reason Tracking
**Issue:** Loss reasons not tracked (all NULL)
**Impact:** Cannot understand why deals are lost

**Actions:**
1. **Make Loss Reason Mandatory:**
   - Required field in CRM before closing as lost
   - Dropdown with standard reasons:
     * Price too high
     * Found better offer
     * Not interested
     * Lack of capacity
     * Poor communication
     * Other (specify)

2. **Track Lost Deal Reasons:**
   - Monthly analysis of loss patterns
   - Identify root causes
   - Implement fixes

**Expected Improvement:** Will reveal patterns to systematically reduce churn

---

#### Recommendation #4: Address Sales Team Performance Inequality
**Issue:** 39.1% of salespeople generate 80% of revenue
**Impact:** Underperforming majority burning leads

**Actions:**
1. **Mentorship Program:**
   - Pair top performers with bottom 60%
   - Weekly shadowing sessions
   - Share best practices

2. **Performance-Based Incentives:**
   - Tiered commission structure
   - Bonuses for hitting targets
   - Recognition programs

3. **Training & Development:**
   - Sales bootcamp for underperformers
   - Product knowledge training
   - Objection handling workshops

**Expected Improvement:** Bottom 60% could double productivity

---

### 🟡 MEDIUM PRIORITY

#### Recommendation #5: Reduce Value Concentration Risk
**Issue:** Top 10 deals = 25.9% of total value
**Impact:** Vulnerable to losing key deals

**Actions:**
1. **Diversify Pipeline:**
   - Focus on mid-size deals (R$ 500k-2M)
   - Build more balanced portfolio

2. **Key Account Management:**
   - Dedicated support for mega-deals
   - Regular check-ins
   - Relationship building

**Expected Improvement:** More predictable and stable revenue

---

#### Recommendation #6: Fix Downward Revenue Trend
**Issue:** Month-over-month growth: -10.7%
**Impact:** December-January showed -77.8% decline

**Actions:**
1. **Investigate Recent Decline:**
   - What changed in October?
   - Market conditions?
   - Competition?
   - Internal issues?

2. **Stabilize Sales Process:**
   - Consistent lead generation
   - Regular sales activities
   - Avoid seasonal dips

**Expected Improvement:** Return to positive growth trajectory

---

#### Recommendation #7: Invest in Organic Growth
**Issue:** 100% paid traffic, 0% organic
**Impact:** Vulnerable to ad cost increases

**Actions:**
1. **SEO & Content Marketing:**
   - Blog with business financing tips
   - Educational content
   - Case studies

2. **Inbound Marketing:**
   - Free tools/calculators
   - Webinars
   - Whitepapers

3. **Referral Program:**
   - Incentivize referrals
   - Partner with complementary businesses

**Expected Improvement:** 20-30% organic traffic within 12 months

---

## 8. DOMAIN-DRIVEN DESIGN INSIGHTS

### 8.1 Customer Segmentation

**High-Value Segment (>R$ 1M deals):**
- 26.7% of deals, 77.2% of value
- Characteristics: Larger companies, proven revenue, established
- Strategy: White-glove service, dedicated support

**Mid-Value Segment (R$ 300k-1M):**
- 46.0% of deals, 18.7% of value
- Characteristics: Growing companies, need capital
- Strategy: Standardized process, faster approval

**Low-Value Segment (<R$ 300k):**
- 27.2% of deals, 4.1% of value
- Characteristics: Smaller businesses, higher risk
- Strategy: Automated process, minimum thresholds

### 8.2 Behavioral Patterns

**Fast Closers (≤11 days):**
- 250 deals closed quickly
- Characteristics: Clear need, ready to buy, good credit
- Strategy: Fast-track approval, minimal friction

**Slow Closers (≥48 days):**
- 253 deals took very long
- Characteristics: Shopping around, uncertain, complex needs
- Strategy: Build relationship, provide value, overcome objections

### 8.3 Pricing Optimization

**Current Deal Size Distribution:**
- Mode: R$ 300k (most common)
- Median: R$ 543k
- Mean: R$ 1.32M (skewed by large deals)

**Opportunity:**
- Shift focus from many small deals to fewer larger deals
- Target companies with R$ 100k+ monthly revenue
- Minimum deal size: R$ 500k

---

## 9. ACTION PLAN (Next 90 Days)

### Month 1: Foundation
- [ ] Implement lead scoring model
- [ ] Make loss reasons mandatory in CRM
- [ ] Train sales team on first-call script
- [ ] Set up deal aging alerts

### Month 2: Process
- [ ] Launch mentorship program
- [ ] Implement pipeline cleanup (close stale deals)
- [ ] Create performance-based incentives
- [ ] Start tracking key metrics weekly

### Month 3: Growth
- [ ] Launch SEO/content marketing
- [ ] Refine lead qualification based on data
- [ ] Scale successful patterns
- [ ] Review and adjust strategies

---

## 10. KEY PERFORMANCE INDICATORS (KPIs)

### Track These Metrics Weekly

| KPI | Current | Target (90 days) | Target (12 months) |
|-----|---------|------------------|-------------------|
| **Win Rate** | 3.4% | 8% | 15% |
| **Pipeline Velocity** | N/A | 30 days | 21 days |
| **Deals per Salesperson** | 9.0 | 12 | 18 |
| **Avg Deal Size** | R$ 1.32M | R$ 1.5M | R$ 2.0M |
| **Lead-to-Deal Conversion** | 3.2% | 5% | 6% |
| **Pipeline Bloat** | 32.6% | 20% | 15% |

---

## CONCLUSION

### The Good News
✅ Strong total pipeline value (R$ 1.26B)
✅ Top performers closing significant deals
✅ Clear pattern in lead sources and purposes
✅ Monday morning identified as best selling time

### The Bad News
🔴 Win rate (3.4%) is 4-7x below industry standard
🔴 99.99% of deals lost at first contact
🔴 Revenue declining (-10.7% month-over-month)
🔴 No loss reason tracking
🔴 Extreme performance inequality (Pareto imbalance)
🔴 100% dependency on paid traffic

### The Path Forward
Focus on the **CRITICAL** priorities first:
1. Fix lead qualification (biggest impact)
2. Improve first contact (biggest loss point)
3. Track loss reasons (unlock insights)
4. Train bottom performers (increase productivity)

**Expected Impact:** Implementing these recommendations could potentially **triple the win rate** from 3.4% to 10%+ within 6-12 months, resulting in:
- **Additional won deals:** +1,961 to +2,941
- **Additional revenue:** +R$ 2.6B to +R$ 3.9B

---

**Report prepared by:** Senior Data Analyst & BI Expert
**Analysis tools:** Python, pandas, numpy, scipy, Monte Carlo simulations
**Database:** Supabase PostgreSQL

---

*This report is confidential and intended for internal use only.*
