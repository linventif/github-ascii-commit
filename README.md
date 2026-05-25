# OVH Commit Map

Bun/TypeScript preview for writing text into a GitHub-style `7 x 52` commit
calendar.

```sh
bun install
bun run dev
```

Open the local URL printed by Bun. The preview defaults to:

- text: `OVH`
- date range: today minus 6 months to today plus 6 months
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
- create project button that opens the GitHub fork page
- copy config button for pasting the generated design into `config.txt`
- paint tools: pencil, eraser, and clear for live manual edits
