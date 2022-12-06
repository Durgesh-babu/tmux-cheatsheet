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
Prefix d
```
---
## List all sessions.
```bash
Prefix s
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
Prefix x
```
or
```bash
Ctrl + d
```
