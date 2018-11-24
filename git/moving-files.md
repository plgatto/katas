# Moving a file to a new folder

## Kata
1. Create a new repo
2. Add a file and commit
3. Move the file into another folder
4. Commit changes


## Code
```bash
# 1. Create a new repo
mkdir kata-repo
cd kata-repo
git init
git config user.name "someone"
git config user.email "someone@someplace.com"

# 2. Add a file and commit
touch test.txt
git add test.txt
git commit -m "added test.txt"

# 3. Move the file into another folder
mkdir new-folder
git mv test.txt new-folder

# 4. Commit changes
git commit -m "moved test.txt to new-folder"
```
