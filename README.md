# dotfiles

[install oh-my-zsh](https://github.com/ohmyzsh/ohmyzsh) 

## Linking to `.zshrc` config
create `~/.zshenv` with the following contents.
```
ZDOTDIR=~/sites/dotfiles
```

## Linking to `.gitconfig`

create `~/.gitconfig` with the following contents:
```
[include]
    path= ~/sites/dotfiles/.gitconfig
```
Any following information will overwrite data in `~/sites/dotfiles/.gitconfig` - useful for adding work email / work git info.   
Confirm settings have been overwritten with `git config user.name` etc.
