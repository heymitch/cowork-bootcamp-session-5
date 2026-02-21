---
name: idea-finder
description: Find digital product ideas by scanning existing content for demand signals. Triggers — "find product ideas", "what should I build", "product idea scan"
user-invocable: true
---

# Idea Finder

## Process

### Step 1: Scan for Content History

Check these sources (use whatever is connected):
- Notion pages tagged with content, drafts, or posts
- Local files in the user's workspace
- Analytics or engagement data the user can share

### Step 2: Rank by Demand Signals

Score topics by signal strength (strongest first):
1. **Comments and replies** — people asking questions means they would pay for answers
2. **Likes and engagement** — interest exists but weaker than comments
3. **Recurring topic** — the user keeps writing about this (passion + expertise signal)

### Step 3: Present 3 Candidates

For each candidate show:
- **Topic** — one sentence
- **Evidence** — what signals you found (quote specific comments or numbers)
- **Angle** — how to turn it into a product (guide, template, playbook)
- **Working title** — one title to make it feel real

### Step 4: No Content History Fallback

If the user has no content to scan, ask these 3 questions one at a time:
1. What do people keep asking you about? (at work, in DMs, at events)
2. What do you know how to do that most people struggle with?
3. What did you figure out the hard way that you wish someone told you earlier?

Use their answers to generate 3 candidates using the same format.

### Step 5: Pick and Move On

Ask the user to pick one or suggest their own. Once chosen, recommend running topic-validator to test demand before building.

## Rules
- Never suggest ideas without evidence or user input.
- Always present exactly 3 candidates.
- Keep each candidate to 3-4 lines. No essays.
- If scanning sources, summarize findings. Do not dump raw data.
- End by recommending topic-validator as the next step.
