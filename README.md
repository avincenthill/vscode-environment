# Automate your dev setup on a new machine!
## vscode-environment-automation

This shell script quickly configures git (.gitconfig), VSCode, and bash (.bashrc) with my settings. This installs the following VSCode extensions

```
shardulm94.trailing-spaces
formulahendry.auto-rename-tag
wesbos.theme-cobalt2
dbaeumer.vscode-eslint
donjayamanne.githistory
sysoev.language-stylus
ritwickdey.liveserver
esbenp.prettier-vscode
ms-python.python
equimper.react-native-react-redux
wayou.vscode-todo-highlight
vsmobile.vscode-react-native
formulahendry.auto-close-tag
shardulm94.trailing-spaces
robertohuertasm.vscode-icons
```

and asks you for .gitconfig username and email, and replaces .bashrc (mine has git branch indication and some nice aliases) and replaces VSCode User Settings and Keybindings with my preferences (wes bos cobalt2 color scheme, line bubbling/duplication, and more). Don't execute until you read through the shell script and understand what everthing does, and I don't assume liability for you using this and accidentally overwriting your non-backed-up .bashrc.

Remember to

`chmod u+x configDevEnvironment.sh`

before executing the script in the root directory of this repo with

`./configDevEnvironment.sh`

Happy hacking! -AVH
