This is entire git repo dedicated to a bash script that I like.

What it does

lets you run the command `mob` in your terminal which
- [if the session is not already running] creates a new TMUX session called funtime
- [if the session is already running] connects to the TMUX session called funtime

This is meant for mob programming sessions, for devs who are too lazy or incompetent to learn TMUX properly

Supported Systems
- Anything that has bash and has a ~/.bashrc file

Prerequisites
- tmux installed on your system

Guide
- pull this repo
- cd mob
- ./configure
- source ~/.bashrc
- mob
... and you're away!
