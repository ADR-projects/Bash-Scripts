# Bash-Scripts

Bash scripts to automate some of my daily tasks.

---

## Table of contents
-[To-do list](#to-do-list)

---
## Current Scripts

### To-do list

A simple Bash to-do list script that:
* Creates a new `.txt` file or uses an existing one.
* Lets you **add**, **delete**, and **view** your chores.
---
#### Preview
<img src="public/todo.png" width="550" height="400"/>

#### Usage
Clone the repo or download the todo.sh file.
It is recommended that you create a new directory for todo.sh as well as the actual to-do lists, for simplicity.

In your home folder,
```bash
mkdir todos            # create a new dir for todo.sh and also to-do lists.
mv ~/Bash-Scripts/todo.sh ~/todos/todo.sh # if you have cloned the repo in home folder (~/)
cd todos

chmod +x todo.sh       # make it executable
./todo.sh help         # show help/usage
./todo.sh -a           # add a chore (interactive)
./todo.sh -l           # view chores list
./todo.sh -d           # delete a chore (interactive)
```

The script will prompt you to create or select a to-do file on first run.
