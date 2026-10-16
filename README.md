# AhaSend Homebrew tap

The [Homebrew](https://brew.sh) formula of the
[AhaSend CLI](https://github.com/AhaSend/ahasend-cli), the command-line
interface for [AhaSend](https://ahasend.com). It works on macOS and Linux,
on Intel and ARM.

## Install

```bash
brew install ahasend/tap/ahasend
```

Use the full name `ahasend/tap/ahasend`. Homebrew adds this tap and installs
`ahasend` with shell completion for bash, zsh and fish.

```bash
ahasend --version
```

## Upgrade and uninstall

```bash
# Upgrade
brew upgrade ahasend/tap/ahasend

# Uninstall
brew uninstall ahasend
brew untap ahasend/tap
```

## About this tap

Each AhaSend CLI release updates `Formula/ahasend.rb` here, so do not edit it
by hand. Report problems with the CLI or the formula in the
[CLI's issues](https://github.com/AhaSend/ahasend-cli/issues).

For other ways to install, and for how to use the CLI, see the
[AhaSend CLI documentation](https://ahasend.com/docs/cli/installation).
