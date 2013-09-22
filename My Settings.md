My Settings
===========

Getting started with vim one can become overwhelmed with a lot of plugins and options that one doesn't know why it is even supposed to be interesting.

I'll try to answer that, and suggest the settings I use for begginers.


First bit of advice, is to start out with the following enhancement (imho the best)

Use Maximum-awesome-squared
---------------------------

Visit the following project and install by `cd`-ing into the directory and using the `rake` command.

https://github.com/tsironis/maximum-awesome-squared

## Command line installation drawn out:
```bash
git clone https://github.com/tsironis/maximum-awesome-squared
cd maximum-awesome-squared
rake
```

if you don't have `rake` then you try the following (using package manager for your distro)

```bash
sudo apt-get install rake
```


Maximum-Awesome-Squared requires Jellybeans colorscheme by default

http://www.vim.org/scripts/script.php?script_id=2555

You will need to copy the `jellybeans.vim` file into the `~/.vim/colors` directory.

You may need to make a `~/.vim/colors` directory if one doesn't already exist.


(for my students who are just starting out)
```bash
cd ~/.vim
mdkir colors
```

Useful Commands
===============


### Operations:


Before you can type, press `i`.  This will allow you to start to *insert* text into the file.
This is how to transition from **Normal Mode -> Insert Mode**

**Anymode to Normal Mode** -- use `Esc` key or use `cntl + [` the latter is highly recommended.

**Normal-Mode to Visual Mode** -- press `v` to select text with cursor (move around with arrow keys) or `Shift + v` to select lines straightaway.


### States:

Insert Mode -- you can type - yay!

Normal Mode -- can do seds and stuff

Visual Mode -- allows you to make a selection and do copying and further stuff to selection.

I use this for CopyPasta as well as for doing edits on a selection.
