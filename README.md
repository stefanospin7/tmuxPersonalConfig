# tmux PersonalC onfig

*This are some config I like on tmux (terminal app)


sudo nano ~/.tmux.conf



# changing prefix from 'Ctrl+b' to 'Ctrl+a'

unbind C-b
set-option -g prefix C-a


# Splitting terminals using + and -

unbind '"'

unbind %

bind - split-window -h

bind + split-window -v
