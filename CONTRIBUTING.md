# Contributing

Contributions are welcome. Before submitting a pull request, please review these guidelines.

## Entry requirements

Each entry must:

- Link to a **live public product** with a working website. No roadmap items, no defunct cards, no concepts.
- Be a **crypto-backed payment card** — Visa, Mastercard, or equivalent network. Pure fiat prepaid cards do not belong here.
- Have a **one-line description** describing the key differentiator (custody model, cashback, fees, or region).
- Link to the canonical detail page at `sweepbase.net/cards/{slug}` where full fee data is maintained.

## Format

```markdown
- [Card Name](https://sweepbase.net/cards/card-slug) - Short description ending in a period.
```

Rules:

- Card name in title case.
- Description is one sentence, ends with a period.
- No marketing adjectives ("best", "leading", "revolutionary").
- Alphabetical order within each section.
- Do not add emojis or badges to individual entries.

## Adding a new card

1. Fork the repo.
2. Verify the card is listed at [sweepbase.net/cards](https://sweepbase.net/cards). If not, open an issue at [sweepbase/data](https://github.com/mbtrilla/crypto-card-aggregator) first.
3. Add the card to the **most specific region section** it serves. Multi-region cards can appear in multiple sections.
4. If the card has a unique property (self-custody, yield, stablecoin-first), also add it to that Use Case section.
5. Run `awesome-lint` locally: `npx awesome-lint`.
6. Submit a PR with a description explaining why the card should be included.

## Removing a card

If a card is discontinued, bankrupt, or region-locked beyond usefulness, open an issue citing the source (announcement, news article) and the PR removing it.

## Pull request checklist

- [ ] Card is live and publicly available.
- [ ] Entry follows the format above.
- [ ] Placed in the correct section(s).
- [ ] `awesome-lint` passes.
- [ ] PR description explains the addition / removal.

## Code of conduct

Be respectful. Discussion of product quality is fine — personal attacks, spam, and undisclosed affiliate promotion are not.
