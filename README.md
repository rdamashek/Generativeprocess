# README

This note explains how to interact and callaborate on our Generative Process, stored as linked markdown files within an Obsidian Vault. 

## General
- Go to Github.com and sign up for a new account, if you don't already have one.
- The group work is stored as a repository under the Org "SoCoDoJo": https://github.com/SoCoDoJo
- The repo on this org that we are working from is called "Generativeprocess": https://github.com/SoCoDoJo/Generativeprocess

### If you do NOT have git installed
- Install `git` from this link: https://git-scm.com/downloads
	- If prompted for an editor, it doesn't matter for our purposes
	- When asked about naming branches; select override and call it `main`
	- When prompted about path dependencies select the option "Git from command line and also third party software"
	- Bundled SSH
	- Choosing HTTPS transport back end: Use open SSL libraries
	- Configuring the line ending conversions: Checkout windows style, commit unix style line endings
	- Configuring the Terminal emulator: Use windows console window
	- Default behaviour of Git pull: default, fast forward or merge.
	- Credential helper: Git credential manager core
	- Enable file system caching: Yes
	- Enable symoblic links: No
	- Experimental options: None
	- Install 
%%
- If you have a Mac with Homebrew installed you can type `brew install git` and it will get hold of what you need and run the installation. 

- On Windows open up the app "command prompt" by typing this into the search bar
- On Mac open up a terminal by going into apps>utilities>terminal
%%

- On Github find the button in the top right corner named "Fork" and click it.
	- If asked about repository or branch select repository
- Now go to the repo on your personal page 
- Find the green "code" button
- Copy the address
- Go to your command prompt/terminal and `cd` to the folder you want to download into.
- Type `git clone *paste copied link*`
- If you have an error here, you probably just need to reopen your terminal

%%
Alex got an error saying 
```
error: invalid path > How money index
fatal: unable to checkout working tree
warning: Clone succeeded, but checkout failed.
```
The cloned folder was also empty

- `dir` for pc list contents

%%

