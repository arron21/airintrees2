+++
date = 2020-07-29T07:00:00Z
gallery = []
title = "Useful git Commands"

+++
**git config credential.helper store**

This saves your username and password for the project folder

**git  fetch -p**

this looks at all local branches on your computer, then compares it to the remote repository. if the branch no longer exists on the remote repository then you "prune" it. this is good for cleaning up "stale" branches

**git remote -v**

this shows your git urls that you are fetching and push to

**git remote set-url origin https://myawesomerepository.git**

this changes the git url that your fetch and push to