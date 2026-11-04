# agent-instructions

A portable baseline of instructions for coding agents. It is meant to sit under a project's own instructions, which take precedence over it.

- [agent-starter-instructions.md](agent-starter-instructions.md): the instructions.

## Loading it

How you load it depends on the host. If you use it as an `.instructions.md` file, add this frontmatter at the top so it applies to every file:

```yaml
---
applyTo: '**'
---
```

## First use

Before adopting it in a new workspace, ask the agent to compare it with what is already there. For example:

> Read https://raw.githubusercontent.com/Likwidt/agent-instructions/main/agent-starter-instructions.md and compare it with the instructions and procedures already in effect in this workspace. Report what overlaps, what would change your behaviour, and what conflicts (and which side would win). Don't edit anything.

## License

[MIT](LICENSE)
