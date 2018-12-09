Linux CLI - manning the oligarchy 
=====================================

Thanks to the 
[Unix History Repo](https://github.com/dspinellis/unix-history-repo) we have
a copy of the man pages of System 7, from 1979. It's a piece of archieology  
that can help understand toda
start 

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
