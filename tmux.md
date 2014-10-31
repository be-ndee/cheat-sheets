# Commands

CTRL+B : starts tmux-input

After CTRL+B type the following keys:

* arrows : move around in panes
* c : new window
* " : horizontal-pane-dividing
* % : vertical-pane-dividing
* x : kill pane
* & : kill window

#### Resize panes

After CTRL+B type in the following:

```
: resize-pane -U
: resize-pane -L
: resize-pane -R
: resize-pane -D
```
Resizes UP, LEFT, RIGHT and DOWN  
Optionally add a value (e.g. 20)
