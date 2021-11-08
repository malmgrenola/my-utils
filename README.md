# my-utils

Bash utils to be a little quicker in the terminal.

Alias `workon` opens a new Finder window from the current folder and installed Visual studio Code
Alias `cpwd`copies the current full folder path to clipboard.

## Prequisites

1. is vim installed `vwhereis vim`
2. is pwd installed `whereis pwd`
3. is pbcopy installed `whereis pbcopy`
4. Visual studio shell commands installed `code --version`

## Deploy

To install my-utils to local computer.

1. `vim ~/.zshrc`
2. press "i" to activate insert mode
3. add `alias workon=". /<path to this repo root>/workon"`
4. add `alias cpwd=". /<path to this repo root>/cpwd"`
5. press `esc` to exit edit
6. press `:wq` to write and quit vim
7. open a new terminal window and test the commands
