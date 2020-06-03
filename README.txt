Everything about how Bash (Packages) Works

1. Tmux ( Terminal Multiplexer / switch between tabs  )
-Commands..
.. strg + shift + c = copy
.. strg + shift + v = paste 
.. ctrl b + c = new tab
.. ctrl b + n = switching tabs
.. ctrl b + 0 - 9 = switch / select windows by number 
.. ctrl b + d = deleting session 
.. ctrl b + % = vertical split
.. ctrl b + " = horizontol split
.. ctrl b + w = list of all open tmux processe
.. ctrl b + & = kill window 
.. ctrl b + PgUp = scrolling mode = q for quit 

2. VIM ( Virtual Improved / Editor )

2.1 Basic Vim Commands 
.. i       = going into Insertmode
.. esc :q! = Quitting withot saving
.. esc :q  = Quitting 
.. esc :w  = Saving 
.. esc :wq = Saving and Quitting
.. esc :e  = Open files in vim 

2.2 Vim Commands for movement 
.. esc h = moves left 
.. esc l = moves right 
.. esc j = moves down 
.. esc k = moves up 
.. esc H = Cursor top of the screen 
.. esc L = Cursor bottom of the screen
.. esc w = Cursor start of the next word
.. esc b = Cursor start of the previous word
.. esc e = Cursor at the end of the word 
.. esc 0 = Cursor at the beginning of a line 
.. esc $ = Cursor at the end of a line 
.. esc G =

2.3 Vim Commands for Editing
.. ESC     = Insertmode left
.. esc yy  = copies a line
.. esc yw  = copies a word 
.. esc v   = selecting one character 
.. esc V   = selecting one lines
.. esc A   = spring to the end of the current line 
.. esc d   = deletes highlighted text
.. esc dw  = deletes a word
.. esc dd  = deleting line 
.. esc u   = undo last change
.. esc P   = Inserting line 
.. esc 4gg = Jump to the line number

2.4 Vim commands for searching 
.. /[keyword] = Searches for the text in the document
.. n          = Searches your text in whatever direction 
.. :%s/[keyword]/[replacement] = This will replace the keyword

2.5 Vim commands for working with multiple files
.. :sp [filename] = Opens a new file and splits your screen horizontally

3.0 ~/home

3.1 .bashrc
export PS1="\e[0;36m\u@\e[m\W\$ " ( George Hotz )
export PS1='\u@\[\e[33m\]\W\[\e[0m\]\$ ' ( George Hotz + My own )
export PS1='\u@\h:\[\e[33m\]\w\[\e[0m\]\$ ' ( My own, blue )
