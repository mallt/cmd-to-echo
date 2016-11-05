[![License GPL 3][badge-license]](http://www.gnu.org/licenses/gpl-3.0.txt)

## cmd-to-echo for emacs
Show the output of long-running commands in the emacs echo area.

<p align="center">
<img src="https://raw.github.com/mallt/cmd-to-echo/master/cmd-to-echo.gif" alt="cmd-to-echo screencast"/>
</p>

## Installation
cmd-to-echo is available as a MELPA package: <kbd>M-x</kbd> `package-install` <kbd>[RET]</kbd> `cmd-to-echo` <kbd>[RET]</kbd>

## Usage
- Call the cmd-to-echo function: <kbd>M-x</kbd> `cmd-to-echo` <kbd>[RET]</kbd>
- Enter the command to run
- Enter the options for the command (optional)
- If you want to stop a process started with cmd-to-echo, you can kill it by calling the cmd-to-echo-kill-process function and selecting the process from the list: <kbd>M-x</kbd> `cmd-to-echo-kill-process` <kbd>[RET]</kbd>

[badge-license]: https://img.shields.io/badge/license-GPL_3-green.svg
