# fish

### initialize for your mac

following apolication required.

- homebrew
- https://github.com/fikovnik/ShiftIt

### initialize fish

```fish
brew install fish peco ghq fzf
```

Specifies the directory which manages the repository with ghq

```fish
git config --global ghq.root ~/git
```

## fisher setup

https://github.com/jorgebucaran/fisher/

```fish
curl https://git.io/fisher --create-dirs -sLo ~/.config/fish/functions/fisher.fish
```

```fish
fisher
```
