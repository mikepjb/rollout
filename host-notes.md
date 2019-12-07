# Host Notes

Documenting details about target systems that should be addressed.

## Windows & Cygwin

TODO ensure x server starts at windows startup (so urxvt etc can launch)

a few packages need to be installed that are not default including:

  - openssh
  - wget & curl (may need updating?)
  - tmux
  - urxvt
  - xorg-server
  - xinit
  - gvim (default is small vim install (without mouse/clipboard support etcetc)
    - after installation the vimx binary should be put under /usr/bin/vi and /usr/bin/vim
  - fzf (available on cygwin.. but not on RHEL)

also sudo is not available
neither is xrdb

none of the ctrl keys or tab seem to work properly

node must include -i flag to be interactive (default seems to be broken/miscommunicating)

(contents of Cygwin.bat to launch urxvt for Windows 10)
start "" /B "C:\cygwin64\bin\urxvt" -e /bin/bash --login -i

also be aware that urxvt PATH is not the same as mintty

installing nodejs (LTS) also provides chocolatey, python2 and some visual studio libs to compile some node C++ extensions.

