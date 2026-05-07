# DiscoveryTreeSkill

Agent skill for discovery tree task management

## STARTER_CHARACTER

This skill defines a `STARTER_CHARACTER = [emoji]` at the top. This is a visual indicator that your AI tool has loaded the skill and is following its instructions.

To activate this, add the following to your global AGENTS.md or CLAUDE.md:
```
Always start replies with STARTER_SYMBOL
Default STARTER_SYMBOL: 🍀
```

Pick any default emoji you like — it confirms your tool is reading your ground rules. When a skill activates, its emoji replaces the original starter character until it’s done using that skill.

Without this line in your global AGENTS.md or CLAUDE.md, the `STARTER_CHARACTER` line might have unpredictable behavior.
