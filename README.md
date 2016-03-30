GAYL Git
===

Setup
===

First you need to download and install a few things to get Git on your system make your life easier.

1. Install Git
	- **Windows**, download Git Bash from [Git For Windows](https://git-for-windows.github.io/)
	- **OSX**, should already be installed on your system, verify with `git --version`. If it's not installed, grab it using [Homebrew](http://brew.sh).
	- **Linux**, todo: install from package manager?


2. **(OSX / Linux only)** Modify `PS1` environment variable to include the git branch (todo: fix): 

	`export PS1="\[[1m[91m\]\u \[[30m\]at \[[38;5;172m\]\h \[[30m\]in \[[38;5;190m\]\w\[[30m\]$([[ -n $(git branch 2> /dev/null) ]] && echo " on ")\[[38;5;141m\]$(parse_git_branch)\[[30m\]\n$ \[(B[m\]"`


Useful links
===

- CodeSchool's tryGit interactive tutorial, 
- add stuff from https://docs.google.com/document/d/1o0ve-lDe8zu0u3OVMJEQrQV5TPG9TybJ4QbGb1su6q8/edit
