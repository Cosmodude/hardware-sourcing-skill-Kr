# Grok Bot setup

Use the shared [SKILL.md](../SKILL.md) as the skill instructions. This file is a setup prompt, not an automatically loaded Grok configuration; the referenced documentation does not specify an equivalent to agents/openai.yaml.

Provide SKILL.md to Grok Bot and ask:

> Create a skill named hardware-sourcing-design using the attached SKILL.md as its instructions. Preserve its sourcing order: Korea → China → Japan → HyperFlight UK or broader global search. Preserve native-language searches, compatibility checks, availability verification and the requirement for authorization before sending enquiries or placing orders. Do not create a routine or schedule.

After creation, confirm the skill is enabled for the intended Bot under Settings → Plugins → Yours, and reference the saved skill from the `/` menu.

Suggested task prompt:

> Use hardware-sourcing-design to select obtainable hardware and design around verified specifications. Check my existing inventory first, verify shipping to my location, and report unresolved specifications before recommending a purchase or print handoff.

When SKILL.md changes, update the saved Grok skill from that file; this repository does not automatically sync it.

Source: [Grok Bot skills documentation](https://docs.x.ai/grok-bot/skills-routines-and-automations).
