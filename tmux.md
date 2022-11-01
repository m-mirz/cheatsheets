# tmux

new session:

    tmux

new session with name:

    tmux new -s [name]

attach:

    tmux a

attach to named session:

    tmux a -t [name]

list sessions:

    tmux ls

kill session:

    tmux kill-session -t [name]

Kill all tmux sessions:

    tmux kill-server

## Command mode

Press the PREFIX `Ctrl + B` and then:

    d  detach    
    ?  list shortcuts
    :  prompt

### Sessions

    :new -s [name] new session
    s  list sessions
    $  name session

### Tabs / Windows

    c  create window
    w  list windows
    n  next window
    p  previous window
    f  find window
    ,  name window
    &  kill window

### Splits / panes

    %  vertical split
    "  horizontal split
    
    o  swap panes
    q  show pane numbers (when the numbers show up type the key to goto that pane)
    x  kill pane
    +  break pane into window (e.g. to select text by mouse to copy)
    -  restore pane from window
    space - toggle between layouts
    { (Move the current pane left)
    } (Move the current pane right)
    z toggle pane zoom

### Resizing Panes

    PROMPT resize-pane -D 20 (Resizes the current pane down by 20 cells)
    PROMPT resize-pane -U 20 (Resizes the current pane upward by 20 cells)
    PROMPT resize-pane -L 20 (Resizes the current pane left by 20 cells)
    PROMPT resize-pane -R 20 (Resizes the current pane right by 20 cells)
