# my configuration stuff

This repo is for storing the dotfiles (configuration files for software) that I use on a daily basis.
Helps speed up setting up new machines with my favorite settings, themes, etc. Plus I like CLIs so it's better than managing the whole thing using Google Drive or something.

The tool that I use to manage my dotfiles is [chezmoi](https://github.com/twpayne/chezmoi). Slight overhead as this tool needs to be installed first for syncing the dotfiles but the pros definitely make up for it.

Git is also needed btw

## Usage

1. Install [chezmoi](https://www.chezmoi.io/install/) for your distro/platform

2. `chezmoi init --apply https://github.com/bhodrolok/dotfiles.git`
