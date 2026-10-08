# Facebook Ads Live Build

Prompts and Claude skills from Gareth Winter's Facebook Ads Live Build session.

**Open the prompt page:** https://garethwinter-cpu.github.io/facebook-ads-live-build/

## What's here

- `index.html`: the prompt page. Type your brand once and every prompt fills in. Works with Claude or ChatGPT.
- `skills/`: four Claude skills that run the same build as a guided interview.

| Skill | What it does |
|---|---|
| `facebook-ads-brand-kit` | Purpose, values, position, audience, tone of voice, visual identity, proof and offer |
| `facebook-ads-insight` | Customer tensions, human needs (Life-Force 8), the 10 beliefs |
| `facebook-ads-static` | 20 hooks, feed ads, carousels, lead forms, follow-up email, Ads Manager test plan, reading results |
| `facebook-ads-video` | 15-second Reels scripts, funny versions, AI video shot prompts, hook tests |

## Install the skills in Claude

1. Download the four `.zip` files from `skills/`.
2. In Claude, open **Settings**, then **Capabilities**, and upload each zip under **Skills** (paid Claude plans).
3. Start a new chat and type: **start my brand kit**.

Each skill keeps a running **MY BRAND KIT** document and hands over to the next one.

## Notes

Facebook's placements, specs and ad policies change. Check Meta's Business Help Centre and Advertising Standards before you launch. Frameworks are credited to their authors inside each skill.
