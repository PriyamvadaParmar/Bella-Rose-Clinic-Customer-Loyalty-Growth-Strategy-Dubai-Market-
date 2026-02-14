# KPI Dashboard Concept

## Executive View
- Total Revenue
- Repeat Revenue %
- Membership Penetration
- Capacity Utilization %

## Operational View
- Membership Conversions (Daily)
- Upsell Performance by Staff
- Tier Distribution
- Revenue Trend (6 Months)

## Expansion Trigger Panel
- Repeat Revenue ≥ 55%
- Capacity ≥ 85%
- Membership ≥ 40%


| A     | B             | C                | D                | E              | F           | G            |
| ----- | ------------- | ---------------- | ---------------- | -------------- | ----------- | ------------ |
| Month | Total Revenue | Unique Customers | Repeat Customers | Active Members | Total Slots | Booked Slots |


| H        | I            | J    | K          |
| -------- | ------------ | ---- | ---------- |
| Repeat % | Membership % | ARPC | Capacity % |



**Membership_Tracker**
Track detailed membership movement.
| Customer ID | Customer Name | Annual Spend | Tier | Join Date | Staff Assigned | Wallet Credit |


Optional Tier Logic Formula:

**Excel to auto-assign tier:**
=IF(C2>=30000,"Platinum",
 IF(C2>=15000,"Gold",
 IF(C2>=5000,"Silver","None")))

# 📊 Excel KPI Tracker – Formula Logic & Risk Considerations  
Bella Rose Clinic – Loyalty & Expansion Strategy

---

# 1️⃣ Dashboard Sheet Formulas

## Repeat Customer %

Formula:
= D2 / C2

Where:
D2 = Repeat Customers  
C2 = Total Unique Customers  

Purpose:
Measures customer retention effectiveness.

---

## Membership Penetration %

Formula:
= E2 / C2

Where:
E2 = Active Members  
C2 = Total Unique Customers  

Purpose:
Tracks adoption of loyalty program.

---

## ARPC (Average Revenue Per Customer)

Formula:
= B2 / C2

Where:
B2 = Total Revenue  
C2 = Unique Customers  

Purpose:
Measures revenue efficiency per customer.

---

## Capacity Utilization %

Formula:
= G2 / F2

Where:
G2 = Booked Slots  
F2 = Total Available Slots  

Purpose:
Indicates operational efficiency and readiness for scaling.

---

# 2️⃣ Membership Tier Auto-Assignment Logic

Formula:
=IF(C2>=30000,"Platinum",
 IF(C2>=15000,"Gold",
 IF(C2>=5000,"Silver","None")))

Where:
C2 = Annual Spend

Purpose:
Automatically assigns membership tier based on spending.

---

# 3️⃣ Upsell Conversion %

Formula:
= D2 / C2

Where:
D2 = Packages Sold  
C2 = Total Consultations  

Purpose:
Measures effectiveness of sales conversion by doctors.

---

# 4️⃣ Staff Incentive Calculation

If average membership value assumed = 5,000 AED  
Commission rate = 2%

Formula:
= (B2 * 5000 * 0.02)

Where:
B2 = Number of Membership Conversions

Purpose:
Calculates performance-linked incentive payout.

---

# 5️⃣ Expansion Trigger Status Logic

## KPI Status Check

Formula:
=IF(B2>=C2,"Met","Not Met")

Where:
B2 = Current KPI Value  
C2 = Target Threshold  

Purpose:
Checks whether KPI meets expansion criteria.

---

## Final Expansion Decision

Formula:
=IF(COUNTIF(D2:D5,"Met")=4,"Ready for Expansion","Optimize Current Clinic")

Purpose:
Ensures expansion is only approved when all 4 conditions are satisfied.

---

# 6️⃣ Possible Management Objections & Responses

---

## Objection 1: “We are already profitable. Why complicate things?”

Response:
This system does not complicate operations.
It reduces risk before expansion and ensures predictable revenue.

Profit today does not guarantee scalable profit tomorrow.

---

## Objection 2: “Second branch will bring more revenue anyway.”

Response:
Opening a branch increases:
- Rent
- Staffing cost
- Marketing cost
- Operational complexity

If retention is optimized first, second branch becomes a safer and faster ROI decision.

---

## Objection 3: “Staff may resist new tracking.”

Response:
Tracking is tied directly to incentives.
When revenue increases, staff income increases.
Resistance reduces when benefits are visible.

---

## Objection 4: “Tracking for 6 months delays growth.”

Response:
6 months of structured data ensures:
- Lower expansion risk
- Higher success probability
- Stronger investor confidence
- Better cash flow stability

Delayed expansion is safer expansion.

---

## Objection 5: “Membership discounts will reduce margins.”

Response:
Wallet credit increases repeat visits.
Higher lifetime value compensates small discounts.
Retention cost is lower than acquisition cost.

---

# 7️⃣ Strategic Safeguard

This KPI model ensures:

- Data-driven scaling
- Financial discipline
- Measurable performance
- Controlled growth
- Leadership-level decision making

Minimum data collection period before expansion:
6 months

 
