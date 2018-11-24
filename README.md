# Code katas
* [Basic Git](#basic-git)

## Basic Git

### Kata
1. Create a repo
2. Commit some changes
3. Create new branche from repo
4. Commit some changes
5. Merge the branch into master
6. Delete the branch

### Code
```bash
# 1. Create a repo
mkdir kata-repo
cd kata-repo
git init
git config user.name "someone"
git config user.email "someone@someplace.com"

# 2. Commit some changes
touch test.txt
git add *
git commit -m "first commit"

# 3. Create new branche from repo
git checkout -b new-feature master

# 4. Commit some changes
echo test > test.txt
git commit -m "new feature"

# 5. Merge the branch into master
git checkout master
git merge new-feature

# 6. Delete the branch
git branch -d new-feature
```
