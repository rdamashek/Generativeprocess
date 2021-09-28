# README

This note explains how to interact and callaborate on the Generative Process within Obsidia.

## General Information
If you don't already have a Github account, please sign up for one. This will allow you to create a copy of the information and modify it without worrying that the edits are permanent. You will also need to install Git if you do not alread have it. Instrutions on this process are below.

### Quick start
Content is stored at the following loctations
- The Org is called "SoCoDoJo": https://github.com/SoCoDoJo
	- This a place where other artefacts besides Obsidian can be stored
- The repo called "Generativeprocess" is an Obsidian vault and contians all the notes from C1: https://github.com/SoCoDoJo/Generativeprocess

Forking the repo to your own profile is best practice. Updates made there will not affect anyone else unless a pull request is made to the org, at which point modifications you have made can be integrated. 

### Detailed setup
This guide assumes that you are new to computers and essentially coming at this from ground zero. It is consequentially verbose and many of the steps are a one time process enabling you to set up your local environment. 

#### Installing Git
- Download and install Git from the following link: https://git-scm.com/downloads
- It will open up a wizard with many confusing options, safe options are documented. If you know what you are doing, feel free to select alternatives. If you don't just tick these boxes and you should be fine. This guide assumes you may contribute to other projects in the future and so recommendations take this into account. You can always change your configuration at a later date.
- Editor: Any, you will not use them for our purposes. VScode is recommend as an editor for junior developers, but this is not installed on your computer by default. Nano is 


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
... it was because of question marks
- `dir` for pc list contents
%%

- Open up Obsidian
- In the left ribbon click "Open another vault"
- "Open folder as vault"
- Select the vault you just downloaded


- In the left hand ribbon select "Settings" > "Community Plugins"
- Turn off safe mode
- Click browse
- Search for "Obsidian Git"
- Click Install
- In the community plugins tab scroll down and click the switch to turn on "Obsidian git"
- Set preferences in the plugins settings

- Authorise git for obsidian when it makes the first backup