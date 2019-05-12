tmux shortcuts & cheatsheet
tmux            start new
tmux ls           list sessions
tmux new -s myname        start new with session name
tmux rename -t 0  byname
tmux a  #  (or at, or attach)     attach
tmux detach                     detach one
tmux a(ttach)                   attach one
tmux a -t myname        attach to named
tmux kill-session -t myname     kill
tmux ls | grep : | cut -d. -f1 | awk '{print substr($1, 0, length($1)-1)}' | xargs kill     kill all
tmux source-file ~/.tmux.conf                           source conf
Sessions
s  list sessions
$  name session
d  detach
t  big clock
?  list shortcuts
:  prompt
Windows (tabs)
d  dettach window
c  new window
w  list windows
f  find window
,  name window
&  kill window
  (num 0,1,2,3 etc.) switch window
Panes
%  vertical split
"  horizontal split
o  swap panes
q  show pane numbers
x  kill pane
+  break pane into window (e.g. to select text by mouse to copy)
-  restore pane from window
⍽  space - toggle between layouts
<prefix> q (Show pane numbers, when the numbers show up type the key to goto that pane)
<prefix> { (Move the current pane left)
<prefix> } (Move the current pane right)
<prefix> z toggle pane zoom
