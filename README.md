```
git clone --bare git@github.com:bonben/config.git  $HOME/.cfg
alias config='/usr/bin/git --git-dir=$HOME/.cfg/ --work-tree=$HOME'
mv .bashrc .bashrc.bak
mv .gitconfig .gitconfig.bak
config checkout
```
