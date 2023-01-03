## Console notes
- mkdir `-- repository`
- cd `--repository`
- git init
- touch `readme.md` `-- File cration`
- git add `.` oder `readme.md`
- git status
- git commit -m “Add readme.md”
- git log
- git status
- git config –global user.name “Your Name” --`first time only`
- git config –global user.email you@email.com --`first time only`
- git pull `link from github` -- for a coppy of proitect to begene
- git log --graph –decorate ‘– online’
- git remote add origin ‘server’
- git checkout -b create
- git branch `-d delete` delete the branch
- git branch `name of branch` to work on branch
- git merge ‘to master’
- git commit -a “Commit and add all file”
- 
- git status 
- nano readme.md
- git commit -a = --all
- git commit -am “Git Commands added”

## Comands

- mv `– move `
- cp `– copie`
- cd `– direktory`
- rm `– remove`
- rm -rf `- remove directory force`
- nano `– text editor`
- mkdir `– directory creator`
- pwd `– directory check`

## github with SSH

- ssh-keygen -t rsa -b 4096 -C “email@example.com” – create
- ssh-keygen -t rsa -b 4096 -C – decode external ssh
- /home/user/.ssh/ssh_dresca – location for shh key’s
- ssh-add – ?? to save


## These are common Git commands used in various situations:

## start a working area (see also: git help tutorial)
   - clone   --  `Clone a repository into a new directory`
   - init    --  `Create an empty Git repository or reinitialize an existing one`

## work on the current change (see also: git help everyday)
   - add    --   `Add file contents to the index`
   - mv      --  `Move or rename a file, a directory, or a symlink`
   - restore  -- `Restore working tree files`
   - rm    --    `Remove files from the working tree and from the index`

## examine the history and state (see also: git help revisions)
   - bisect  --  `Use binary search to find the commit that introduced a  bug`
   - diff    --  `Show changes between commits, commit and working tree, etc`
   - grep   --   `Print lines matching a pattern`
   - log     --  `Show commit logs`
   - show   --   `Show various types of objects`
   - status  --  `Show the working tree status`

## grow, mark and tweak your common history
   - branch  --  `List, create, or delete branches`	
   - commit  --  `Record changes to the repository`
   - merge  --   `Join two or more development histories together`
   - rebase  --  `Reapply commits on top of another base tip`
   - reset   --  `Reset current HEAD to the specified state`
   - switch  --  `Switch branches`
   - tag    --   `Create, list, delete or verify a tag object signed with GPG`

## collaborate (see also: git help workflows)
   - fetch   --  `Download objects and refs from another repository`
   - pull   --   `Fetch from and integrate with another repository or a local branch`
   - push  --    `Update remote refs along with associated objects`
