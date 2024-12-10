###############################################################################
# bash aliases
###############################################################################

# grep with colors
alias grep='grep --color=auto'
alias egrep='egrep --color=auto'
alias fgrep='fgrep --color=auto'

# some more ls aliases
alias ll='ls -alF'
alias la='ls -A'
alias l='ls -CF'


# calculator
alias calc='echo -e "Python-based Calculator\nCtrl-D or quit() to quit"; \
    ipython3 -i -c="from math import *; \
    from statistics import *"'

# clear
alias c='clear'

# syntax highlighting for cat (requires bat binary)
alias cat="bat --color=always"
alias less="less -R"

# check running daemons
alias daemons='systemctl | grep daemon'

# check loaded services
alias services='systemctl --type=service --state=running'

# tmux
alias tmux="tmux -2"

# wget
alias wget='wget -N -c'

# use vim for default editor
alias vi="vim"
alias nvim="vim"

# nvim -d for vimdiff
alias vimdiff='nvim -d'

# vim keys to exit
alias :q='exit'

# fzf
alias fzf='fzf --preview="batcat --color=always {}"'

# update proxychains
alias upx='sudo fzproxy --country="Japan|Singapore|United States"'

# sshuttle
alias sshu='/var/home/philip/.local/bin/sshuttle-controller'
