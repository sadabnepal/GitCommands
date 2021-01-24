# GitCommands
Useful git command for daily use

### Commands
 - git init
 - git add . (add all file)
 - git commit -m "meaningful comment"
 - git branch -M master  (Create master branch)
 - git remote add origin https://github.com/sadabnepal/GitCommands.git  (add remote url to local)
 - git push -u origin master  (push newly created master branch to remote)


 ### Show graphical representation of all log
  - git log --oneline --graph --decorate --all
  
 ### working with tag
  - git tag -a v0.1 -m "meaningful comment" COMMIT_ID  (creates tag locally)
  - git push --tags (push all created tags to remote)

