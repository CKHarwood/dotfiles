# dotfiles
Dotfiles are stored here and hard linked to the appropriate path directories where possible. In some cases it is necessary to copy files over and keep them in sync manually.

## .bashrc
`~/.bashrc` (hard-linked to this file)

**Bash r**un **c**ommands in startup. Most changes are documented in the file. A few personal changes documented below. 

This file may be over-customized for WSL today, but since I do not currently have a non-WSL Linux environment I have not made a separate file for a vanilla bash environment.

### Custom aliases and commands set in `.bashrc`

* `ll`: List all files in the present working directory in long format, with forward slashes indicating subfolders (`ls -alF`)

* `la`: List all files in the present working directory (`ls -a`)

* `l`:  List visible files in the present working directory by column, with forward slashes to indicate subfolders (`ls -CF`)

* `gitlog`: Print a pretty git log.

#### Windows Subsystem for Linux (WSL) aliases

* `cdc`: `cd` into Windows `%userprofile%` folder

* `cdp`: `cd %userprofile%/Projects`

* `cdd`: `cd %userprofile%/Downloads`

## .dircolors
In my .bashrc, the dircolors command sets up color output for ls and grep. The colors settings are stored in ~/.dircolors. Hard link: ~/.dircolors. 

## MYVIMRC

* `.vimrc-WSL`: Startup run commands for vim in a Windows Subsystem for Linux (WSL) command-line environment
* `_vimrc-Win`: Startup run commands for gVim in Windows

