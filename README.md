# git-mods

bashrc:

export PS1="\[\033[38;5;11m\]\u\[$(tput sgr0)\]\[\033[38;5;15m\]@\h:\[$(tput sgr0)\]\[\033[38;5;6m\][\w]:\[$(tput sgr0)\]\[\033[38;5;15m\]\$(__git_ps1)$blue \[$(tput sgr0)\]"





Git stuff:

git config --global user.name ""
git config --global user.email ""
git config --global core.editor "atom --wait"
