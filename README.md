# TMUX COMMANDS

## Install

```
sudo apt install tmux
```

- copy .tmux.conf under ~/

- reload

```
tmux source-file ~/.tmux.conf
```

## Commands

```
Prefix = Ctrl + a
```

- Open new pane
> Prefix + . or -

- Navigating panes
> Alt + cursor

- Closing panes
> Ctrl + d

- Create new windows (virtual desktop)
> Prefix + c

- Navigating windows
> Prefix + p (previous) or n (next)

- Terminate windows
> Prefix + q

- Detach current session
> Prefix + d or D (to choice which session)

- See list of sessions
```
tmux ls
```

- attach to a old session
```
tmux attach -t <session name>
```

- create a new session with a custom 
name
```
tmux new -s <session name>
```

- rename a session
```
tmux rename-session -t <old session name> <new session name>
prefix + $
```

- make a pane full screen
```
prefix + z
```

- rename current window
```
prefix + ,
```
