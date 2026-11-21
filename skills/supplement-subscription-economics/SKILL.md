---
name: supplement-subscription-economics
description: Models the unit economics of a supplement or nutricosmetics brand sold in cures and subscriptions: contribution margin, CAC, payback, LTV by cohort, and the effect of subscription discounts. Use when setting subscription pricing, deciding how much to pay per customer on Meta/Google, judging first-order ROAS, or forecasting repeat revenue.
---

# Supplement subscription economics

A cure-based business is judged on what a customer is worth over several cures, not on the first order. Build the numbers from the user's data; label anything missing as MISSING instead of estimating silently.

## Inputs

- Price per pack (one-time and subscription), days per pack, VAT treatment per market.
- COGS per pack, packaging, pick-and-pack, shipping cost, payment fees, average discounts.
- Ad spend and new customers per channel for the same period (CAC).
- Repeat data: share of customers placing order 2, 3, 4...; subscription share; monthly subscription churn.

## Calculations

1. **Contribution margin per order** = net revenue (excl. VAT, after discounts) − COGS − packaging − fulfillment − shipping − payment fees.
2. **First-order margin after CAC** = contribution margin of order 1 − CAC. Negative is normal for supplements; the question is how fast it is recovered.
3. **Cohort LTV (contribution)** = sum over orders of (probability of reaching order n × contribution margin of order n), over 6 and 12 months. Use subscription churn for subscribers and repeat curves for one-time buyers separately.
4. **Payback** = number of orders (and days, using pack length) needed for cumulative contribution to cover CAC.
5. **Break-even ROAS / max CAC** = target CAC that keeps payback within the chosen window (e.g. 90 days or 3 cures).
6. **Subscription discount test**: compare contribution LTV with and without discount using expected change in retention; a 10-15% discount must buy enough extra orders to pay for itself.

## Outputs

- A table per segment (subscription vs one-time, per channel if data allows): margin per order, CAC, 6- and 12-month LTV, LTV:CAC, payback.
- Max CAC and break-even first-order ROAS to give to the ads team.
- The 2-3 levers with the most impact (e.g. pack size, subscription take rate, reorder timing) and what data is MISSING.

Use code or a spreadsheet for the arithmetic rather than mental math, and show formulas so the user can check them.
