# Standalone Skills Extracted From BMAD-METHOD

This repository contains standalone AI skills adapted from selected workflows/tasks in the BMAD ecosystem, with neutral skill names for independent use.

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

Interactive install (recommended):

```bash
npx -y skills add https://github.com/sungkhum/agent-skills-pack
```

This mode prompts you to:
- choose which skills to install
- choose which agent(s) to install to (Codex, Claude, etc.)

Install one specific skill (still interactive for agent selection):

```bash
npx -y skills add https://github.com/sungkhum/agent-skills-pack --skill code-review
```

List available skills before installing:

```bash
npx -y skills add https://github.com/sungkhum/agent-skills-pack --list
```

Non-interactive install (optional):

```bash
npx -y skills add https://github.com/sungkhum/agent-skills-pack --agent codex --yes --copy
```

- `--yes` skips confirmation prompts.
- `--copy` copies files into your agent directory instead of symlinking them.
- If you omit `--copy`, the CLI symlinks by default.

After install, restart Codex so newly installed skills are picked up.

## Attribution

These skills are adapted from the BMAD project:

- Source repository: https://github.com/bmad-code-org/BMAD-METHOD
- Organization: BMad Code, LLC

Full credit for the original methodology, workflow design, and source materials belongs to the BMAD project and contributors.

## Licensing

The BMAD-METHOD repository is licensed under MIT (software license):

- BMAD LICENSE: https://github.com/bmad-code-org/BMAD-METHOD/blob/main/LICENSE

This repository contains derived/adapted materials from that project. Keep the original copyright and license notices when redistributing substantial portions.

## Trademark Notice

BMAD names and branding are trademarks of BMad Code, LLC and are not granted by the MIT software license.

- BMAD trademark policy: https://github.com/bmad-code-org/BMAD-METHOD/blob/main/TRADEMARK.md

This repository is an independent adaptation and is not an official BMAD product or endorsement.
