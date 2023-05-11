# Using Git

## Why?
- To keep track of changes
- Your computer may explode, but your code will be secure in the cloud
- To colaborate with others
- If you ever make mistakes and need to return to a version that worked, or 
want to see what changed from one version to another.

## Basic terms
### Git
To keep it simple, it's a program to keep track of files and versions

### GitHub
A commercial offering that uses git. You can use it for free too (with some limits)

### Repository
Is where you store your files. Like a storage in the cloud for code. 

### Commit
When used as noun, it refers to a snapshot of the files at certain time. When used
as a verb, it is the act of creating such snapshot.

### .gitignore
A file where you can define which files you don't want to upload.

### README.md
This file typically has a welcome message or some information about your project
in a special format called markdown. This file is a README.md

## Basic commands
To download a project from a repository
```
git clone [the URL to your repository. like https://github.com/user/project.git]
```
To pull (download) the latest changes from the main repository
```
git pull
```
To see if you have new files, which files have changed since your last commit, etc
```
git status
```
To add your changes locally. Note that this does only adds them to a "bundle", 
but does not really create a version. Why? because maybe you want to create a snapshot (commit)
with only a few files, then another snapshot, etc.
```
git add [name of file, or . for all in this directory]
git add .
git add newfile.txt
```
To commit your changes locally (create the snapshot)
```
git commit -m "Put a message here that describes the changes, like, created feature x, or fixed bug y"
```
You can combine add all and commit at the same time (note that this does only adds changes to files
that you added in the past
```
git commit -am "your message"
```
To push (upload) your changes to the repository
```
git push
```

## Common pitfalls
Git tries to keep things tidy. If you try to upload your changes but someone already uploaded something
(that someone could be you, working in the GitHub page), you'll need to pull their changes first

## Notes:
Git has more capabilities, and some of the explanations here are simplified versions. 
We won't be using the advanced capabilities
The first time you use git locally, it will refuse to push your changes until you configure your name
and email. The instructions are in the error message

