# Enterprise Architecture Skill

A portable AI agent skill for enterprise architecture work. It uses the open
`SKILL.md` format so it can be shared across agentic development tools rather
than depending on one vendor's prompt or configuration format.

## Use the skill

The skill definition is [`SKILL.md`](SKILL.md). Install or link this repository
as a skill directory in the location recognized by your agent:

- Claude Code: `.claude/skills/enterprise-architecture/`
- Codex: `.agents/skills/enterprise-architecture/`
- Cursor: `.cursor/skills/enterprise-architecture/`
- Hermes and other agents: use the agent's configured skills directory and
  follow its instructions for discovering `SKILL.md` files.

For repository-local use, the directory should contain `SKILL.md` at the paths
shown above. For user-wide use, place it in the equivalent user-level skills
directory documented by the agent. Restart or reload the agent if it does not
discover the skill immediately.

## Scope

The skill helps agents reason about business and technology architecture,
evaluate options and trade-offs, and communicate recommendations. It is
tool-agnostic: it does not require a particular cloud provider, modeling
notation, repository structure, or architecture framework.
