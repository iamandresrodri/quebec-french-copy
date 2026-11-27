# quebec-french-copy

A Claude skill for marketing copy in **Quebec French**: the kind a Montrealer reads without noticing it started in English, and without it sounding like it came from Paris.

Most AI translation gives you France French with English sentence structure. In Quebec that reads as "translated", and people notice. This skill adapts instead of translating.

## What it handles

- **Tu vs vous**, picked by audience and kept consistent
- **Quebec terms**: courriel, magasinage, fin de semaine, balado
- **Business anglicisms** that slip into Quebec writing: "appliquer sur", "céduler", "adresser un problème"
- **Typography**: spaces before `: ; ! ?`, « guillemets », prices as 49,99 $
- **Length**: French runs longer, so it offers short versions for buttons, headlines and ads

## Install

**Claude Code:**

```bash
git clone https://github.com/iamandresrodri/quebec-french-copy ~/.claude/skills/quebec-french-copy
```

**Claude.ai:** download this repo as a zip and upload it under Settings > Capabilities > Skills.

Then ask: *"Make a Quebec French version of this landing page. B2B audience."*

## Why I built it

I'm a trilingual product marketer in Montreal. I write a lot of French copy for Quebec companies, and I kept fixing the same AI mistakes by hand. So I wrote them down once.

Suggestions welcome. If you spot a term that's wrong or missing, open an issue.

## License

MIT.
