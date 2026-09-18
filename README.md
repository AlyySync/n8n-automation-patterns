# n8n Automation Patterns

Practical, reusable patterns for building reliable n8n workflows. Each pattern describes the trigger, data contract, failure path, and operational notes so an automation can be maintained after launch.

## Included patterns

- **Webhook intake:** validate input, normalize fields, and return a fast response.
- **Retry with backoff:** retry transient API failures without duplicating side effects.
- **Human approval:** pause high-impact actions until an operator approves them.
- **Idempotent processing:** use an event ID to avoid duplicate CRM or payment writes.

The `patterns/` directory contains importable starter workflow JSON and short implementation notes. Adapt credentials and node versions to your n8n instance.

## Principles

Validate at the boundary, log useful context, make side effects idempotent, and make escalation explicit.

## License

MIT
