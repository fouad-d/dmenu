dmenu
dmenu is a dynamic menu for X, originally designed for dwm. It manages large numbers of user-defined menu items efficiently.  It is a very powerful tool that allows you to pipe information into it.  This makes dmenu a perfect utility to incorporate into your scripting.

Mouse functionality
Mouse actions supported:

  Left-mouse click:
    
      On prompt and input field: clear input text and selection.
      In horizontal and vertical mode on item: select and output item (same as pressing enter).
      In horizontal mode on arrows: change items to show left or right.
    
  
  Ctrl-left-mouse click: multisel modifier.
  Right-mouse click: close.
  Middle-mouse click:
    
      Paste current selection.
      While holding shift: paste primary selection.
    
  
  Scroll up:
    
      In horizontal mode: same as left-clicking on left arrow.
      In vertical mode: show items above.
    
  
  Scroll down:
    
      In horizontal mode: same as left-clicking on right arrow.
      In vertical mode: show items below.
			
Installing dmenu
Download the source code from this repository or use a git clone:

`git clone https://gitlab.com/fouad-dev/dmenu.git`

`cd dmenu-distrotube`

`sudo make clean install`
