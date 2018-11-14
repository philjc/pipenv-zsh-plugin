# pipenv-zsh-plugin

[oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh) plugin to set up the pipenv environment

### System Requirements

[pipsi](https://github.com/mitsuhiko/pipsi)

[philjc/pyenv-zsh-plugin](https://github.com/philjc/pyenv-zsh-plugin)

### Installing

Copy the following into your zsh shell.
```shell
curl https://raw.githubusercontent.com/mitsuhiko/pipsi/master/get-pipsi.py | python - --no-modify-path
```

Copy the following into your zsh shell.

```shell
git clone https://github.com/philjc/pipenv-zsh-plugin.git "$ZSH_CUSTOM/plugins/pipenv-pjc"

# Automatically open .zshrc with vim with the search and replace string to activate the pipsi plugin
# just hit 'y' and then ':wq' to save
vim -c ":%s/^plugins=(/plugins=(\r  pipenv-pjc/gc" $HOME/.zshrc && source $HOME/.zshrc
```
