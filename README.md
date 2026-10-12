# skills-wrap

A Claude Code plugin marketplace that wraps upstream skill repos which ship a
bare `SKILL.md` (no `.claude-plugin/` manifest), so they can be installed and
auto-updated like any plugin. Each entry points at the upstream GitHub repo with
`strict: false`; no skill content is copied here.

| Plugin | Upstream |
|---|---|
| `anatomy` | [wheresryan22/anatomy](https://github.com/wheresryan22/anatomy) |

```bash
claude plugin marketplace add borisbosiak/skills-wrap
claude plugin install anatomy@skills-wrap
```
