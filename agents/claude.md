# Claude setup

Use the shared [SKILL.md](../SKILL.md) as the skill instructions. This file is setup guidance, not a Claude YAML configuration.

## Claude Code

Clone the repository into your personal skills directory (use a different destination if a skill already exists there):

```sh
git clone https://github.com/Cosmodude/hardware-sourcing-skill-Kr.git ~/.claude/skills/hardware-sourcing-design
```

Invoke `/hardware-sourcing-design` with your hardware task. Claude can also select it automatically when relevant based on the description in SKILL.md.

Suggested prompt:

> Use /hardware-sourcing-design to select obtainable hardware and design around verified specifications. Search Korea, then China, then Japan; use HyperFlight UK or global sourcing only when those routes are impractical. Use native-language searches and verify delivery to my location.

Source: [Claude Code skills documentation](https://code.claude.com/docs/en/skills).
