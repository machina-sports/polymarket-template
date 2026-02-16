# polymarket-template

Machina templates for syncing sports prediction market data from Polymarket.

## Skills

| Skill | Description |
|-------|-------------|
| `polymarket-sync-events` | Sync sports events with embedded markets |
| `polymarket-sync-series` | Sync series (leagues/competitions) |
| `polymarket-sync-markets` | Sync prediction markets with prices |

## Install

```bash
# All skills
npx skills add https://github.com/machina-sports/polymarket-template

# Individual skills
npx skills add https://github.com/machina-sports/polymarket-template --skill polymarket-sync-events
npx skills add https://github.com/machina-sports/polymarket-template --skill polymarket-sync-series
npx skills add https://github.com/machina-sports/polymarket-template --skill polymarket-sync-markets
```

## Dependencies

- **polymarket** connector (no auth required)
- **machina-ai** connector (for embeddings) — requires `$TEMP_CONTEXT_VARIABLE_SDK_OPENAI_API_KEY`
