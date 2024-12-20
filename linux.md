# Linux CLI Tools

---

## Create, Copy & Move

### touch

- create files

### mkdir & rmdir

Make and remove directories

### mv & cp

- move or copy files and directories

---

## Simplification Utilities

### ip

Quick way to get your IP address and see all network connections.

- `brew install iproute2mac`
- `ip route show`
- `ip addr`

### host

Get host details for any URL.

- `host google.com`

### tree

- viewing directory structure: `brew install tree`
- `tree -L [number of levels]`

### .aliases

- stop typing so much

### history

- no need to scroll up to find the command you recently ran
- no need to re-type long commands
- `history` displays your numbered command history
- `![number from history]` gives you the command with that number
- `!gulp` gives you the last gulp command you ran
- `history | grep gulp` shows your history filtered to just `gulp` commands

---

## Finding & Displaying Information

### less

Read files and command line data from top to bottom.

- pipe lengthy `git status` output: `git status | less`
- pipe file contents for better readabililty: `cat file.html | less`

### grep

- find stuff
- useful in combination with other commands

### cat

- pull only the content you want out of a file
- push content into the system clipboard

---

## Advanced

### functions

- add variables to shortcuts

### scripts

- automate processes

## Libraries

- https://github.com/romkatv/powerlevel10k
- https://github.com/sharkdp/bat
- https://github.com/so-fancy/diff-so-fancy
- https://github.com/antonmedv/fx
- https://github.com/Peltoche/lsd
- https://github.com/cantino/mcfly
- https://github.com/orf/gping
- https://www.jedsoft.org/most/
- https://github.com/rakyll/hey
- https://httpie.io/docs/cli
- http://jonas.github.io/tig/
- https://github.com/ajeetdsouza/zoxide

---

#### Use Cases


**Moving Around**

- `/` (search forward)
- `?` (search backwards)
- `F` (enable tail -f like behvaior, Ctrl-C to break out of it)
- `v` (open file in $EDITOR for editing, defaults to vi/vim)
- `u` - up half page
- `d` - down half page
- `k` - scroll single line up
- `j` - scroll single line down
