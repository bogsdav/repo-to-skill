# Repo to Skill

A Claude skill. Use when the user shares a GitHub repo link and wants it turned into a Claude skill they can save and reuse.

## What's inside

- `repo-to-skill/SKILL.md`

## Install

### Claude app (claude.ai, desktop, mobile)

1. Download this repo as a ZIP (**Code > Download ZIP**) and unzip it.
2. Zip the `repo-to-skill` folder on its own, so the ZIP contains `repo-to-skill/SKILL.md`.
3. In Claude's settings, open the Skills section, upload that ZIP, and turn the skill on.

### Claude Code

```bash
git clone https://github.com/bogsdav/repo-to-skill.git
mkdir -p ~/.claude/skills
cp -r repo-to-skill/repo-to-skill ~/.claude/skills/
```

Restart Claude Code. The skill loads automatically when a request matches its description.

## Try it

- "Turn https://github.com/owner/repo into a Claude skill."
- "Is this repo a good fit for a skill? Vet it and package it."

## License

MIT. See [LICENSE](LICENSE).
