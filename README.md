# Worlds

An open-source spatial workspace for people and their agents.

Connect your own setup, review an agent plan, choose a world, and work together inside it. The world is the workspace interface: rooms contain projects, characters represent actual people or agents, and objects open useful work.

**Status: design and implementation handoff. There is no runnable app or tested integration in this initial repository. Build and test locally first. No deployment has been authorized in this phase.**

## Start building

Select Claude Fable 5 in your Claude Code environment, open this repository, and paste [the full build prompt](prompts/FABLE-5-BUILD.txt). The prompt instructs Claude to implement, inspect, test, and document a local alpha in milestones.

1. Read [the product brief](docs/PRODUCT-BRIEF.md) and [workspace interaction specification](docs/WORKSPACE-UI.md).
2. Read [the design-system brief](docs/DESIGN-SYSTEM.md). Supply an authorized Glob checkout for its separate, read-only design-system audit.
3. Use the original generated [concept maps](assets/concepts/) for atmosphere and spatial composition. These are illustrations, not game assets or collision maps.
4. Start with the labelled sample rosters in [examples](examples/). Implement and verify a real source adapter separately.
5. Record evidence against [local acceptance checks](docs/LOCAL-ACCEPTANCE.md). Add actual installation and run instructions after there is working code.

## Product direction

- White, colourful, clean interface; playful worlds with much richer environments.
- Office, Café, Village, and Cyberpunk are themes, not fixed agent teams.
- Source → discovery → AgentPlan → WorldPlan → human review → validated build → workspace.
- Humans, connected agents, proposed agents, and ambient characters remain distinguishable.
- Useful work is reachable by clicking or a direct list; walking is optional.
- Open-source, self-hostable foundation; Nebula is the first intended source integration.

The initial alpha targets one polished local world, source-driven planning, useful work inspection, and two-client local presence. Additional worlds, full character production, and the larger design system follow in explicit milestones; they are not all promised within a 20–30-hour sprint.

## Documents

| Material | Purpose |
|---|---|
| [Fable 5 prompt](prompts/FABLE-5-BUILD.txt) | Complete implementation handoff |
| [Glob audit prompt](prompts/GLOB-DESIGN-SYSTEM-AUDIT.txt) | Reuse architecture and match depth without copying a brand |
| [Design system](docs/DESIGN-SYSTEM.md) | Identity, tokens, components, character/3D/motion pipeline, explorers |
| [Workspace UI](docs/WORKSPACE-UI.md) | Map navigation, inspector, plans, tasks, people, provenance |
| [Roadmap](docs/ROADMAP.md) | Local alpha, design expansion, later launch |
| [Acceptance](docs/LOCAL-ACCEPTANCE.md) | Checks that must actually pass |
| [Sources](docs/SOURCES.md) | Research links and verification limits |
| [Brand decisions](docs/BRAND-DECISIONS.md) | Working name and domain status |

## Independence and licensing

This is an independent project. Nebula is an intended integration, not a claim of endorsement, employment, or official product status. Gather, Grok Bot, Nebula, and Glob inform interaction/design research; their logos and proprietary assets are not bundled.

Original project code and documentation are offered under [MIT](LICENSE). Concept-art provenance and reuse terms are recorded separately in [ASSETS.md](ASSETS.md). Check permissions before importing any third-party or Glob materials. Personal creator strategy and private company material do not belong in this public repository.
