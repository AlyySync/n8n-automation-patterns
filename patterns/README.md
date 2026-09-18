# Pattern notes

`webhook-intake.json` is intentionally small: respond quickly, validate required fields, and pass a normalized event to the next workflow. Add an idempotency lookup on `event_id` before any external write.
