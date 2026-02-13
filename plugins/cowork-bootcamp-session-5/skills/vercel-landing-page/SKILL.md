---
name: vercel-landing-page
description: Build and deploy a landing page to Vercel from a description, Notion content, or product brief. Say "Build me a landing page for [product]" or "Deploy a sales page".
---

# Vercel Landing Page

Build a working landing page and deploy it live to the internet — from a description, product brief, or Notion content.

## How to Run
- "Build me a landing page for [product/offer]"
- "Deploy a sales page for my bootcamp"
- "Turn this Notion page into a live landing page"

---

## Preflight Check (Run Every Time)

Run through this silently. Only speak up if something is missing.

### 1. Does config.md exist?
Read `config.md` from the project root.
- **If missing:** Stop. Say: "I need to know about you and your business first — especially what you sell and who you serve. Say **'Run my business blueprint'** — it takes 5 minutes."
- **If exists:** Continue. Load business context.

### 2. Are Vercel tools available?
Check your available tools for Vercel tools (deploy, list projects, etc.).
- **If not found:** Stop. Say: "I need Vercel connected to deploy your page live. Here's the quick setup:\n\n1. Create a free account at [vercel.com](https://vercel.com)\n2. In your Cowork Settings, go to Integrations and connect Vercel\n\nOnce that's done, say 'Build me a landing page' again. Or if you just want me to generate the page code without deploying, say 'Build a landing page but don't deploy it.'"
- **If found:** Continue. If config.md has Vercel unchecked, update it.

### 3. Is voice training complete? (Optional)
Check config.md for `- [x] Voice Training completed`.
- **If checked:** Use voice profile for page copy.
- **If unchecked:** Use clean, persuasive copy. Don't block.

### 4. Is Notion connected? (Optional)
Check for Notion tools.
- **If found:** Can pull product content from Notion pages.
- **If not found:** Ask user to provide content directly.

### 5. All clear — proceed silently.

---

## What the Agent Does

Step 1: Gather the content
- Read description, product brief, or Notion page (if connected)
- If nothing provided, ask: What are you selling? Who is it for? What's the price? What's the main benefit?

Step 2: Write the landing page copy
- Hero section: headline + subheadline + CTA button
- Problem section: what pain does your audience have?
- Solution section: what your product does about it
- Features/benefits: 3-5 key points
- Social proof section: placeholder for testimonials (or real ones if provided)
- Pricing section: what it costs + what's included
- Final CTA: closing push + button
- Written in user's voice if trained, persuasive professional tone if not

Step 3: Generate the code
- Clean HTML/CSS or a simple Next.js page
- Mobile-responsive, fast-loading

Step 4: Show preview before deploying
- Review copy, layout, and design
- Make changes if needed

Step 5: Deploy to Vercel
- Push to Vercel, get a live URL back
- Page is live in under a minute

## Tips
- Better input = better page. A clear product brief produces a stronger page than "make me a landing page."
- You can iterate: "Change the headline" or "Add a testimonial section" and redeploy.
- Free Vercel accounts give you unlimited deploys with a `.vercel.app` domain.

## Rules
- Always show the full page preview before deploying
- Never deploy without explicit approval
- Write copy using voice profile and human writing rules
- If critical information is missing (price, offer, audience), ask — don't make it up
- Include placeholder text for sections the user hasn't provided (marked clearly as [PLACEHOLDER])
