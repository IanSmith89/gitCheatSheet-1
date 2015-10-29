## Cheat Sheet

Whenever you're confused about git, come read this cheat sheet. Remember that all git commands can be run with the `--help` option. For example:

`$ git branch --help` or `$git log --help`

### Essential Git Commands

####Create a new git repository
`$ git init` - Create a new, local repository

#### Repo Status
`$ git status` - Check the status of your current repository and see which files have changed.

`$ git diff` - Show changes between commits, commit and working tree, etc.

#### Repo History
`$ git log` - Show commit logs.

`$ git log --oneline --decorate --color --graph --all` -
--oneline: compacts log info to one line
--decorate: prints out ref names of any commits that are shown
--color: shows color difference
--graph: draws a text-based graphical representation of the commit history on the left hand side of the output
--all: pretend as if all the refs in refs/ are listed on the command line as <commit>

`$ git log -p [filename]` -  Show commit logs

#### Stage files to commit
`$ git add <filename>` - Add file contents to the index/stage

`$ git add -A` - automatically stage all tracked, modified files before the commit

#### Commit changes in staged files
`$ git commit -m "<commit message>"` - Record changes to the repository.

#### Branching
`$ git branch <branch name>` - Create or delete specified branch.

`$ git branch` - List, create, or delete branches.

`$ git checkout <branch name>` - to create a new branch

#### Merging

`$ git merge <branch name>` - put branch changes together in master
