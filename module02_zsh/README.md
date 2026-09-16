# ISM 3232 - Module 2: zsh Navigation and File Operations

## Commands Practiced

| Command        | What it does                                        |
| ---------------------------------------------------------------------|
| pwd            | Shows where you are right now                       |
| ls             | Shows which files/folders exist here                |
| ls -la         | Shows all files including hidden ones               |
| cd ~/ism3232   | Navigates to specified folder (ism3232)             |
| cd ..          | Jumps up one level                                  |
| cd ~           | Jumps home from anywhere                            |
| mkdir          | Creates a new folder                                |
| touch          | Creates a new file                                  |
| cp             | Copies while original stays                         |
| mv             | Renames while original goes away                    |
| cat            | Prints entire file                                  |
| rm             | Permanently deletes file, follow rm safety ritual   |
| code .         | Opens specified folder as VS Code Workspace         |

## AI Use Statement
I did not use AI for any part of this assignment. 

## Week 3: Virtual Environments and .zshrc 

This lab helped me understand what virtual environments are, their purpose, and how to create, activate, and verify them. I learnt commands and prompts such as venv, source .venv/bin/activate, which python 3, pip freeze, requirements.txt, .gitignore, and .zshrc. I also created nine aliases which have been expanded on below: 

| Alias          | Command         | Purpose                           |
| ---------------------------------------------------------------------|
| ll             | ls -la          | Shows all files                   |
| c              | clear           | clear terminal                    |
| py             | python3         | which python3 currently active    |
| gs             | git status      | shows git status                  |
| ga             | git add         | stages all changed/new files      | 
| gcmsg          | git commit -m   | creates a Git commit              |
| gp             | git push        | uploads changes to Git repository |
| gl             | git log--oneline| Git commit history in one line    | 
| tree2          | tree -L 2       | shows files/folders 2 levels deep |

