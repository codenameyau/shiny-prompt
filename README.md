# shiny-prompt

![Screenshot of terminal](https://user-images.githubusercontent.com/3826772/67151641-f0c57780-f296-11e9-8ce4-0a19f5ce598d.png)

## Prompt features:
- displays the current directory as title
- displays the active python virtualenv
- displays the current branch of a git or mercurial repository
- displays the timestamp of a command
- displays the exit code of the previous command `$` as color (white=0, red=1)

## Installation

Download this file to your home directory. You can pick another prompt in src.

```bash
wget -N -O ~/.bash_prompt https://raw.githubusercontent.com/codenameyau/shiny-prompt/master/src/.bash_prompt
```

Add this line to your `.bashrc` (Linux) or `.bash_profile` (Mac)
```bash
echo "source ~/.bash_prompt" >> .bashrc
```

Lastly open a new terminal or source your `.bashrc`.
