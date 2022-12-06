# Tmux Cheat-sheet
By default the Prefix command is Ctrl+b.
## New session.
```bash
tmux
```
## New named session.
```bash
tmux new -s <Name of the session>
```
or 
```bash
tmux new-session -s <Session-name>
```
----
## Attach to a target session.
```bash
tmux attach -t <session-name>
```
---
## Detach from a session.
```bash
tmux detach -t <session-name>
```
or
```bash
Prefix + d
```
---
## List all sessions.
```bash
Prefix + s
```
or 
```bash
tmux ls
```
---
## Kill a session.
```bash
tmux kill-session -t <session-name>
```
or
```bash
Prefix + x
```
or
```bash
Ctrl + d
```
---
## New window.
```bash
tmux new-window -n <window-name>
```
or
```bash
tmux neww -n ramen <window-name>
```
or (recommended)
```bash
Prefix + c
```
---
## Switching windows
Previous window.
```bash
Prefix + p
```
Next window.
```bash
Prefix + n
```
Index window (N = index number like 1,2,3...).
```bash
Prefix + N
```
---
## List all windows.
```bash
Prefix + w
```
---
## Renaming a window.
```bash
Prefix + ,
```
---
## Kill a target window
```bash
tmux kill-window -t <window-name>
```
or
```bash
tmux killw -t <window-name>
```
or
```bash
Prefix + x
```
or
```bash
Ctrl + d
```
---
## New pane
Horizontal
```bash
tmux split-window -h
```
or
```bash
Prefix + %
```
Vertical
```bash
tmux split-window -v
```
or
```bash
Prefix + "
```
---
## Navigate panes
```bash
Prefix + Up
Prefix + Down
Prefix + Left
Prefix + Right
```
---
## List panes
```bash
Prefix + q
```
---
## Delete pane
```bash
Prefix + x
```
or
```bash
Ctrl + d
```
---
## Sizing pane
S is the size in number.
D/U/L/R represent Down/Up/Left/Right.
```bash
tmux resize-pane -D S
tmux resize-pane -U S
tmux resize-pane -L S
tmux resize-pane -R S
```
---
## Changing pane position
Rotate pane
```bash
Prefix + Ctrl + o
```
Swap panes
```bash
Prefix + {
Prefix + }
```
---
## Pane Layouts
```bash
tmux select-layout even-horizontal
tmux select-layout even-vertical
tmux select-layout main-vertical
tmux select-layout main-horizontal
tmux select-layout tiled
```
or toggle between
```bash
Prefix + Space
```
