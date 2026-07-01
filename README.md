# customizations

Personal terminal and shell customizations.

## oh-my-posh

A custom oh-my-posh prompt theme, stored at `oh-my-posh/themes/hennie.omp.json`.

It is a powerline-style prompt that shows an OS or WSL icon, a session segment with the user name, the current working directory, Git branch and status, and language and runtime segments.

## Prerequisites

Install oh-my-posh from https://ohmyposh.dev/docs/installation and install a Nerd Font so the powerline glyphs and icons render correctly, from https://ohmyposh.dev/docs/installation/fonts

## Usage

Clone this repository, then point oh-my-posh at the theme from your shell profile.

In PowerShell, add this line to your profile: `oh-my-posh init pwsh --config /path/to/hennie.omp.json | Invoke-Expression`

For Bash, Zsh, Fish and other shells, follow the prompt setup guide at https://ohmyposh.dev/docs/installation/prompt

Reload your shell and the prompt will use the theme.

## License

Released under the MIT License. See LICENSE for details.
