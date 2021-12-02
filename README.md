# dotfiles

[install oh-my-zsh](https://github.com/ohmyzsh/ohmyzsh) 

## Linking to `.zshrc` config
create `~/.zshenv` that inits zsh from this repo:
```
echo 'ZDOTDIR=~/sites/dotfiles' > ~/.zshenv
```

## Linking to `.gitconfig`

create `~/.gitconfig` that links to the one in this repo:
```
[include]
    path= ~/sites/dotfiles/.gitconfig
```
Any following information will overwrite data in `~/sites/dotfiles/.gitconfig` - useful for adding work email / work git info.   
Confirm settings have been overwritten with `git config user.name` etc.
