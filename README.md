.files-msysgit
==============

These are my .files for msysgit. There are many like them, but these are mine.

Most interesting changes from defaults are related to:

* environment variables (PATH, etc)
* correcting an msysgit bug with libiconv-2.dll
* using internal directories for /tmp, /home


The starting point for this environment is:

[msysgit1.7.6](http://code.google.com/p/msysgit/downloads/detail?name=msysGit-fullinstall-1.7.6-preview20110708.exe&can=2&q=)

To actually get this environment up and running, there are some things I currently have to do by hand. 

* install Console2
* install pik
* get a ruby with pik
* git clone https://github.com/oneclick/rubyinstaller.git
* modify rubyinstaller to remove redirection '> NUL 2>&1'
* build devkit
* extract devkit *on top of* msysgit

