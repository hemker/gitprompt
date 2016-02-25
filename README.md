## Description

This simple bash script allows you to show the current branch in your prompt solely when you are in a git repository.  
If you have anything modified, the branchname will be coloured red, otherwise green.  
In case of any untracked files, the prompt shows a bold branchname. 

## Installation

Requirements: git-shell completion needs to be enabled/installed

Just copy the .bash_git to your homefolder and source it via .bashrc  
You can do so with: 

	echo "source ~/.bash_git\n" >> ~/.bashrc 


