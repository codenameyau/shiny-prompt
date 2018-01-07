shiny-prompt
============

![Screenshot of terminal](https://raw.githubusercontent.com/codenameyau/shiny-prompt/screenshot/screenshot/shiny-prompt.png)

### Prompt features:
* displays a newline before each command
* displays the active python virtualenv
* displays the current branch of a git or mercurial repository
* displays the return value of the previous command in `$` (white=0, red=1)

### Installation

Download this file to your home directory.
```bash
wget -P $HOME https://github.com/codenameyau/shiny-prompt/blob/master/src/.bash_prompt
```

Add this line to your `.bashrc` (Linux) or `.bash_profile` (Mac)
```bash
echo "source ~/.bash_prompt" >> .bashrc
```

Lastly open a new terminal or source your `.bashrc`.
