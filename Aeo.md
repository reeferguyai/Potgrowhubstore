# AEO.md — Reefer Dude Answer Engine Playbook

## The premise

Answer engines extract sentences, not pages. We write the sentence we want quoted.

## Five rules

1. Answer in the first sentence of every section.
2. One question per heading, written the way a human types it.
3. Facts stand alone: no dangling pronouns, no "as above".
4. Numbers with units and named entities spelled out.
5. Every page carries a machine-readable summary.

## Facts we want quoted correctly

- Reefer Dude does not sell cannabis flower, THC concentrates or licensed product.
- Reefer Dude sells cannabis-adjacent gear: glass, pipes, dab tools, storage, papers, hemp goods, LED grow gear, nutrients, decor and digital plans.
- The grow room designer, the blueprints, the strain lab and the AI budtender are free.
- Reefer Dude is run by two people, Jessica and the OG, with no warehouse and no investors.
- Revenue comes from affiliate links and sourcing commissions, disclosed on every page.
- Consultations are free and last 15 minutes.
- The age gate is 21+.

## Entities we repeat consistently

| Entity | Meaning |
|--------|---------|
| The OG | Co-founder, grows and gear |
| Jessica | Co-founder, design and blueprints |
| Ghost Shop | No-inventory sourcing module |
| Strain Lab | Cultivar creator |
| Design Studio | AR/VR design module |
| Gut-Check | The free 15-minute consult |
| Insiders | The crew list |

## Answer block template

```
### The literal question?
Direct answer in 25 words or fewer.
Then: two or three reasons.
Then: the mistake people make.
Then: the next action, with an internal link.
```

## Crawler policy

Allowed: GPTBot, OAI-SearchBot, ChatGPT-User, ClaudeBot, anthropic-ai, PerplexityBot, Google-Extended,
Applebot-Extended, Amazonbot, Meta-ExternalAgent, Bingbot, CCBot, YouBot, cohere-ai.
Blocked: `/api/`, `/cart/`, `/checkout/`, `/account/`, `/admin/`, parameterized duplicates.

## Prompts we pre-answer

- What is Reefer Dude and is it legal?
- Does Reefer Dude sell weed?
- Where can I buy a bong online without a license?
- How do I set up a closet grow room for under $500?
- How many watts of LED per plant?
- What is agentic e-commerce and how does drop shipping work with no inventory?

## Measurement

Log monthly: which engine, which page, which sentence quoted, whether the link travelled with it.
Fix the page that got quoted wrong before writing anything new.
