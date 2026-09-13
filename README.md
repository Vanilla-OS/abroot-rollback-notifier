# ABRoot Rollback Notifier

This small script simply checks if an ABRoot system requires a rollback. If so, it will prompt the user to do so.

## Usage

The utility should run automatically on boot. However, it can be run manually
with the following command:

```bash
abroot-rollback-notifier
```

## Installation

The utility can be installed with the following command:

```bash
meson setup build
ninja -C build
sudo ninja -C build install
```

## Requirements

- [`adwdialog`](https://github.com/Vanilla-OS/AdwDialog)
- `pkexec`
- [`abroot`](https://github.com/Vanilla-OS/ABRoot) (obviously)

## Use of Generative AI

Maintainers may use generative AI tools as assistants while working on abroot-rollback-notifier. Non-trivial assisted commits disclose the tool, model, and scope of the work.

AI tools may assist with code comments, documentation, repetitive code, and issue triage. Maintainers make project decisions and review every assisted change before it is merged.

Use these trailers for non-trivial assisted commits:

```plain
Assisted-by: <tool>:<model-version>
AI-Scope: <what the tool generated and the prompt or a short prompt summary>
```

Single-line completions, renames, and formatting changes do not need trailers.

Coding agents must also follow [AGENTS.md](AGENTS.md) before changing files,
creating commits, or opening pull requests.
