# fantastic-fun
fantastic-fun

Github Tips:Regarding ```git rebase```  try following steps, it may be helpful

- ```checkout your branch : git checkout <your branch name>```

- ```run  git fetch && git rebase origin/master  it will fetch latest update from remote master (you may see the conflict at this stage in case your branch is behind)```
  
- ```resolve the conflict if you see```
  
- ```run git add .```
  
- ```run git rebase --continue```
  
- ```run git push --force-with-lease origin <your branch name>  --force-with-lease will check incoming changes while pushing the code. In case any incoming changes then fetch to update your local branch and push it again.```
  
- ```create PR.```
