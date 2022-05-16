#Git
#Guide/Git
#Obsidian


# Push Obsidian vault to github

How to push [[Obsidian Vault]] into [[github]].

1. Log into [[github]], and create the new repo
- Make sure not to select the README and description.
	- Can do this after it is up n running.

2. Go into your terminal, and cd into the project (vault) folder.
3. Set it up doing this.
	- git init
	- git commit -m "first commit"
	- git remote add origin <mark style="background: #BBFABBA6;">(path given in the github page)</mark> 
	- git branch -M master
	- git push -u origin master
4. Refresh the webpage, and it should be there.

