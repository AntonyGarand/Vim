# My vim folder for Windows

My personnal vim for windows.  
This vim is 64 bit and requires 64 bit tools.(ex: python)

## Plugins

Airline: Better information on the current mode, selection and position  
delimitMate: Automatically open and close brackets on creation.  
easyMotion: Easily move to a specific place  
easyoperator-line: Select and use verbs with lines relatively to current position.
exchange: Easily swap 2 words  
gundo: History map of undo, can preview and swap between previous undo nodes.  
headlight: Gvim menu with list of plugin commands  
markdown: Markdown syntax and coloring  
neocomplete: Better autocomplete  
nerdcommenter: easily comment and uncomment lines  
nerdtree: File manager interface (Toggle using F2)  
php: Better php syntax highlighting  
python: Better python syntax highlighting  
rainbow_parentheses: Colors matching parentheses, usefull when working with a lot of these  
solarized: Color theme
Sparkup: Currently broken, write html using short syntax. Sample:
	ul > li.item-$*3 > strong  
	Becomes:  
	<ul>  
        <li class="item-1"><strong></strong></li>  
        <li class="item-2"><strong></strong></li>  
        <li class="item-3"><strong></strong></li>  
    </ul>  
Supertab: Autocompletion using Tab  
Surround: Easily surround selection with tags, quotes and brackets  
syntastic: Check for syntax error within code (Think, missing coma?)  
tagbar: Menu checking the tags of the current file. Can browse by function, vars, etc.  
vdebug: Debugging with Vim. I use it with xDebug but is compatible with most debuggers.  


## vimrc

the vimrc is pretty much always commented, here are few keys not to forget:  

jj in insert mode will get back to normal mode  
  
Leader key: Space  
Leader + v: Select previously pasted text  
Leader + w: Open a new vertica split window [ | ]  
Leader + s: Clear the previous search

F2: Open nerdtree  
F3: Preview in NerdTree  
F4: Switch windows  
F5: Open vDebug, wait connection  

Ctrl + T: Open a new tab  
Alt + [1-0]: To to tab  

Marks: 
' and \` are swapped. Use ' to find a line and collumn, use \` to find a line only.

###[EasyMotion]  
s: S + 1 character will search for the next occurences of the char. You can then press the appropriate key to go to this char.  
Leader + j: Highlight first letters of line under, easily swap to other line  
Leader + k: Same as previous but up  
Leader, Leader + w: Look forward words  
Leader, Leader + b: Look backward words  
Easymotion should work with most commands using Leader, Leader + key:  
f, F  
t, T  
b  
