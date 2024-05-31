# My MacOs (.)dotfiles

This repo contains the dotfiles and setup instruction for my MacOs system

## Requirements

Install these prerequisites

### Homebrew

Install [Homebrew](https://brew.sh)

```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

### Git

```bash
brew install git
```

### Stow

```bash
brew install stow
```

## Installation

First, make sure you are in the $HOME directory

```bash
cd ~
```

clone this git repo

```bash
git clone https://github.com/deondazy/dotfiles.git
```

cd into the dotfiles directory you just cloned

```bash
cd dotfiles
```

then use GNU stow to create symlinks

```bash
stow .
```

