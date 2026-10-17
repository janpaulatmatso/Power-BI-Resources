# Contributing

Thanks for helping to improve this list!

## Adding a resource

1. Add it to the most fitting section in [README.md](README.md). If nothing fits, propose a new section in your pull request.
2. Use this format:

   ```markdown
   - [Name](https://link) 🆓 - Short description that ends with a period.
   ```

3. Mark the pricing model where it applies: 🆓 free, 💰 paid, 🔀 freemium.
4. Add 🇳🇱 or 🇧🇪 for Dutch or Belgian creators and events, and list them under [Dutch & Belgian Community](README.md#dutch--belgian-community) as well.
5. Use ⭐ sparingly, only for the best starting points in a section.

## Guidelines

- The resource must be about Power BI (or Fabric, as far as it is relevant to Power BI users).
- The resource must be actively maintained, or still be valuable as a reference.
- Link to the original source, not to a reseller, aggregator or affiliate link.
- Keep descriptions short and factual. No marketing language.
- Use HTTPS links without a locale, such as `learn.microsoft.com/power-bi/...` instead of `learn.microsoft.com/en-us/power-bi/...`.
- One resource per pull request is easiest to review.

## Dead links

A [GitHub Action](.github/workflows/links.yml) checks all links every week. You can run the check locally with [lychee](https://github.com/lycheeverse/lychee):

```bash
lychee README.md
```
