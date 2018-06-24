---
layout: single
title:  "Session One Extended:  Math and Terminal"
date:   2018-06-19
categories: main
---

Hey guys! After talking to a few of you I wanted to make a screen cast going over terminal navigation and I also wanted to make a quick cheat sheet with the most useful commands

Before I start I want to reemphasize that a directory is the same thing as a folder.

| Command | Definition  | Purpose |
|----|---|---|
| cat [file] | Concatenate contents of file to screen | Useful to check what is in the file without opening it
| cd .. | Go Back one directory | Lets you go back one folder
| cd ../../ | Move 2 levels up | Lets you go back 2 folders
| cd [folder] | Change to a specific directory | When typing `ls` you must be able to see the desired directory before going into it
| cd | Change Directory | Goes back to the Home Directory no matter what folder you are in |
| cd ~ | Home directory, e.g. 'cd ~/folder in home directory/' | Makes navigating easier
| clear | Clear screen | When your screen gets cluttered this helps
| cp [file] [newfile] | Copy file to file | Copies all the contents of the desired file to a new one
| head -10 [file] | Displays the top (head) ten lines of the file | Useful to check what is in the file without opening it
| ls -R | List entire content of folder recursively | List all folders and files and all of its subfolders and files etc.
| ls -la | List detailed contents including hidden files | Tells you everything there is to know about whats in the folder
| ls | List Directories | Lists all directories in your current folder
| mkdir [dir] | Create new directory | Creates a new folder in your current directory
| mv [file] [folder] | Moves a file into a folder | If you need to move a file to a folder 
| mv [file] [new filename] | Renames a file | If you need to rename a file or folder
| open . | Opens the current directory | open the current directory you are in 
| open [file] | Opens a file | Open a file or folder in your current directory
| pwd | Full path to working directory | When you forget when you are at this shows you your full path 
| q | Exit Terminal | You can also type `exit`
| rm -rf [folder] | Remove a folder and all of its contents recursively | SUPER WARNING make sure you want to delete the folder and everything inside of it you will not be able to get it back!
| rm [file] | Remove a file | Warning make sure you want to delete the file you will not be able to get it back!
| sudo [command] | Run command with the security privileges of the superuser (Super User DO) | Make sure you know what the command does before prepending sudo to a command 
| tail -10 [file] | Displays the bottom (tail) ten lines of the file | Useful to check what is in the file without opening it
| touch [file] | Create new file | Allows you to create a new empty file 


Some general cool terminal navigation techniques 

| Command | Description|
|---|---|
| ⬆ | Displays last command typed you can press up again to see the command before that etc. |
| Ctrl + A | Go to the beginning of the line you are currently typing on |
| Ctrl + E | Go to the end of the line you are currently typing on |
| Ctrl + K | Clear the line after the cursor |
| Ctrl + L | Clear the terminal |
| Ctrl + U | Clear the line before the cursor |
| Ctrl + W | Delete the word before the cursor |
| TAB | Auto completion of file or command|
| nc towel.blinkenlights.nl 23 | One of the coolest commands there is |

<iframe width="854" height="480" src="https://www.youtube.com/watch?v=MsdjQqyzqEk" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>



If you need any clarification reach out to me on slack! 
 - Jeremiah Parrack


---

