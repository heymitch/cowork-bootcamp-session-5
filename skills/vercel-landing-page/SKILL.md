---
name: vercel-landing-page
description: Build and deploy a landing page to Vercel from a description, Notion content, or product brief. Say "Build me a landing page for [product]" or "Deploy a sales page".
user-invocable: true
---

# Vercel Landing Page

## Preflight (Run Silently)

1. **config.md** — Read from project root. If missing, stop: "Say **'Run my business blueprint'** first — it takes 5 minutes."
2. **Vercel tools** — Check for Vercel MCP tools. If not found, tell the user to connect Vercel in Cowork Settings, or offer to generate the code without deploying.
3. **Voice training** — If config.md shows voice training complete, use voice profile for copy. Otherwise use clean persuasive tone.
4. **Notion** — If connected, can pull product content from Notion pages.

## Process

### Step 1: Gather Content

From description, product brief, or Notion page. If nothing provided, ask: What are you selling? Who is it for? What's the price? What's the main benefit?

### Step 2: Write Landing Page Copy

- Hero: headline + subheadline + CTA button
- Problem: what pain does your audience have?
- Solution: what your product does about it
- Features/benefits: 3-5 key points
- Social proof: placeholder for testimonials (or real ones if provided)
- Pricing: what it costs + what's included
- Final CTA: closing push + button

### Step 3: Generate Code

Use the `../frontend-design/SKILL.md` guidelines for visual quality. Clean HTML/CSS or Next.js page. Mobile-responsive, fast-loading.

### Step 4: Preview

Show full page preview before deploying. Make changes if needed.

### Step 5: Deploy

Push to Vercel on approval. Page is live in under a minute.

## Rules

- Always show the full page preview before deploying
- Never deploy without explicit approval
- If critical information is missing (price, offer, audience), ask — don't make it up
- Include placeholder text for sections the user hasn't provided (marked clearly as [PLACEHOLDER])
