# vscode
## Basic editing

| Command   |      effect      
|----------|:-------------
Ctrl + P |  Quick Open 
Ctrl + Shift + N | New Window/instance 
Ctrl + W  | Close window/instance|
Ctrl+X               |Cut line (empty selection)
Ctrl+C               |Copy line (empty selection)
Alt+ ↓ / ↑           |Move line down/up
Ctrl + Shift + K         |Delete line
Ctrl + Shift + Alt + m         |Copy line down 
Ctrl+Enter / Ctrl+Shift+Enter  |Insert line below/above
Ctrl+Shift+\         |Jump to matching bracket
Home / End           |Go to beginning/end of line
Ctrl+ Home / End    |Go to beginning/end of file
Ctrl+Shift+V         |Open Markdown preview
Ctrl+J               |Fold/Unfold all regions
Ctrl+K Ctrl+O        |Open Folder
Ctrl+K Ctrl+S        |Keyboard Shortcuts
Ctrl + B 	 |Open/close side bar
Ctrl + D 	 |Select word
Ctrl + left/right arrow  |move cursor to beginning last word

## Multi-cursor and selection
| Command   |      effect      
|----------|:-------------
Alt+Click | Insert cursor*
Shift+Alt+ ↑ / ↓ | Insert cursor above/below
Ctrl+U | Undo last cursor operation
Shift + Alt + I	| place cursor at the end of selected lines
Ctrl+L | Select current line
Ctrl+Shift+L | Select all occurrences of current selection
Ctrl+F2 | Select all occurrences of current word
Shift+Alt + → | Expand selection
Shift+Alt + ← | Shrink selection

## Display
| Command   |      effect      
|----------|:-------------
Ctrl + b 	| Toggle sidebar visibility
Ctrl + Shift + e | explore file
Ctrl + Shift + f | search tab
Ctrl + Shift + G , G | open source control tab
Ctrl+Shift+H | Replace in files
F3 / Shift + F3 | to find the next/previous
Ctrl+Shift+C | Open new command prompt/terminal
Ctrl + G 	| move to line 
Ctrl+K Z | Zen Mode (Esc Esc to exit)

## Editor management
| Command   |      effect      
|----------|:-------------
Ctrl+W | Close editor
Ctrl+K F | Close folder
Ctrl+Alt+M | move active editor to right group
Ctrl+Alt+N -|move active editor to left group
Ctrl+Shift+PgUp | Move editor left
Ctrl+Shift+PgDn | Move editor right
Ctrl + K + Left/RightArrow	| move edtiroegroup left/right

## File management
| Command   |      effect      
|----------|:-------------
Ctrl+N | New File
Ctrl+O | Open File
Ctrl+Shift+T | Reopen closed editor
Ctrl+Tab | Open next
Ctrl+Shift+Tab | Open previous
Ctrl+K R | Reveal active file in Explorer

# tmux
## base control of sessions
| Command   |      effect      
|----------|:-------------
tmux                | open a session
tmux a          | se rattacher à session
Ctrl+b c 	    | Create a new window
Ctrl + b , d | detach from session tmux 
tmux detach         | Se détacher de la session
tmux ls             | list the sessions attached
tmux attach -t "sessionName" | attach session of the name
tmux kill-session -t id| stop tmux session
exit                | shut down the session

# terminal manager
| Command   |      effect      
|----------|:-------------
Ctrl b , 'n'       | Switcher entre les différents terminaux de la session
Ctrl + b , 'X'     | Choisir un terminal spécifique (ou X est le numéro du terminal)
Ctrl + b , ','   | Permet de renommer un terminal
Ctrl + b , 'w'     | Affiche la liste des terminaux disponibles
Ctrl + b , '&'   | Supprime la fenêtre courante
Ctrl + b , ':' 	| Enter the tmux command prompt.

# split manager
| Command   |      effect      
|----------|:-------------
Ctrl + b , '%'       | Split vertical du terminal courant en deux + ouverture d’un terminal dans le nouveau panel
Ctrl + b , 'o'       | Switcher entre les terminaux splittés
Ctrl + b , 'espace'  | Changer l’organisation visuelle des terminaux splittés
Ctrl + b , '"'       | Split horizontal du terminal courant en deux + ouverture d’un terminal dans le nouveau panel
Ctrl + b , (flèches directionnelles) | se déplacer de terminal en terminal
Ctrl + b , '!'       | Convertir un split en terminal seul
Ctrl + b , 'q'       | Afficher les numéros des terminaux splittés
Ctrl + b + : +'join-pane -s 'source' -t 'dst-pane' | merge!!!!!!
Ctrl + b + Ctrl +':' + break-pane -t|

# Chrome
| Command   |      effect      
|----------|:-------------
Alt + n | Move to Tab # n={1…8}
Alt + 9 | Move to rightmost/last Tab
Ctrl + Page Up/Down | Move to next/previous Tab
Ctrl + w | Close the current tab
Ctrl + Shift + w | Close the current window
Ctrl + Shift + I | Inspect (Developer)
Ctrl + R | Reload the page
Ctrl + t | open a new tab
Ctrl + Shift + T | Reopen last closed tab or window
ALT + D | Jump to the address bar
Ctrl + k | google search
Ctrl + Click a link | Open a link in new background tab
Ctrl + L | Focus Address bar
Shift + Enter | open url in a new window
Type a search term + Alt + Enter | Open a new tab and perform a Google search

# ubuntu
| Command   |      effect      
|----------|:-------------
Super + D | Show desktop
Ctrl + Alt + Arrow Left/Right | Switch Workspace
Ctrl + W | Close Window
Super + Arrow Up/Down | Make window small or full screen
Super + Arrow Left/Right -|Snap window to side
Ctrl + Alt + T | Terminal Open window
Super + space 	| switch to next input source
Shift + Super + space 	| switch to previous input source
Shift + Super + left/right | move window one monitor to the left
Shift + Super + PgUp/PgDn | move window one worskapce to the left/right
Shift + Tab | switch applications
Super + Home/End | switch to first/last workspace
Ctrl + Alt + F | launch firefox
Ctrl + Alt + H | open home folder