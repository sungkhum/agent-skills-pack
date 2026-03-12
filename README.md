# Agent Skills Pack

Standalone AI skills adapted from selected BMAD workflows, rewritten to run independently.

## Why This Repo Exists

I found substantial value in BMAD, particularly in its skills and tooling, but the full methodology was more process-heavy than my use case required.

To simplify day-to-day use, I isolated the components I found most useful and repackaged them as standalone skills in this repository for easier access and installation.

## Included Skills

- `code-review`
- `copy-review`
- `create-ux-design`
- `domain-research`
- `edge-case-hunter`
- `market-research`
- `tech-writer`
- `ux-designer`

## Install

Recommended interactive install:

```bash
npx -y skills add https://github.com/sungkhum/agent-skills-pack
```

This will prompt you to choose:
- which skills to install
- which agent(s) to install to (Codex, Claude, etc.)

Install one specific skill (still interactive for agent selection):

```bash
npx -y skills add https://github.com/sungkhum/agent-skills-pack --skill code-review
```

List available skills:

```bash
npx -y skills add https://github.com/sungkhum/agent-skills-pack --list
```

Optional non-interactive install:

```bash
npx -y skills add https://github.com/sungkhum/agent-skills-pack --agent codex --yes --copy
```

- `--yes` skips confirmation prompts.
- `--copy` copies files into your agent directory instead of symlinking them.
- If you omit `--copy`, the CLI uses symlinks.

After install, restart Codex so newly installed skills are picked up.

## Attribution

These skills are adapted from:
- Source repository: https://github.com/bmad-code-org/BMAD-METHOD
- Organization: BMad Code, LLC

Full credit for the original methodology, workflow design, and source materials belongs to the BMAD project and contributors.

## Licensing

BMAD-METHOD is licensed under MIT:
- https://github.com/bmad-code-org/BMAD-METHOD/blob/main/LICENSE

This repository contains derived/adapted materials from that project. Keep original copyright and license notices when redistributing substantial portions.

## Trademark Notice

BMAD names and branding are trademarks of BMad Code, LLC and are not granted by the MIT software license:
- https://github.com/bmad-code-org/BMAD-METHOD/blob/main/TRADEMARK.md

This repository is an independent adaptation and is not an official BMAD product or endorsement.
