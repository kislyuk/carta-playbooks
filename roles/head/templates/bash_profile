# /etc/skel/.bash_profile:
# $Header: /home/cvsroot/gentoo-src/rc-scripts/etc/skel/.bash_profile,v 1.10 2002/11/18 19:39:22 azarah Exp $

#This file is sourced by bash when you log in interactively.

[ -f ~/.bashrc ] && . ~/.bashrc

if [[ `who -m` ]] && [ ! $EUID == 0 ] ; then
	[ -z "$WINDOW" ] && screen -UxdR
fi
