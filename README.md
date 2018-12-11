OSX/Linux CLI and its evolution
===============================

Thanks to the 
[Unix History Repo](https://github.com/dspinellis/unix-history-repo) we have
a copy of the man pages from one of Linux's ancient forefather -
the seventh version. 
![Unix Histroy](images/Unix_history-simple.svg)

The man pages are what defines the system. All executables, system & library calls, special files, file formats and sys admin commands are well defined in the man. When stallman and the otherGNUs set out to create a free Unix clone, they started by coding the libraries
and developing tools that work exactly as the commands defined in Unix's man.

This repo contains a copy of System 7 man pages from 1979. 

The chars below where typed in a presentation in PyWebIl #78 in Tel aviv, exploring the evolution of the shell:

```bash

$ man man
$ ls version7/man1
$ man -l version7/man1/cp.1
$ man -l version7/man1/tar.1
$ man -l version7/man1/find.1
# stdio is the API that all commands share
$ man stdio 
$ curl wttr.in/tlv
$ !! | head -7
# FAIL! the progress bar kills the pipe
$ man curl
/silent
n
q
$ curl -s !c:1-$ 
$ !! | tail -5
$ alias tlv="!!"
$ tlv
$ echo !! >> ~/.bashrc
$ tail !:$
# FAIL! what's the "tlv" doing there?
$ ed ~/.bashrc
$p
$d
$p
w
q
$ !alias
$ echo !! >> ~/.bashrc
$ !tail
$ source !e:$
# Debian
$ man dpkg
/EX
q
$ dpkg -l
$ !! | wc
$ man apt help
# tools
$ man rclone
...
