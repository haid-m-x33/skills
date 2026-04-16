# Skills

This repository contains installable agent skills for the `npx skills` ecosystem.

## Available Skills

### `explain-in-depth`

A general-purpose explanation skill with a cybersecurity-first bias.

It is designed to explain terms, concepts, technologies, and topics in depth using two required sections in this exact order:

1. `Plain Understanding`
2. `Root Understanding`

For cybersecurity topics, it prefers authoritative sources such as CompTIA, NIST, NVD, MITRE, OWASP, and CISA. Wikipedia may be used as a supporting source, but not as the main source when stronger sources are available.

## Install

Install from GitHub:

```bash
npx skills add haid-m-x33/skills --skill explain-in-depth
```

List skills in this repository:

```bash
npx skills add haid-m-x33/skills --list
```

Install from a local checkout:

```bash
npx skills add . --skill explain-in-depth
```

From your home directory in PowerShell, use:

```powershell
npx skills add "$HOME\projects\skills" --skill explain-in-depth
```
