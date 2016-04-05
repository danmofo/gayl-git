GAYL Git
===

Repository containing useful information and some dummy exercies for getting our team up to speed on Git.

Setup
===

First you need to download and install a few things:

1. Install Git
	- **Windows**, download Git Bash from [Git For Windows](https://git-for-windows.github.io/)
	- **OSX**, should already be installed on your system, verify with `git --version`. If it's not installed, grab it using [Homebrew](http://brew.sh).
	- **Linux**, todo: install from package manager?

2. Set some global git configuration, this applies to all git repositories (specify `--local` to change repository specific settings if you've already set some)
	- Set your name (will be displayed against repository actions), `git config --global user.name "Daniel Moffat"`
	- Set your email, `git config --global user.email "daniel@everycick.com"`
	- Set the editor for commit messages, by default this is `vi` on OSX / Linux / Git Bash.
		- Set the default editor to be Sublime Text 3 - `git config --global core.editor "subl --wait"`

3. **(OSX / Linux only)** Modify `PS1` environment variable to include the git branch [screenshot](http://cl.ly/3t040w1d1H3k): 

	`export PS1="\[[1m[91m\]\u \[[30m\]at \[[38;5;172m\]\h \[[30m\]in \[[38;5;190m\]\w\[[30m\]$([[ -n $(git branch 2> /dev/null) ]] && echo " on ")\[[38;5;141m\]$(parse_git_branch)\[[30m\]\n$ \[(B[m\]"`


Useful links
===

Links I've used myself to learn all about Git, would suggest the interactive tutorial at least.

- CodeSchool's tryGit interactive tutorial, 
- add stuff from Google doc

-- Testing Slack integration
