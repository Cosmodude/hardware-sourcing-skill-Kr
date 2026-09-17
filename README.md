# Hardware Sourcing Skill — Korea First

An AI assistant skill for designing hardware around parts you can actually obtain. It checks existing inventory, specifications, price and delivery before committing to a component or CAD interface.

**Search order:** Korea → China → Japan → HyperFlight UK or global search. Searches use Korean, Chinese and Japanese for the respective markets.

This repository contains instructions for an AI assistant, not a standalone executable script. The shared rules live in [SKILL.md](SKILL.md).

## Install and use

### Codex

Clone into your skills directory (use `$CODEX_HOME/skills` instead if you configured a custom Codex home):

```sh
git clone https://github.com/Cosmodude/hardware-sourcing-skill-Kr.git ~/.codex/skills/hardware-sourcing-design
```

Start a new session and mention `$hardware-sourcing-design` in your request.

### Claude Code

```sh
git clone https://github.com/Cosmodude/hardware-sourcing-skill-Kr.git ~/.claude/skills/hardware-sourcing-design
```

Invoke `/hardware-sourcing-design`. See [Claude setup](agents/claude.md).

### Grok Bot

Provide [SKILL.md](SKILL.md) to your Bot and ask it to save the instructions as a skill named `hardware-sourcing-design`. See [Grok setup](agents/grok.md) for the setup prompt. Updates must be imported into Grok again.

If the installation directory already exists, update that installation instead of cloning over it. For a Git installation, run `git pull --ff-only` inside its repository.

## Example request

> Use hardware-sourcing-design to find a return spring for my prototype. I need one sample and six later, delivered to Jeju within a week. Check my existing parts first, search in the required regional order, and suggest design changes if a readily available part is a better fit. Include exact options, total cost, delivery evidence and any unresolved compatibility checks.

Give the assistant your location, quantities, budget, deadline, owned parts and essential technical constraints. It needs web access to verify current availability. Recommendations do not authorize purchases, supplier messages or fabrication.
