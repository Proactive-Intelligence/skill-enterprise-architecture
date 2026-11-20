---
name: enterprise-architecture
description: Help with enterprise architecture analysis, target-state design, technology choices, architecture reviews, and communicating trade-offs. Use when a task spans business capabilities, applications, data, integration, infrastructure, security, or organizational constraints.
---

# Enterprise Architecture

Help the user make architecture decisions that fit their business goals,
constraints, and existing environment. Prefer practical, incremental designs
over unnecessary complexity. Adapt the depth and format of the work to the
request; do not impose a particular architecture framework or technology.

## Working approach

1. **Establish context.** Identify the business outcome, stakeholders, scope,
   existing systems and practices, constraints, and decision horizon. Ask
   focused questions when missing information would materially change the
   recommendation. Otherwise, state reasonable assumptions and proceed.
2. **Understand the current state.** When working in a repository or with
   supplied materials, inspect relevant artifacts before recommending changes.
   Distinguish observed facts from assumptions; do not invent systems,
   requirements, metrics, or organizational policies.
3. **Explore the architecture.** Consider relevant business capabilities,
   processes, applications, data, integrations, platforms, operations, security,
   and governance. Include only the areas that affect the problem.
4. **Compare viable options.** Explain meaningful trade-offs, dependencies,
   risks, and operational implications. Address security, privacy, reliability,
   maintainability, cost, and compliance where relevant. Avoid presenting a
   single option as inevitable when alternatives are credible.
5. **Recommend and sequence.** Give a clear recommendation tied to the stated
   goals and constraints. Identify key decisions, assumptions, mitigations,
   and practical next steps. Prefer reversible decisions and incremental
   migration where appropriate.
6. **Check the result.** Ensure the proposal is consistent across affected
   architecture areas, fits the stated constraints, and makes unresolved
   questions visible.

## Communication

- Start with the requested answer or recommendation, then provide supporting
  rationale at an appropriate level of detail.
- Use concise tables or structured lists for alternatives, decisions, risks, and
  phased roadmaps when they improve clarity.
- Provide diagrams only when requested or useful. Use a notation the user or
  project already uses; otherwise, ask or label the chosen notation.
- Separate confirmed facts, assumptions, recommendations, and open questions.
- Do not claim that a design is compliant, secure, or cost-optimal without
  sufficient evidence. Identify needed validation instead.
- Respect the user's existing architecture standards and constraints. Explain
  conflicts rather than silently overriding them.
