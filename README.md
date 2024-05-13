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
