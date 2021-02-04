## Installing software
MAC/OSX -- brew, cask (macports program)
A few commands
$ df -h # check how much space do I have lefts 
$ whoami
$ groups
$ sudo # do something as the "super user" or "root"
Root has all permissions, can do anything to the system.
Avoid using sudo or the root user as much as possible. Use only when necessary.
Package management systems: apt, snap, npm, brew, cask, yum, gem, emerge
$ sudo apt update	# updates the list of things that I can install
$ sudo apt install	# actually installs something
$ sudo apt remove	# uninstall something
$ sudo apt search google chrome	# search for something to install
$ sudo apt autoremove # remove left over files from updating and installing
$ sudo snap search opera
$ sudo snap install opera
$ sudo snap remove
$ npm install -g "something" # node package manager installation
$ npm uninstall -g "something" 
$ which  # show information about a program
$ whereis # show program location
## Browser Basics
Big browsers: Google Chrome, Safari, Internet Explorer, Edge, Mozilla Firefox
Small browsers: Opera, Brave, Vivaldi, eLinks, DuckDuck, Midori....
Target browsers: Support latest version of chrome and Edge
Browser = Browser Engine + JavaScript engine + other stuff too, such as plugins and tools
Browser Engine = HTML to visual rendering
JavaSript Engine = Runs Javascript
If your site works with one Browser using the Blink engine, most likely other Blink engine Browsers will work too.
If your JS works with one browser that uses the V8 engine, it will most likely work with all of them.
Shortcuts
^T -- opens new tab
^N -- opens new window
^W -- closes a tab
^Shift-T -- reopens a closed tab
^Shift-N -- reopens a closed window
F11 -- view full screen
F12 -- open developer console -- the web developers best friend and toolkit