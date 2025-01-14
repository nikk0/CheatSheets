# Tmux cheat sheet (tmux 3.5a)
-------------

## Usage

Start a new session
```bash
tmux new -smysession
```

Add a custom binding

in the ~/.tmux.conf:  
To toogle the sync panes with C-X (without C-b):
```bash
bind -n C-x setw synchronize-panes
```

## Shortcuts

### Panes

```bash
C-b "       Split window horizontally  
C-b %       Split window vertically 

C-b o       Select the next pane  
C-b C-o     Rotate through the panes  
C-b ;       Move to the previously active pane  

C-b x       Kill the active pane  

C-b z       Zoom the active pane  

C-b {       Swap the active pane with the pane above  
C-b }       Swap the active pane with the pane below 

C-b f       Search for a pane  
C-b E       Spread panes out evenly  

C-b q       Display pane numbers  

C-b m       Toggle the marked pane  
C-b M       Clear the marked pane

C-b Up      Select the pane above the active pane  
C-b Down    Select the pane below the active pane  
C-b Left    Select the pane to the left of the active pane  
C-b Right   Select the pane to the right of the active pane  

C-b C-Up    Resize the pane up  
C-b C-Down  Resize the pane down  
C-b C-Left  Resize the pane left  
C-b C-Right Resize the pane right  
C-b M-Up    Resize the pane up by 5  
C-b M-Down  Resize the pane down by 5  
C-b M-Left  Resize the pane left by 5  
C-b M-Right Resize the pane right by 5  
```

### Layouts
```bash
C-b <Space> Toogle layouts 
C-b M-1     Set the even-horizontal layout  
C-b M-2     Set the even-vertical layout  
C-b M-3     Set the main-horizontal layout  
C-b M-4     Set the main-vertical layout  
C-b M-5     Select the tiled layout  
C-b M-6     Set the main-horizontal-mirrored layout  
C-b M-7     Set the main-vertical-mirrored layout  
```

### Sessions
```bash
C-b s Choose a session from a list  
```

### Windows
```bash
C-b c       Create a new window  
C-b w       Choose a window from a list 
C-b n       Select the next window  
C-b p       Select the previous window 
C-b &       Kill current window 
C-b f       Find window
C-b ,       Rename current window 
C-b l       Select the previously current window  
C-b 0       Select window 0  
C-b 1       Select window 1  
C-b 2       Select window 2  
C-b 3       Select window 3  
C-b 4       Select window 4  
C-b 5       Select window 5  
C-b 6       Select window 6  
C-b 7       Select window 7  
C-b 8       Select window 8  
C-b 9       Select window 9  
```

### Miscellaneous
```bash
C-b !       Break pane to a new window  
C-b #       List all paste buffers  
C-b $       Rename current session  
C-b '       Prompt for window index to select  
C-b (       Switch to previous client  
C-b )       Switch to next client  
C-b -       Delete the most recent paste buffer  
C-b .       Move the current window  
C-b /       Describe key binding  
C-b :       Prompt for a command  
C-b =       Choose a paste buffer from a list  
C-b ?       List key bindings  
C-b C       Customize options  
C-b D       Choose and detach a client from a list  
C-b L       Switch to the last client  
C-b [       Enter copy mode  
C-b ]       Paste the most recent paste buffer  
C-b d       Detach the current client  
C-b i       Display window information  
C-b r       Redraw the current client  
C-b t       Show a clock  
C-b ~       Show messages  
C-b DC      Reset so the visible part of the window follows the cursor  
C-b PPage   Enter copy mode and scroll up  
C-b M-n     Select the next window with an alert  
C-b M-o     Rotate through the panes in reverse  
C-b M-p     Select the previous window with an alert  
C-b C-b     Send the prefix key  
C-b C-z     Suspend the current client  
C-b S-Up    Move the visible part of the window up  
C-b S-Down  Move the visible part of the window down  
C-b S-Left  Move the visible part of the window left  
C-b S-Right Move the visible part of the window right  
```

## Commands
TBC
