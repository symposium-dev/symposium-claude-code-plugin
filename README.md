# Symposium Claude Code Plugin

[Symposium][] plugin for Claude Code. Installing this plugin will instruct your agent to look for applicable skills for the crates you are using. See the [homepage][] for installation instructions or visit [symposium.dev][] for full documentation.

## Quick install

**Plugin:**

```bash
claude plugin marketplace add symposium-dev/symposium-claude-code-plugin
claude plugin install symposium@symposium
```

**Standalone skill:** [Download the skill zip][skill-zip] and unzip it into the appropriate skills directory for your agent (e.g., `.claude/skills/` for Claude Code).

## Note

Using this plugin and skill will download the pre-compiled Symposium binary from the published artifacts of the [Symposium repository][repo].

[Symposium]: https://symposium.dev
[symposium.dev]: https://symposium.dev
[homepage]: https://symposium-dev.github.io/symposium-claude-code-plugin/
[skill-zip]: https://symposium-dev.github.io/symposium-claude-code-plugin/symposium-skill.zip
[repo]: https://github.com/symposium-dev/symposium
