# Lullabot Homebrew Tap — `sandbar`

Homebrew formulae for [`sandbar`](https://github.com/Lullabot/sandbar), a CLI/TUI
that spins up disposable [Lima](https://lima-vm.io) VMs preconfigured as Claude
Code development environments.

## Install

    brew install lullabot/sandbar/sandbar

That one-liner taps this repository and installs the formula. If you'd rather
tap explicitly:

    brew tap lullabot/sandbar
    brew install sandbar

**Supported platforms:** macOS and Linux, on both amd64 and arm64.

## Renamed from `sand`

The formula was previously named `sand`. Existing installs migrate to `sandbar`
on the next `brew update && brew upgrade`, via `formula_renames.json`. Releases
after the rename also install a `sand` compatibility symlink that prints a
deprecation warning.
