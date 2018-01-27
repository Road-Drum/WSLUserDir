# Script to change WSL user directory to Windows user directory

# Why?

WSL directory can be accessed in Windows Explorer from `C:\Users\yourname\AppData\Local\Packages\CanonicalGroupLimited.UbuntuonWindows_mayberandomvalues\LocalState\rootfs`.
While it is accesible, it is a hassle to work in that directory (imagine working with Git in that directory and you need to copy/paste many stuff at once).
Being lazy, we can just work at our own Windows directory using WSL Shell. 

# Where is my user directory then?

Same as Windows directory, such that `/mnt/c/Users/yourname`. Windows drives are located at `/mnt`, labelled alphabetically with lowercase. Say, `C:` is `/mnt/c`.  

# Neat, now I need a simple script to make stuff easier

Have a look at the code or clone it. It's pretty simple.

To run the code, use `. wsldir.sh` instead of `./wsldir.sh`


That said, happy working with WSL!  
