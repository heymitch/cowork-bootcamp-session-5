---
name: digital-product
description: Build a digital product from idea to live sale. Triggers — "build a digital product", "idea to sale", "find product ideas", "validate idea", "outline product", "8-question framework", "name my product", "generate titles", "write the product", "write the ebook", "design my product", "product cover", "launch my product", "launch kit"
user-invocable: false
---

# Digital Product — Router

## Preflight

Check for config.md in the user's workspace. If it exists, load voice profile. If not, proceed — it is optional.

## Routing

**Full pipeline** ("build a digital product", "idea to sale", "zero to one"):
Run in order: idea-finder > topic-validator > outline-builder > title-generator > content-writer > design-advisor > launch-kit

**Individual skills:**

| Intent | Skill |
|--------|-------|
| "find product ideas", "what should I build" | `../idea-finder/SKILL.md` |
| "validate this idea", "test my product idea" | `../topic-validator/SKILL.md` |
| "outline my product", "8-question framework" | `../outline-builder/SKILL.md` |
| "name my product", "generate titles" | `../title-generator/SKILL.md` |
| "write my product", "write the ebook" | `../content-writer/SKILL.md` |
| "design my product", "product cover" | `../design-advisor/SKILL.md` |
| "launch my product", "create launch posts" | `../launch-kit/SKILL.md` |

## How It Works

If the user says a specific trigger, go directly to that skill. If they say something broad like "build a digital product," start with idea-finder and move through the pipeline step by step. Always confirm before advancing to the next stage.

## References

All frameworks and templates live in `references/`:
- `ltl-frameworks.md` — 8-question framework, 1+1+1 naming, 10 sections template
- `pricing-guide.md` — pricing tiers, psychology, platform fees
- `launch-checklist.md` — pre-launch, launch day, post-launch actions
- `platform-guides.md` — Gumroad, Stripe, Lemon Squeezy setup
