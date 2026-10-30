# Which Shell?

the ``` echo$0 ``` and ``` bash --version ``` commands gave the following info for what git shell i am using resulted in:

``` echo$0 ```  ->  /usr/bin/bash

``` bash --version ```  ->

GNU bash, version 5.3.15(2)-release (x86_64-pc-cygwin)  
Copyright (C) 2025 Free Software Foundation, Inc.  
License GPLv3+: GNU GPL version 3 or later <http://gnu.org/licenses/gpl.html>  

This is free software; you are free to change and redistribute it.  
There is NO WARRANTY, to the extent permitted by law.  

# Where am i?

``` pwd ``` returns /c/Users/Jonas

Windows File Explorer shows the directory as "C:\Users\Jonas"

# Where do commands come from?

``` $PATH ``` returns all the directories in use 

it returns:

```` bash ``` -> searched first
```` s\bin ``` 
```` v1.0 ``` -> SSH protocol apparently does not exist

my ``` curl ``` is located at "C:\Program Files\Git\ucrt64\bin\curl.exe"  
my ``` python3 ``` is locatied at "C:\Users\USER\AppData\Local\Microsoft\WindowsApps\python3.exe"  
my ``` git ``` is located at "C:\Program Files\Git\ucrt64\bin\git.exe"  
my ``` git ``` version is git version 2.56.0.windows.4

# How full is my harddrive and how big is my downloads folder

``` df -h ``` tells me that my Hardrive is 930GB big and that it currently 68% full
``` du -sh ~\Downloads ``` tells me that my Download Folder is currently occupying 115GB of my Harddrive,

# Stop a runaway process

I initiated a sleep process w/ ``` sleep 600 ```  

Then i looked it up w/ ``` ps aux | greg sleep ``` and it returned a bunch of precesses with differend IDs, the sleep process had the PID 373.  

The sleep process was terminated via the ```` kill 374 ``` command which terminated any process correseponding to the input PID aka we killed the sleep process.

In the original windows now displays a process terminated message.




