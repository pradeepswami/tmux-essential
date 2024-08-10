# Tmux-essential
Tmux essential commands

## Sessions


```
tmux                      :Create new session 
tmux new -s sessionname   :New session with name
tmux ls                   :List existing session
tmux a -t sessionname     :Attach 
```

## Windows
`bind-key` and
```
c    :Create new window
w    :List all windows
n    :Move to next window
p    :Move to previous window
,    :Rename window
[0-9]:Move to window  

```

## Panes
`bind-key` and
```
%     :Split vertically
"     :Split horizontally
x     :Kill pane
q     :Show pane number
arrow :Switch pane

```
#### Resize pane
`bind-key` and  

`ctrl`+ `↑` \
`ctrl`+ `↓` \
`ctrl`+ `←` \
`ctrl`+ `→` 


#### Join window to pane
`ctrl+b :` join-pane -s 0 -t 1


## Help
`ctrl+b ?`

 




