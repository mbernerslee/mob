This is a git repo dedicated to allowing remote mob programming on your machine using ssh and tmux.
It has two features:

1. lets you run the command `mob` in your terminal which
- [if the session is not already running] creates a new TMUX session called funtime
- [if the session is already running] connects to the TMUX session called funtime

This is meant for mob programming sessions, for devs who are too lazy or incompetent to learn TMUX properly

2. lets you run the command `ssh_access [approve | revoke] keyname` in your terminal which
- approved or revokes ssh access to your machine searching your ~/.ssh/keys directory for a file named `keyname`. If found it adds / removes it from your ~/.ssh/authorized_keys file, thus adding or removing ssh access for that key
- you need to add keys to ~/.ssh/keys/ for this to work of course

Supported Systems
- Anything that has bash and has a ~/.bashrc file

Prerequisites
- tmux installed on your system
- ssh server

Guide
- pull this repo
- cd mob
- ./install
- source ~/.bashrc
- mob
... and you're away!

Uninstalling
- ./uninstall
