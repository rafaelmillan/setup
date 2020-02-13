# Quick setup for a new Mac

1. Install https://ohmyz.sh/
2. Copy zshrc config `cp .zshrc ~/.zshrc`
3. Install http://brew.sh/
4. Install brew packages `brew bundle`
5. Copy Atom config:
```
cp ./atom/{config.cson,github.cson,keymap.cson} ~/.atom/
```
6. Install Atom packages `` apm install `cat ./atom/packages.list` ``
