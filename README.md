**git checkout --track origin/branchname**  
Switch to "branchname", like expected. (creates a new local branch, but will be merged on commit/push?). Useful if you want to continue work on a remote branch.  
  
**git fetch origin**  
Fetches all the new stuff from origin, but keeps HEAD and the working tree untouched.
  
**git push origin branchname**  
Pushes the branch into origin, creating it if it doesn't exist yet
