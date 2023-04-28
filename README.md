# macos-migration
My personal list of MacOS dotfiles and extras to smooth out a migration to a new Mac

## Install

Clone this repository:

```bash
git clone git@github.com:jakubhomoly/macos-migration.git ~/.mmigrate
```

## Homebrew

Install homebrew

```bash
xcode-select --install

/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

Install zsh and all the packages

```bash
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"

brew bundle --file ~/.mmigrate/brew/Brewfile
```

