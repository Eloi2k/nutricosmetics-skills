---
name: claims-check
description: Checks marketing copy for food supplements and nutricosmetics (collagen, beauty-from-within) against Swiss and EU health-claim rules before publishing. Use before any ad (Meta, Google), product page, email, influencer brief, landing page or packaging text that mentions skin, hair, nails, anti-aging, wrinkles, cellulite, health or results, and whenever the user asks "is this claim allowed?", "conformité", "allégation santé" or "can we say...".
---

# Nutricosmetics claims check (Switzerland + EU)

Food supplements are foods, not medicines. Every health or beauty-benefit statement must map to an authorized claim. Run this check on any copy before it ships, and rewrite anything that fails.

## Legal frame

- **Switzerland:** Ordonnance du DFI concernant l'information sur les denrées alimentaires (OIDAl, RS 817.022.16). Nutrition claims: annex 13. Health claims: annex 14 only (positive list, inspired by EU law). Any claim not in annex 14 needs prior OSAV/BLV authorization. Supplement-specific rules: Ordonnance du DFI sur les compléments alimentaires (OCAl).
- **EU / France (if shipping there):** Regulation (EC) 1924/2006 and the EU Register of nutrition and health claims (Regulation (EU) 432/2012 for general function claims).
- The lists change. Never rely on memory for exact wording: tell the user to confirm the claim in the current annex 14 OIDAl (fedlex.admin.ch) or the EU Register before final use, and say which entry you are relying on.

## How to check

1. **Extract every claim.** List each sentence, headline, hashtag, visual promise, before/after, testimonial and product name that implies an effect on the body, skin, hair, nails, weight, cellulite, aging or health.
2. **Classify each one:**
   - **Disease / medical claim** (prevents, treats, cures, heals, repairs damage, acne, eczema, inflammation, "anti-cellulite treatment", "reverses aging"): forbidden for a supplement. Rewrite or delete.
   - **Health claim** (effect on a body function): allowed only if it matches an authorized claim for a nutrient actually present at a significant amount in the product, with the condition of use met.
   - **Generic benefit** ("good for your skin", "glow from within", "beauty boost"): allowed only when accompanied by a specific authorized health claim next to it.
   - **Cosmetic / sensory / lifestyle wording** ("ritual", "premium", "Swiss made", taste, texture): usually fine if true and not misleading.
3. **Anchor claims on the authorized nutrient, not the hero ingredient.** Marine collagen, hyaluronic acid, ceramides and most botanicals have no authorized health claim in the EU lists. The compliant pattern is to attach the claim to a vitamin or mineral in the formula that has one. Typical candidates to verify in the current lists (check the product contains enough of the nutrient):
   - Vitamin C: contributes to normal collagen formation for the normal function of the skin; contributes to the protection of cells from oxidative stress.
   - Biotin, zinc, riboflavin, niacin, vitamin A, iodine: contribute to the maintenance of normal skin (wording differs by nutrient).
   - Biotin, zinc, selenium: maintenance of normal hair; zinc and selenium: maintenance of normal nails.
   - Copper: normal skin and hair pigmentation.
4. **Check numbers and studies.** Percentages ("+30% elasticity"), timelines ("results in 4 weeks") and "clinically proven" need a real study on the finished product or its ingredient at the same dose; flag them for the user to confirm the source. Never invent or extrapolate study results.
5. **Check testimonials and influencer content.** The brand is responsible for claims made by customers and creators it reposts or briefs. Apply the same rules; remove medical wording from quotes the brand reuses.
6. **Check mandatory supplement mentions** on product pages and packaging: the name "complément alimentaire", recommended daily dose, warning not to exceed it, statement that supplements do not replace a varied diet, keep out of reach of young children. Flag any that are missing.

## Output

Return a table with: original text, verdict (OK / reword / forbidden / needs proof), reason, compliant rewrite. Then the full corrected copy. Keep the brand's premium, sensory tone in rewrites; compliance does not require flat copy. End with the list of claims the user must verify in the current annex 14 OIDAl or EU Register, and recommend a regulatory or legal review for packaging and new product launches. State plainly that this is a pre-check, not legal advice.
