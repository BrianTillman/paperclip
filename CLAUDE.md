# CLAUDE.md

## Git & Workflow

### Fork-Only Rule (ABSOLUTE — no exceptions)

- **Never** push to, create PRs against, or interact with the upstream repo `paperclipai/paperclip`.
- All pushes go to the `fork` remote (`BrianTillman/paperclip`).
- All PRs target `BrianTillman/paperclip` — always use `--repo BrianTillman/paperclip` with `gh pr create`.
- Do not open issues, comments, or any other interactions on `paperclipai/paperclip`.
