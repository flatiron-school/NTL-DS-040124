# NTL-DS-040124's Cohort Repository!

A repository for all lectures, reviews, and other resources for the Flatiron School's Live Data Science 040124 Cohort.

![cool data graphic from gihpy](https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExd2tmZDFtcnc5ZWUzeHFqeTZsMmx4Mnhyajd6cXNhZ3k2MTVtOWhwdiZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/3oKIPEqDGUULpEU0aQ/giphy.gif)

## Written Instructions to Connect to this Repository:

**We will be going through these instuctions several times during the first week or so of class - no rush!**

1. FORK this repository, creating a copy on your own GitHub account

2. Then clone your fork down to your local computer
```
git clone https://github.com/[yourusername]/NTL-DS-040124.git
```

3. Add the original non-forked `/flatiron-school/` version as the remote `upstream` within your local forked clone, this will allow you fetch/pull future material
```
git remote add upstream https://github.com/flatiron-school/NTL-DS-040124.git
```

4. You can make changes to the notebooks now! Remember to push your changes to your forked version of the repo (to put your local changes up online and save any notes):
```
git add [filename]
git commit -m 'message here'
git push origin main
```
### I would encourage everyone to push daily!

### Whenever you want to get newly added material (will be announced):

5. Grab the changes from the upstream remote repo
```
git fetch upstream
```

6. Merge new changes onto your local repo
```
git merge upstream/main -m "meaningful message about what you're updating"
```