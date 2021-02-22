## 1. Tmux ( Terminal Multiplexer / switch between tabs  )

	* ctrl + shift + c = copy
	* ctrl + shift + v = paste 
	* ctrl b + c = new tab
	* ctrl b + n = switching last tabs
	* ctrl b + 0 - 9 = switch / select windows by number 
	* ctrl b + d = deleting session 
	* ctrl b + % = vertical split
	* ctrl b + " = horizontol split
	* ctrl b + x = kill current pane 
	* ctrl b + o = go to next pane
	* ctrl b + w = list of all open tmux processe
	* ctrl b + & = kill window 
	* ctrl b + PgUp = scrolling mode = q for quit 

## 2. VIM ( Virtual Improved / Editor )

Basic Vim Commands
  * i       = going into Insertmode
  * esc :q! = Quitting withot saving
  * esc :q  = Quitting 
  * esc :w  = Saving 
  * esc :wq = Saving and Quitting
  * esc :e  = Open files in vim 

Vim Commands for movement
  * esc h = moves left 
  * esc l = moves right 
  * esc j = moves down 
  * esc k = moves up 
  * esc H = Cursor top of the screen 
  * esc L = Cursor bottom of the screen
  * esc w = Cursor start of the next word
  * esc b = Cursor start of the previous word
  * esc e = Cursor at the end of the word 
  * esc 0 = Cursor at the beginning of a line 
  * esc $ = Cursor at the end of a line 
  * esc G = Cursor at the end of the file 

Vim Commands for Editing
  * ESC     = Insertmode left
  * esc yy  = copies a line
  * esc yw  = copies a word 
  * esc v   = selecting one character 
  * esc V   = selecting one line
  * esc A   = spring to the end of the current line 
  * esc d   = deletes highlighted text
  * esc dw  = deletes a word
  * esc dd  = deleting line 
  * esc u   = undo last change
  * esc P   = Inserting line 
  * esc 4gg = Jump to the line number
  * cat file | pbcopy = copy all the lines in the file 

Vim commands for searching
  * /[keyword] = Searches for the word in the document
  * n          = Searches your word in next word  
  * :%s/[keyword]/[replacement] = This will replace the keyword

Vim commands for working with multiple files
  * :sp [filename] = Opens a new file and splits your screen horizontally

## 3. Github  

Adding files to a repository
  * git init = Initialize the local directory as a Git repository
  * git add (.) = Add the file(s) to your local repository and stages it for commit
  * git commit -m "Add existing file" = Commits the tracked changes and prepares them to be pushed
  * git push (origin master) = Pushes the changes in your local repository up to the remote repository 

Basic knowledge
  * git clone = clone an existing repository from elsewhere
  * git pull = fetch from and integrate with another repository or a local branch 

!Error - Please, commit your changes or stash them before you can mer merge
  * rm file = delets the file 
  * git reset --hard = resets the file of the index of the working directory 
  * git pull = fetch from and integrate with another repository or a local branch


## 4. ssh 
	* sudo service ssh status = shows status of ssh
	* sudo service ssh start = start ssh server
	* sudo service ssh stop = stop ssh server
	* sudo /sbin/shutdown = shutdown pc-server 
	* scp "filename" user@host: = Copy the file to the host in home directory
	* rsync --remove-source-files "filename" user@host: = move the file to the host home directory and delet it on the local machine

