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
	- `git config --global user.name "Daniel Moffat"`, Set your name (will be displayed against repository actions).
	- `git config --global user.email "daniel@everycick.com"`, Set your email.
	- (Optional) `git config --global core.editor "subl --wait"`, Set the editor for commit messages, by default this is `vi` / `vim`.

3. **(OSX / Linux only)** Modify `PS1` environment variable to include the git branch [screenshot](http://cl.ly/3t040w1d1H3k)
	- Clone this repo, `git clone https://github.com/danmofo/gayl-git.git`.
	- Copy `.bash_prompt` to the user directory, `cp gayl-git/scripts/.bash_prompt ~/`.
	- Add the following line to `~/.bash_profile`, `source ~/.bash_prompt`. 


Useful tools
===

- **octotree** [link](https://github.com/buunguyen/octotree), Google Chrome extension that greatly improves the GitHub repository browsing experience.

Useful links
===

Links I've used myself to learn all about Git

- CodeSchool's tryGit - https://try.github.io/levels/1/challenges/1
- Git handbook - https://git-scm.com/book/en/v2/Git-Branching-Rebasing
- Atlassian Git guide - https://www.atlassian.com/git/tutorials/what-is-version-control
