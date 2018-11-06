# pipsi-zsh-plugin

[oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh) plugin to set up the pipsi environment

### Installing

Copy the following into your zsh shell.
```shell
curl https://raw.githubusercontent.com/mitsuhiko/pipsi/master/get-pipsi.py | python - --no-modify-path
```

Copy the following into your zsh shell.

```shell
git clone git@github.com:philjc/pipsi-zsh-plugin.git "$ZSH_CUSTOM/plugins/pipsi-pjc"

# Automatically open .zshrc with vim with the search and replace string to activate the pipsi plugin
# just hit 'y' and then ':wq' to save
vim -c ":%s/^plugins=(/plugins=(\r  pipsi-pjc/gc" $HOME/.zshrc && source $HOME/.zshrc
```