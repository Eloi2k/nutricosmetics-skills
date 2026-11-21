---
name: cure-retention-flows
description: Designs email and SMS lifecycle flows timed to a supplement cure (collagen, beauty-from-within, wellness), from first order to reorder, subscription and win-back. Use when planning post-purchase, replenishment, reorder reminder, subscription conversion or win-back flows for supplements in Klaviyo, Shopify Email or similar.
---

# Cure retention flows

Supplements are a repeat purchase whose results take weeks. Most of the profit is in the second and third cure, and most customers stop before results show. Time every message to where the customer is in the cure.

## Inputs to collect

- Days of product per pack and recommended cure length (e.g. 30-day pack, 90-day cure).
- Shipping time per market (sets the reorder reminder).
- Subscription available? Terms (discount, skip, pause, cancel).
- Email/SMS tool and consent status per channel.
- Current repeat rate and time between orders, if known.

## Core flows

**1. Post-purchase onboarding (first order)**
- Day 0: order confirmation plus how and when to take it, one habit tip (anchor to an existing routine).
- Delivery day (or day 2-3 after shipping): "start today" with the ritual, what the first weeks feel like.
- Day 7: habit check, recipes or ways to take it, answer the top FAQ.
- Day 14: what to expect next and when; ask for a quick satisfaction signal.

**2. Replenishment / reorder**
- Trigger at: pack days − shipping days − 5 (so the product arrives before running out).
- Message: continuity of the cure, price per day, subscription offer as the default option.
- Reminder 3-4 days later if no order; last reminder on estimated run-out day.

**3. Subscription conversion**
- Offer after the first order is in use (around day 10-20), not at day 0 for new customers who have not tried it yet.
- Lead with convenience and cure continuity, then savings; state skip/pause/cancel clearly.

**4. Review and UGC request**
- After enough days for the customer to have an opinion (often day 21-30 for a 30-day pack), ask for a review; ask experience questions, never results or medical outcomes.

**5. Win-back**
- Trigger when expected reorder date + 15-30 days passes without order.
- Ask why they stopped (one-click reasons), then address the main reasons: price (smaller pack, subscription), taste/format, no visible result yet (explain timelines honestly), forgot (reminder setup).

## Rules

- Every claim in emails and SMS follows the same health-claim rules as ads; run claims-check on copy that mentions results.
- SMS only with explicit SMS consent; keep SMS for time-sensitive moments (delivery, run-out, last reminder).
- Suppress customers with an active subscription from reorder flows.
- Measure per flow: repeat purchase rate, time to second order, subscription take rate, revenue per recipient.

## Output

Return a flow map (trigger, delay, channel, goal per message), then subject line plus body for each message, then the metrics to watch.
