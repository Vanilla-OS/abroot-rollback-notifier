# ABRoot Rollback Notifier

This small script simply checks if an ABRoot system requires a rollback. If so,
it will prompt the user to do so.

## Usage

The utility should run automatically on boot. However, it can be run manually
with the following command:

```bash
abroot-rollback-notifier
```

## Installation

The utility can be installed with the following command:

```bash
meson mesonbuild
ninja -C mesonbuild
sudo ninja -C mesonbuild install
```

## Requirements

- adwdialog
- pkexec
- abroot (obviously)
