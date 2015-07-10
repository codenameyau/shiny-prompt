shiny-prompt
============

![Screenshot of terminal](https://raw.githubusercontent.com/codenameyau/shiny-prompt/screenshot/screenshot/shiny-prompt.png)

###Prompt displays:
* a newline before each command
* the active python virtualenv
* the user and host information
* the timestamp of the command
* the shortened current directory
* the current branch of a git/mercurial repository
* the return value of the previous command (white=0, red=1)

###Installation

1. Save [`.bash_prompt`](https://github.com/codenameyau/shiny-prompt/blob/master/src/.bash_prompt) in your home directory
2. Add the following line to your `~/.bashrc`
```bash
. ~/.bash_prompt
```

Lastly open a new terminal.

###Legacy
Based on the work by woods and miki725.

Feel free to fork and create your own custom prompt.
