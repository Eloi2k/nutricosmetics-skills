# Example: global-claims-localizer

Fictional brand and product. The output shows the format the skill returns; confirm every claim in the official lists before real use.

## Input

> **LUMÉA Collagen Glow** — marine collagen drink, one stick per day.
> Per stick: hydrolysed marine collagen 5,000 mg, hyaluronic acid 100 mg, vitamin C 80 mg (100% NRV), zinc 2 mg (20% NRV), biotin 15 µg (30% NRV).
>
> Source copy (US Amazon listing):
> - "Clinically proven to reduce wrinkles by 35% in 8 weeks"
> - "Clears acne and calms eczema from within"
> - "Boosts collagen and reverses skin aging"
> - "Stronger hair and nails"
> - "Recommended by 200+ dermatologists"
>
> Target markets: France, Switzerland, United Kingdom.

## Output

### 1. Claim by claim

| Source claim | US (source) | France / EU | Switzerland | UK |
| --- | --- | --- | --- | --- |
| Reduces wrinkles by 35% in 8 weeks | OK only if a controlled study on this product supports it, plus FDA disclaimer | Remove: collagen has no authorized claim | Remove | Remove |
| Clears acne, calms eczema | Remove: disease claim | Remove | Remove | Remove |
| Boosts collagen, reverses aging | "Supports the body's collagen production" OK; drop "reverses" | Adapt: "Vitamin C contributes to normal collagen formation for the normal function of skin" | Adapt (same claim, annex 14 OIDAl) | Adapt (check GB register) |
| Stronger hair and nails | "Supports healthy hair and nails" | Adapt: "Zinc contributes to the maintenance of normal hair and nails"; "Biotin contributes to the maintenance of normal hair" | Adapt | Adapt |
| Recommended by 200+ dermatologists | OK if true and documented | Remove: references to recommendations by individual health professionals are not allowed with health claims | Check national rule | Check |

### 2. Localized copy (France, in French)

> LUMÉA Collagen Glow : 5 000 mg de collagène marin et d'acide hyaluronique, avec vitamine C, zinc et biotine. La vitamine C contribue à la formation normale de collagène pour assurer la fonction normale de la peau. Le zinc contribue au maintien de cheveux et d'ongles normaux. La biotine contribue au maintien d'une peau normale.
>
> Complément alimentaire. Ne pas dépasser la dose journalière recommandée. Ne se substitue pas à une alimentation variée et équilibrée ni à un mode de vie sain. Tenir hors de portée des jeunes enfants. Contient : poisson.

### 3. Market-entry gates

| Market | Before selling |
| --- | --- |
| France | Notify the supplement before first sale (Téléicare, DGCCRF); French label |
| Switzerland | Annex 14 OIDAl claims; OCAl mandatory mentions |
| UK | GB claims register; check label operator address rules |

### 4. Evidence gaps

- The 35% wrinkle figure: needs the study design (placebo? n? duration?) even for the US.
- Dermatologist count: needs documentation; unusable in the EU either way.
