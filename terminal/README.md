# Terminal

This primer contains a series of exercises to help you get familiar with the terminal on your system. Please note: I am writing this on a mac, so it will be oriented to the mac terminal experience. Much of what is here will translate well to linux, but it will take me some time to go back through it on Linux to catch discrepancies. This is not intended for Windows users.

### Getting Started

Download this repo to the home directory on your system. Examples in the repo will assume that it it in your home directory. If you'd rather put it somewhere else, that's fine, but you'll have to modify the example commads appropriately.

Use one set of the following commands to clone this repo and enter the directory containing it. Don't worry if these commands don't make sense right now. They will after you finish the [terminal](./terminal) primer. If you're not sure whether to use https or ssh below, use https.

1. If you are using __https__ with github:
    ```
    cd ~
    git clone https://github.com/gsarjeant/primers.git
    ls primers
    ```
    ![Clone Repo https](https://i.imgur.com/MCI3uvP.gif)
1. If you are using __ssh__ with github:
    ```
    cd ~
    git clone git@github.com:gsarjeant/primers.git
    ls primers
    ```
    ![Clone Repo ssh](https://i.imgur.com/jnayM6M.gif)

### What is a terminal?

A terminal is a text-based interface to your computer. It allows you to enter text commands at what is known as a __command line__. These commands can be used to do all sorts of tasks, from the simple to the sophisticated.

### Getting started

The terminal is an extremely powerful way to interact with your computer. As powerful as the terminal is, it can also be somewhat intimidating to first time users. When you open your terminal for the first time, you will see something like this:

![Default Mac Terminal](https://i.imgur.com/4o73QJY.png)

Fairly offputting. 

Perhaps the most difficult thing for people who are new to the terminal is simply learning how to find out how to do what you want to do. As always [Google can help here](https://www.google.com/search?client=firefox-b-1-d&q=basic+mac+terminal+commands), but let's walk through the fundamentals together.

### Replacing the default Mac terminal

The first thing to do on a Mac is stop using the default terminal. I recommend replacing it with [iTerm2](https://iterm2.com/). iTerm2 is a much more fully-featured terminal emulator for Macs. It will make your terminal experience better. Go ahead and grab it and then we'll start with the first exercise: [Shells](shells.md)

### Terminals and Shells

For a farily thorough and accurate description of the difference between a terminal and a shell, see [this post at the ubuntu forums](https://askubuntu.com/questions/506510/what-is-the-difference-between-terminal-console-shell-and-command-line?answertab=votes#tab-top)

For most purposes, it's accurate enough to say that a terminal (or more precisely, terminal emulator), is an application that allows you to enter input from your keyboard and see the results on your display. A shell is a program that runs inside a terminal that acts as the primary interface between you and the computer when working in a terminal. The shell defines your environment and allows you to run a variety of commands. Most modern shells also provide scripting languages that allow you to automate common tasks.

On OS X as of Catalina, the default shell is [zsh](http://zsh.sourceforge.net/). We'll discuss zsh in more depth later, but for now it's enough to know that when you open up a terminal in Mac OSX Catalina or later, you are working with zsh. 

__NOTE:__ Prior to Catalina, the default OSX was [bash](https://www.gnu.org/software/bash/). There are differences between zsh and bash, but for the purposes of this primer they are similar enough to be considered identical.

### Table of Contents

1. [Navigation](navigation/nav_1.md)
1. [Environment Variables](envvars.md)