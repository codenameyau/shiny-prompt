shiny-prompt
============

![Screenshot of terminal](https://raw.githubusercontent.com/codenameyau/shiny-prompt/screenshot/screenshot/shiny-prompt.png)

### Prompt features:
* displays a newline before each command
* displays the active python virtualenv
* displays the current branch of a git or mercurial repository
* displays the return value of the previous command in `$` (white=0, red=1)

### Installation

Download this file to your home directory. Pick one.

#### Features: git branch, mercurial branch, python venv
```bash
wget -O ~/.bash_prompt https://raw.githubusercontent.com/codenameyau/shiny-prompt/master/src/.bash_prompt
```

#### Features: git branch
```bash
wget -O ~/.bash_prompt https://raw.githubusercontent.com/codenameyau/shiny-prompt/master/src/.bash_prompt--git-only
```

#### Features: git branch, purple hostname
```bash
wget -O ~/.bash_prompt https://raw.githubusercontent.com/codenameyau/shiny-prompt/master/src/.bash_prompt--git-only-ssh
```

Add this line to your `.bashrc` (Linux) or `.bash_profile` (Mac)
```bash
echo "source ~/.bash_prompt" >> .bashrc
```

Lastly open a new terminal or source your `.bashrc`.
