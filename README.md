OSX/Linux CLI and its evolution
===============================

Thanks to the 
[Unix History Repo](https://github.com/dspinellis/unix-history-repo) we have
a copy of the man pages from one of Linux's ancient forefather -
the seventh version. 
![Unix Histroy](images/Unix_history-simple.svg)

The man pages are key as they define the system. When stallman and the other
GNUs set out to create a free Unix clone, they started by coding the libraries
and developing tools that work exactly as the commands defined in Unix's man.

```bash

man man
man -l version7/man1/cp.1
man -l version7/man1/tar.1
man -l version7/man1/find.1
man -l version7/man1/sh.1
man stdio # what makes an executable a unix command
curl wttr.in/tlv
man bash
/history exp
q
!! | head -7
man curl
/silent
n
q
curl -s !c:1-$ 
!! | tail -5
alias tlv="!!"
tlv
echo !! >> ~/.bashrc
tail !:$
# DARN! what's the "tlv" doing there?
ed ~/.bashrc
$p
$d
$p
w
q
!alias
echo !! >> ~/.bashrc
!tail
source !e:$
# Debian
man dpkg
/EX
q
dpkg -l
!! | wc
man apt help
# tools
man rclone
