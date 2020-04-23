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

/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)" 
```

Install zsh and all the packages

```bash
sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"

brew bundle --file ~/.mmigrate/brew/Brewfile
```

