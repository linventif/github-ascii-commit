# OVH Commit Map

Bun/TypeScript preview for writing text into a GitHub-style `7 x 52` commit
calendar.

```sh
bun install
bun run dev
```

Open the local URL printed by Bun. The preview defaults to:

- text: `test test`
- date range: `19/06` to `31/08`
- grid: 7 weekdays by 52 weeks

Available controls:

- text content
- contribution intensity
- font style
- letter spacing
- max text size
- text thickness
- fill density
- auto shrink toggle; disable it to let text overflow instead of being compressed
- pixel font mode for cleaner 7-row ASCII letters such as `OVH`
