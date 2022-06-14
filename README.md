# git_commad

**When if there is any commits issue then if you wish to rebase the branch with some specific commits**
1. git reset --hard 88b86acfbd04c86402ff304e9b5f5579788c7130
2. git push --force
3. git reset --hard origin/develop
4. if there is any specific commit you wanted to pick in your branch
   git cherry-pick 88b86acfbd04c86402ff304e9b5f5579788c7130
