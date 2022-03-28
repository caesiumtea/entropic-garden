# git review
tagged: #git #github #commands 

## the basic workflow:
1. *stage* the changes that you want to commit/push - this doesn't permanently affect your repo yet 
2. *commit* the staged changes to make them part of the version history
3. (if using a remote platform) *push* the new commits to the remote repo

## git commands
### config
- first of all, when you're just setting up git on a new machine, you're gonna have to run these two config commands before it lets you do much networked stuff, so next time we might as well just do it right off the bat:
	-  `> git config --global user.email "[ur cool email]"`
	-  `> git config --global user.name "[ur nifty name]"`
	- however! if you wanted to use a different name or email just for a certain repo, then you could run those commands inside that repo *without* the `--global` flag 
### git init
- create a git repo by running  `> git init`  in the relevant folder
### git add
- stage changes with   `> git add`
	- to stage the entire working directory, which is probably what we'll want to do is most cases?, make that  `> git add .`  (a period at the end)
	- the period just means "current directory" afaik - and naming the whole directory implicitly means "everything in it", i think?
### git status
- after staging, run a quick  `> git status`  to double check what you're about to commit and what branch you're about to commit it to
### git rm
- made an oops? pull a file back off the stage with  `> git rm --cached [file]`
	- if it's a whole folder you want to take out, then it's `> git rm -r --cached [dir]` , where `-r` means *recursively* go through that folder to clear it all out
		- i actually don't know what purpose the `--cached` flag serves here, or how  `git rm`  would behave without it; it's just the command that the git CLI itself said to use
### git commit
- okay so once that's all sorted it's finally time to commit!!! ✨ do that with `> git commit -m "[some commit message]"`
	- the `-m` flag is for *message*, and should be directly followed by your commit message, written between quote marks
	- btw, I think one of the tutorials or something I skimmed today said the max length of a commit message is *50 characters*
### git remote add
- okay now before you can push your repo to github or wherever else, you gotta tell it where it's going!!
- `> git remote add [what you wanna call the remote source] [where it is]`
- e.g. `> git remote add origin https://github.com/caesiumtea/entropic-garden.git`
- "origin" appears to be the standard name recommended by github, but afaik it doesn't *have* to be called that, like git itself doesn't care what you call it 
### main
- for github in particular, they also suggest running  `> git branch -M main` which renames your starting branch from `master` to `main`
	- the `-M` flag on  `git branch`  means rename (to whatever term comes after it of course) ......but like. why the letter M???
- i only skimmed realllll briefly on this one, but i think it looked like the reason this matters is just that you need to make sure your local system and remote system will agree about what to call your branches... and git and github just happen to disagree on their defaults. BUT, once again there's nothing *innately* special about the names "main" or "master" - it's just github telling you to use their particular convention.
- btw, this command won't work until *after you've made a commit* in the repo. (how come?)
### git push
- annnnd finally, with everything set up, we can `git push` !!
- run  `> git push -u origin main` 
- of course, `origin` will actually just be whatever name you assigned to your remote repo using the `git remote` command above, and if your branch is called something other than `main` then you'll type that branch name instead!
- so in other words it's like, `> git push [name of remote repo] [name of branch you're pushing]`
- `-u` is optional, but it tells git to set `origin main` as the default destination for the next time you push this repo, so that you don't need to keep typing it each time: you can just run  `> git push`  without any extra arguments and it'll go to that branch again.