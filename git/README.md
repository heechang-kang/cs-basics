# Git

### source
- [backlog.com, korean](https://backlog.com/git-tutorial/kr/intro/intro1_1.html)
- [git visual cheatSheet](https://ndpsoftware.com/git-cheatsheet.html#loc=workspace;)
- [git-scm book korean](https://git-scm.com/book/ko/v2)
git stash add commit push
git pull

### Content, notes
- branch
- basics

webhooks


## Branch
[git branching-model](https://nvie.com/posts/a-successful-git-branching-model/)

--> IntegrationBranch, TopicBranch

HEAD\
(for location) :: ~ : tilde(go back),, ^ : caret(new suggestion)\
git checkout __ : making new branch

git merge\
- git fast-forward : no change in master so just merge them
- when master is changed : merge commit

git rebase : merge commit but integrate the branches

#### typs of branches
according to successful git-branch-model

- main(master, develop), feature(integrate with develop), release, hotfix(quick)




## Basics

Stash - Workspace - Index(stage) - LocalRepo -- UpstreamRepo(remote)
