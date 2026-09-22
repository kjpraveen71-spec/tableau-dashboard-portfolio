# tableau-dashboard-portfolio
collection of tableau dashboards covering retail promotions , telecom customer analysis , supply chain delivery , and HR attrition
# Tableau Dashboard Portfolio

A collection of Tableau dashboards built to practice business-analyst style reporting across different domains: retail, telecom, supply chain, and HR.

Each dashboard lives in its own folder with the `.twbx` workbook and screenshots.

---

## 1. Retail Promotion Analysis
**Folder:** [`retail-promo-analysis/`](./retail-promo-analysis)

**Business question:** How effective were the Diwali and Sankranti promotional campaigns, and which promo types, products, stores, and cities drove (or lagged in) performance?

**Key findings:**
- Units sold nearly doubled after promo (2,09,050 → 4,35,473), but revenue dropped slightly (₹140.70M → ₹130.12M)
- BOGOF was the dominant promo type by volume (49.43% of units sold), well ahead of percentage-off and cashback offers
- Chennai contributed the largest share of post-promo revenue (₹2.5 crore+), far outpacing Vijayawada and Trivandrum
- A cluster of stores (STMLR-2, STMLR-1, STVSK-2) posted the lowest revenue growth, all under 20%

**Conclusion:** The promotions successfully drove volume but eroded overall revenue, most likely due to BOGOF's steep discount depth dominating the promo mix. Revenue is heavily concentrated in Chennai, and a specific set of underperforming stores would benefit from a different promo strategy rather than blanket BOGOF campaigns.

---

## 2. Telecom Customer Analytics
**Folder:** [`telecom-customer-analytics/`](./telecom-customer-analytics)

**Business question:** How do senior citizens differ from other customers in spend, payment method, and internet service usage?

**Key findings:**
- Senior citizens make up 50% of the 100-customer base, with an average revenue of ₹897 per customer
- Payment method preference among seniors splits evenly between Debit Card and Cash (50/50), while the full customer base splits nearly evenly across all four payment methods (~25% each)
- Senior citizen share is roughly balanced across DSL, Fiber Optic, and No Internet service (16–17 each)

**Conclusion:** Senior citizens show no strong skew in payment preference or internet service choice compared to the overall base. This suggests age alone isn't a meaningful segmentation variable here, and marketing or retention strategies likely need a different lens (e.g. tenure or contract type) to differentiate senior citizen behavior.

---

## 3. Supply Chain OTIF Delivery
**Folder:** [`supply-chain-otif/`](./supply-chain-otif)

**Business question:** How well is the supply chain meeting On-Time-In-Full (OTIF) delivery targets, and which customers or products are driving order volume and delivery performance?

**Key findings:**
- Of 57,096 total orders, On-Time delivery stood at 64.80% and In-Full delivery at 65.96%, but combined OTIF was only 43.82%
- OTIF % varies sharply by customer — from Propel Mart and Rel Fresh (~11–12%) down to Coolblue and Lotus Mart (~1–2%)
- Vijay Stores, Lotus Mart, and Rel Fresh are the top customers by order quantity
- Average order quantity (235K) slightly exceeds average delivery quantity (227K), pointing to a fulfillment shortfall

**Conclusion:** The large gap between individual On-Time (64.8%) and In-Full (65.96%) rates versus combined OTIF (43.82%) shows these failures mostly happen on different orders rather than overlapping — meaning fixing either metric alone won't fix OTIF. Performance is also highly customer-specific, so the root cause is more likely tied to specific routes or accounts than a single systemic issue.

---

## 4. HR Attrition Analysis
**Folder:** [`hr-attrition-analysis/`](./hr-attrition-analysis)

**Business question:** What factors are most associated with employee attrition — overtime, gender, job role, or education background?

**Key findings:**
- Overall attrition: 237 of 1,470 employees (~16%), skewed male (63.29%) vs female (36.71%)
- Employees working overtime show a higher attrition rate (33.76% male / 19.83% female) than those who don't (29.54% male / 16.88% female)
- Sales Executive and Research Scientist roles have the highest headcount at the top job-satisfaction level, while Human Resources and Manager roles are comparatively small
- Life Sciences (89) and Medical (63) are the largest education-field groups by attrition-linked headcount, consistent with the R&D-heavy roles in the workforce

**Conclusion:** Overtime is the clearest attrition driver in this dataset — attrition rates are consistently higher for employees who work overtime, regardless of gender. Attrition is not evenly distributed across departments or education backgrounds either, suggesting workload management (especially around overtime) is a more actionable lever than broad, company-wide retention policies.

---

## Tools used
Tableau Public / Tableau Desktop

## How to view
Open the `.twbx` file in Tableau Desktop or Tableau Public, or view the screenshots directly in each folder.
