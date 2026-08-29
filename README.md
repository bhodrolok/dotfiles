# my configuration stuff

This repo is for storing the dotfiles (configuration files for software) that I use on a daily basis.
Helps speed up setting up new machines with my favorite settings, themes, etc. Plus I think it's better to manage things like this over a version control system than something like Google Drive.

The tool that I use to manage my dotfiles is [chezmoi](https://github.com/twpayne/chezmoi). Slight overhead as this tool needs to be installed first for syncing the dotfiles but the pros definitely make up for it.

Git is also needed btw

## Usage

> [!NOTE]
>  Can also run this to both install chezmoi (using their official install script) and setup the repo: `sh -c "$(curl -fsLS https://get.chezmoi.io)" -- init --apply $GITHUB_USERNAME`


1. Install [chezmoi](https://www.chezmoi.io/install/) for your distro/platform

2. Run either one of the following on a terminal:
    - `chezmoi init --apply --verbose https://github.com/bhodrolok/dotfiles.git`  
    - `chezmoi init https://github.com/bhodrolok/dotfiles.git` first followed by `chezmoi diff` to check the changes before running `chezmoi apply`

