# Nutricosmetics Skills

Claude skills for people who sell food supplements and nutricosmetics online (collagen, beauty-from-within, wellness cures). Built by an e-commerce manager in the Swiss supplement industry, for the problems generic marketing skills miss: health-claim rules in every major market, cure-based retention and ad policies on health and beauty.

## Skills

| Skill | What it does |
| --- | --- |
| `global-claims-localizer` | Turns one claim into a compliant version for the US (FDA/FTC), EU, UK, Switzerland, Canada and Australia, with the registrations and platform gates (Amazon, Meta, Google, TikTok Shop) for each market |
| `claims-check` | Checks ads, pages, emails and briefs against Swiss (OIDAl annex 14) and EU (Reg. 1924/2006) health-claim rules and rewrites what fails |
| `supplement-product-page` | Writes or audits a product page that converts and includes the mandatory supplement mentions |
| `cure-retention-flows` | Email/SMS flows timed to the cure: onboarding, reorder before run-out, subscription, reviews, win-back |
| `meta-ads-health-beauty` | Angles, hooks and copy for Meta ads that respect personal-attribute and health policies |
| `influencer-brief-supplements` | Creator briefs with do/don't rules on claims, disclosure and usage rights |
| `supplement-subscription-economics` | Contribution margin, CAC, cohort LTV, payback and max CAC for cure-based businesses |

## Example

See [examples/global-claims-localizer.md](examples/global-claims-localizer.md): one US Amazon listing for a fictional collagen drink, localized for France, Switzerland and the UK.

## Install

**Claude Code:**
```
/plugin marketplace add Eloi2k/nutricosmetics-skills
/plugin install nutricosmetics-skills
```

**Claude.ai / any agent:** copy a skill folder into your skills directory, or paste the `SKILL.md` content into the conversation.

## Disclaimer

`claims-check` is a pre-check, not legal advice. Health-claim lists change: always confirm wording in the current annex 14 OIDAl (fedlex.admin.ch) or the EU Register of nutrition and health claims, and have packaging reviewed by a regulatory professional.

---

## 🇫🇷 En français

Des skills Claude pour vendre des compléments alimentaires et de la nutricosmétique en ligne : vérification des allégations santé (Suisse et UE), fiches produit conformes, flows de rétention calés sur la cure, pubs Meta santé/beauté, briefs influenceurs et rentabilité des abonnements. Les skills sont rédigés en anglais mais répondent dans la langue de l'utilisateur.

## Contributing

Issues and pull requests welcome, especially for other markets' claim rules (UK, US/FDA-FTC, Canada).

License: MIT
