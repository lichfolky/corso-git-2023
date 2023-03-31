 
> Github (git hosting)

> Git

git init

> creiamo una repository / project

Workflow base add (staging), commit (messaggi), push (remote)

Copy (or clone) the repository to your local machine
Add a file to your local repo and "commit" (save) the changes

"Push" your changes to your main branch
Make a change to your file with a git hosting tool and commit

extra: Github Gists

> la tua prima repo

readme
markdown
.gitignore
branch
git status
git checkout <BRANCH-NAME>

"Pull" the changes to your local machine
Create a "branch" (version), make a change, commit the change
Open a "pull request" (propose changes to the main branch)
"Merge" your branch to the main branch

merge - risolvere conflitti


extra: Github Gists



# Header
The # indicates a Header. # = Header 1, ## = Header 2, etc.
* List item
A single * or - followed by a space will create a bulleted list.


**Bold item**
Two asterix ** on either side of a string will make that text bold.
- [ ] Checklist
A - followed by a space and [ ] will create a handy checklist in your issue or pull request.
@mention
When you @mention someone in an issue, they will receive a notification - even if they are not currently subscribed to
the issue or watching the repository.
#975
A # followed by the number of an issue or pull request (without a space) in the same repository will create a crosslink.
:smiley:
Tone is easily lost in written communication. To help, GitHub allows you to drop emoji into your comments. Simply
surround the emoji id with : .



 Undo changes using git restore, git revert, and git reset

html e img base
> sito con Github Pages

issues



 branch per main e dev

Le versioni major etc
feature, hotfix issue template
issue
extra: first good issue
fork
pull requests

ES:
forka il mio lavoro e fai una pull request

https://www.gitkraken.com/




 metodo con squash e rebase
pipeline CI/CD


 

https://www.youtube.com/watch?v=USjZcfj8yxE

https://www.youtube.com/watch?v=nhNq2kIvi9s


1 h
https://www.youtube.com/watch?v=8JJ101D3knE






???
head
https://www.udemy.com/course/git-and-github-bootcamp/
commit atomici
Amend
HEAD
Checkout


Git Revert
Git Reset

feature branching

rebase

tags






bitbucket:
https://www.atlassian.com/git



CONTRIBUTING.md



Untracked — a new file was added to the working tree but it’s not tracked by Git yet. You can start to track it by using git add command (see below).
Modified — the changes were made in the working tree but not yet staged for commit (in other words, these changes are not added to the current index).
Staged — the changes were added to the index. This way, they will become a part of the next commit.
Commited — the changes were added to the project history as a part of a commit. All commits are stored in the .git folder.



git push -u origin master
we’re taking the contents of the master branch and push it to the remote repository which has an alias origin.


https://git-scm.com/book/en/v2/Git-Basics-Undoing-Things

git log



git checkout master
git merge develop


rebase



Feature branching
Forking Workflow



git remote -v




### Documentazione e corsi

http://rogerdudler.github.io/git-guide/index.it.html
https://www.theodinproject.com/lessons/foundations-git-basics


## Articoli

https://lokalise.com/blog/10-git-commands-for-day-to-day-work/


### Games

un super gioco per verificare le proprie competenze
https://github.com/git-learning-game/oh-my-git

per allenarsi con i brach https://learngitbranching.js.org/   


https://skills.github.com/



### Risorse aggiuntive

https://github.com/github/gitignore

https://opensource.guide/
https://goodfirstissue.dev/
https://hacktoberfest.com/


`git config --global core.editor "code --wait"`

-----

TAG

git tag -a v1.4 -m "my version 1.4"


git tag
git tag -l "v1.8.5*" wildcard characters


https://git-scm.com/book/en/v2/Git-Basics-Tagging

BRANCH
- b
git branch --delete <branchname>

to push 

https://www.w3docs.com/learn-git/git-branch.html


FETCH
git fetch --all​

MERGE
Fast forward merge
 Best Practices

commit atomici
committa spesso
pull spesso

HEAD 
PULL
PUSH



https://github.com/sindresorhus/awesome
https://github.com/topics/js13k

`git config --global core.editor "code --wait"`

### Forzare sovrascrittura branch
git push origin dev --force

