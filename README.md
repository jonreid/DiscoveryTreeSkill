# DiscoveryTreeSkill

This is a coding agent skill for Discovery Tree task management.

Discovery Trees are a lightweight way to visualize work and track it, creating an “information radiator” of shared context.

Originally created as physical sticky notes on a whiteboard, they also work well on virtual whiteboards. But neither physical sticky notes nor virtual ones work well with coding agents.

This skill represents the tree as a Mermaid diagram. I decided to this diagram in a Markdown file. I then open the file in [Typora](https://typora.io), a Markdown editor that also renders Mermaid. You may have a different tool to render Mermaid diagrams locally, such as a VSCode plugin or JetBrains plugin.

## Learn More Here

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
