# Adams's dotfiles

These dotfiles are managed using [chezmoi](https://www.chezmoi.io/).

## What I use

| Tools                       | Description                                                                  |
| --------------------------- | ---------------------------------------------------------------------------- |
| Terminal emulator           | [Windows Terminal](https://github.com/microsoft/terminal)                    |
| Debain shell                | [OhMyBash](https://github.com/ohmybash/oh-my-bash)                           |
| Dotfiles manager            | [chezmoi](https://chezmoi.io/)                                               |
| Package managers (Win)      | [WinGet](https://learn.microsoft.com/en-us/windows/package-manager/winget/)  |
| Package manager tool (Win)  | [UniGetUI](https://github.com/marticliment/UnigetUI)                         |
| Package managers (Debian)   | [Debian APT](https://wiki.debian.org/Apt)                                    |

## Getting started

Check out the [Quick Start](https://www.chezmoi.io/quick-start/) page.

### Install chezmoi and the dotfiles on any new machine

With a single command:

```sh
sh -c "$(curl -fsLS chezmoi.io/get)" -- init --apply SimAda00
```

### Update

On any machine, you can pull and apply the latest changes from your repo with:

```sh
chezmoi update -v
```

## Reference

[How To Manage Dotfiles With Chezmoi](https://jerrynsh.com/how-to-manage-dotfiles-with-chezmoi/)
