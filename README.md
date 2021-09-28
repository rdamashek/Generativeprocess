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
This guide assumes that you are essentially new to computer science and coming at this from ground zero. It is consequentially verbose and many of the steps are a one time process enabling you to set up your local environment. 

This guide was written based on the Windows installer as it was the use case we were working through, though Mac and Linux are probably very similar - if thats what you have and find any discontinuities, your encouraged to record the details and/or ping a peer within our group that can help (Josh for now). If you are using one of these operating systems, it would be great if you can help correct any inaccuracies - contributions in this way are very welcome. 

#### Installing Git (one time thing)
- Download and install Git from the following link: https://git-scm.com/downloads
	- If you are on a Mac you can optionally open up a terminal and type `brew install git`. This has advantages to an installer that will become apparent later in your journey if you choose to keep learning the inner workings of your machine (dotfiles). Either option is fine for now though, and the link is probably easier if your fresh.
- It will open up a wizard with many confusing options, safe options are documented. If you know what you are doing, feel free to select alternatives. If you don't just tick these boxes and you should be fine. This guide assumes you may contribute to other projects in the future and so recommendations take this into account. You can always change your configuration at a later date.
- Editor: Any, you will not use them for our purposes. VScode is recommend as an editor for junior developers, but this is not installed on your computer by default. Nano is a safe option.
- Branch naming: Select override and call it `main`
- Path dependencies: Git from command line and also third party software"
- SSH: bundled SSH
- HTTPS Transport back end: Use open SSL libraries
- (Windows install) Configuring line ending conversionss: "Checkout windows style, commit unix style line endings". This is probably MacOS when installing on a Mac, Linux for linux. 
- (Windows install) Configuring the Terminal emulator: "Use windows console window". On Mac this is probably "Use macOS Terminal".
- Default behaviour of Git pull: "default; fast forward or merge".
- Credential helper: "Git credential manager core"
- Enable file system caching: Yes.
- Enable symoblic links: No.
- Experimental options: None.
- Select install to finish the installation. 

#### Using Git and Github to download files
Assuming that you have a Github account as instructed in the General section please go to the repo where the notes are stored: https://github.com/SoCoDoJo/Generativeprocess

- Find the button in the top right corner of Github named "Fork" and click it to make a copy of the files to your own profile. This will become your own space. 
	- If asked if you want to fork the repository or branch, select repository. You want the whole thing.
- This should take you directly to the copied repo on your own page. If it doesn't go there.
- Find the green "code" button near the top right hand side and click it.
- You'll see a link an

- Open up a "Shell":
	- On Windows this is called a command prompt. You can do this by typing "Command Prompt" into the search bar. 
	- On Mac this is called the terminal. It can be found in the following directory : apps>utilities>terminal (or by seraching "Terminal" in Spotlight)
- Leave this running in the background. You'll use it a bit later.






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