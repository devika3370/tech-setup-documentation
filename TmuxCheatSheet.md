## How to use TMUX

### What is TMUX?
tmux (short for "terminal multiplexer") is a powerful tool that allows you to manage multiple terminal sessions within a single window. It enables you to detach from sessions, keep them running in the background, and reattach to them at any time. This guide provides an overview of tmux setup, configuration, and basic usage to enhance your terminal productivity.

### Usage

Starting a new session<br>
```$tmux```

Starting a new session with a name<br>
```$tmux new -s myname```

List Sessions<br>
```$tmux ls```

Detaching from current tmux session, preserving it's state<br>
```Ctrl+b d```

Attaching to an existing session<br>
```$tmux attach -t session_name```

Kill Session<br>
```$tmux kill-session -t myname```

Kill all tmux sessions<br>
```tmux kill-session```

### Key Bindings
tmux uses a prefix key combination (default: Ctrl+b) followed by another key to trigger commands. Here are some common key bindings:

* Split Vertical: Ctrl+b %
* Split Horizontal: Ctrl+b "
* Switch Panes: Ctrl+b arrow_key
* Resize Pane: Ctrl+b Ctrl+arrow_key

Refer to man tmux for a comprehensive list of key bindings and commands.

### Tips and Tricks
Use tmux sessions to manage groups of windows, and within each session, use windows to organize different tasks. Panes further divide windows into multiple resizable areas.

Customize the status bar to display session information, system status, or any other relevant details using the status-left, status-right, and other options in ~/.tmux.conf.

Extend tmux functionality with plugins like tmux-resurrect for saving and restoring sessions, tmux-continuum for automatic saving of tmux environment, and tmux-tpm for managing plugins easily.




