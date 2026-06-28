 # Customer Behavior & Retention Analysis

> ⚠️ **Note:** This was an early exploratory project focused on customer behavior only.  
> It was later connected to the revenue analysis to tell a more complete story:  
> 👉 [TheLook E-Commerce — Customer Retention Analysis](https://github.com/MEQDAD0904/thelook-ecommerce-customer-retention-analysis-)

---

## What This Project Is

A focused SQL and Power BI analysis on one question:

**Do customers come back after their first purchase — and what does that mean for revenue?**

This was exploratory work. No hypothesis framework was used. The goal was to understand customer behavior patterns before connecting them to revenue impact.

---

## What I Analyzed

- Repeat vs. one-time buyer ratio
- Revenue dependency on new vs. returning customers
- Customer order distribution
- Early signals of retention risk

---

## Dataset

| Table | Content |
|---|---|
| Orders | Transaction records |
| Order Items | Product-level detail |
| Customers | Customer profiles |
| Products | Product catalog |

---

## Tools

- SQL — Data extraction and analysis
- Power BI — Dashboard and visualization

---

## Key Findings

**1. Retention is critically low**  
~96.88% of customers placed only one order. Repeat rate is approximately 3%.

**2. Revenue depends on acquisition, not loyalty**  
Growth is driven by new customers. Returning customers contribute very little to total revenue.

**3. High-value customers don't return either**  
Even customers with large first orders showed no repeat behavior.

**4. Possible explanations (not confirmed causes)**  
Three patterns worth investigating further:
- Undelivered or late orders may damage the first experience
- Product type may not naturally encourage repeat purchases
- No visible retention mechanism (loyalty program, follow-up offers)

> These are observations, not proven root causes. Confirming them would require deeper hypothesis testing — which the later project addresses.

---

## What I Learned From This Project

Analyzing customer behavior in isolation showed the *what* but not the *why*.

A 3% repeat rate is alarming — but without connecting it to revenue structure and order patterns, it's hard to know where to intervene.

This is what led me to combine both analyses into one connected framework:  
👉 [TheLook E-Commerce — Customer Retention Analysis](https://github.com/MEQDAD0904/thelook-ecommerce-customer-retention-analysis-)

---

## Project Files

| File | Description |
|---|---|
| `03_customer_analysis.sql` | SQL queries for customer segmentation |
| `customer_analysis_overview.png` | Main dashboard overview |
| `customer_behavior.png` | Customer distribution visual |

---

## How to Run

1. Load the datasets: `orders`, `order_items`, `customers`, `products`
2. Run `03_customer_analysis.sql`
3. Open dashboard images to explore visuals
