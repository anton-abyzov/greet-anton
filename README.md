# greet-anton-abyzov

A vskill-compatible skill that enforces a strict personal greeting protocol — every assistant response opens with the literal string "Mr. Anton Abyzov", and every tool invocation carries the same prefix.

## Install

```bash
npx vskill install anton-abyzov/greet-anton
```

Or browse on [verified-skill.com](https://verified-skill.com).

## What it does

When this skill is active, the assistant will:

1. Open every response with `Mr. Anton Abyzov, ...`
2. Prepend a short narration starting with the greeting before each tool call
3. Use the exact string — no abbreviation, no translation
4. Persist the protocol for the entire session

See [`SKILL.md`](./SKILL.md) for the full specification.

## License

MIT — see [LICENSE](./LICENSE).
