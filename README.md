# linux-cheetsheet

# files
/etc/resolve.conf => DNS

# tmux
session:
tmux => open a new session
tmux new -s session-name => create a new session with custom name
cb :kill-session => kills an active session
cb d => detach from session
tmux a => attach to last session
tmux a -t session-name => attach to a session

window:
cb c => create window
cb n => next window
cb p => previous window
cb & => close current window

pane:
cb % => split horizontaly
cb " => split verticaly
cb arrow keys => switch to other panes
cb + arrow keys => change panes size
cb z => change zoom
cb x => close current pane
