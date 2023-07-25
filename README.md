# my-utils

Bash utils to be a little quicker in the terminal.

Alias `workon` opens a new Finder window from the current folder and installed Visual Studio Code Alias `cpwd` copies the current full folder path to the clipboard.
Alias `hqroutes` add the networks to all subnets at Boffins HQ.

## Prerequisites

1. is vim installed `whereis vim`
2. is pwd installed `whereis pwd`
3. is pbcopy installed `whereis pbcopy`
4. Visual studio shell commands installed `code --version`

## Deploy

To install my-utils to your local computer.

1. `vim ~/.zshrc`
1. press "i" to activate insert mode
1. add `alias workon=". /<path to this repo root>/workon"`
1. add `alias cpwd=". /<path to this repo root>/cpwd"`
1. add `alias hqroutes=". /<path to this repo root>/hqroutes"`
1. Press `esc` to exit the edit
1. Press`:wq` to write and quit Vim
1. open a new terminal window and test the commands
