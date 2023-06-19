## ZSH
Install oh-my-zsh

```
sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions
```

```
git clone git@github.com:nguyentbinh/zsh-config.git ~/.config/zsh
ln -s ~/.config/zsh/zshrc ~/.zshrc
```

## Tmux

```
git clone https://github.com/gpakosz/.tmux.git ~/Github/oh-my-tmux
mkdir -p ~/.config/tmux
ln -s ~/Github/oh-my-tmux/.tmux.conf ~/.config/tmux/tmux.conf
cp ~/Github/oh-my-tmux/.tmux.conf.local ~/.config/tmux/tmux.conf.local
```

## Git

```
git config --global user.name "Binh Nguyen"
git config --global user.email "binh.nguyen@example.com"

git config --global push.autoSetupRemote true
git config --global core.editor "vi"
```
