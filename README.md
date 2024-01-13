# Hi Eng.Ahmed! 

## Deleting branches:

### To delete a branch locally 
```bash
    git branch -d branchName
```

Note this will delete the branch locally only but it will still be available on GitHub

### Deleting The branch remotely:
```bash
git push origin -d branchName
```
### Tagging the current commit: 
#### This is a lightweight tag
```bash
git tag v1.7
```
### Push the tag to main:
```
git push origin v1.7
```
### List all tags:
```bash
git tag
```

### Delete local tag: 
```bash
git tag -d v1.7
```
### Delete remote tag:
```bash
git push origin -d v1.7
```
