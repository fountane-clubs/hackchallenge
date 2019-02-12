# hackchallenge

## Setting up the codebase

The candidate should take a pull from the master branch to start the challange.

```bash
git branch
*master 
```
If you are in any other branch then use this command in the Git Bash. 

```bash 
git checkout master
``` 
Then to get the latest code from the remote use:

```bash
git pull origin master
```
Once, you get the lastest code from the remote repo, then create a branch with your email address: 

```bash
git checkout johndoe@example.com
```

To check the current branch: 

```bash
git branch
  master
* johndoe@example.com
```

Build the code in the local repo and commit to the branch 

```bash 
git add <filename> 

git commit -m "Changes Made - Brief Note"

git push origin johndoe@example.com

```

## Submitting the challange

Once, the branch is commited and push to the remote repository then merge it with the Master branch with a Pull request: 

1. Go to the Repo "Navigation bar"
2. Select option "Pull Request" 
3. Now choose the branch as "johndoe@example.com" and target branch as "master" 
4. Click on Submit. 

For any questions email to Srivishnu Ayyagari at [ayyagarian@fountane.com](mailto:ayyagarian@fountane.com)
