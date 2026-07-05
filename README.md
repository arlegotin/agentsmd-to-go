# agentsmd-to-go

Stop rewriting `AGENTS.md`.

A reliable default for the next repo where custom agent policy would be wasted time.

From your target repo:

```bash
curl -fsSLo AGENTS.md https://raw.githubusercontent.com/arlegotin/agentsmd-to-go/main/AGENTS.md
```

This writes `./AGENTS.md`. Merge first if one already exists.

For tools that want their own memory file:

```md
Read and follow ./AGENTS.md.
```

Keep pointers thin. One rulebook. Put repo-specific setup/commands/facts outside `AGENTS.md`.
