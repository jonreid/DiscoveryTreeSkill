# DiscoveryTreeSkill

This is a coding agent skill for Discovery Tree task management.

Discovery Trees are a lightweight way to visualize work and track it. Learn more here:
- [Product Mapping and Discovery Trees](https://www.fastagile.io/method/product-mapping-and-discovery-trees) from FAST agile
- [Working with Discovery Trees](https://www.industriallogic.com/blog/discovery-trees/) by Steve Kuo

## STARTER_CHARACTER

This skill defines a `STARTER_CHARACTER = [emoji]` at the top. This is a visual indicator that your AI tool has loaded the skill and is following its instructions.

To activate this, add the following to your global AGENTS.md or CLAUDE.md:
```
Always start replies with STARTER_SYMBOL
Default STARTER_SYMBOL: 🍀
```

Pick any default emoji you like — it confirms your tool is reading your ground rules. When a skill activates, its emoji replaces the original starter character until it’s done using that skill.

Without this line in your global AGENTS.md or CLAUDE.md, the `STARTER_CHARACTER` line might have unpredictable behavior.
