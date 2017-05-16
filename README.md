# Merge Conflicts Aren't Scary 
![scary](screaming-woman-merge-conflict.jpg)

## Why is this happening to me?

Merge conflicts occur when two people are working on the same part of the same file because Git doesn't know which version is correct. This is an **awesome** opportunity for you to collaborate with another writer on your team to identify the best way to proceed. 

## Don't Fear the Conflict
Does `<<<<< 02383434` give you nightmares? You are not alone. But don't worry unlike scrimishes with your family on holidays merge conflicts are not hard to fix.

Take a deep breath we are going to help you learn to identify what git is telling you, how to fix the issue and how to bend git to your desired state.

## Reading a Conflict Message in the Terminal
![img](cli-merge-conflict.png)

## Identifying a Merge Conflict in your Document
![img](atom-merge-conflict.png)

So, lets look at this image and identify what it is telling us:

- `<<<<<<< HEAD`
  So, HEAD, is a pointer, that points to a **branch**, a **branch** points to the latest commit. So, HEAD is currently pointing to the latest commit in the `stats-update` branch.
- `=======`
  This is a seperator between the conflict that is occuring between the two branches.
- ` >>>>>>>>> gh-pages` or `>>>>>>>>>>>>>>>>>>>> a1f045`
  This is the branch that you are currently trying to merge into your branch that is causing the merge conflict to occur. This can sometimes display a random assortment of alphanumerical characters. This is in fact the SHA-1 hash associated with a commit and your computer **is not** breaking. 

## Aborting a Merge
Sometimes you may not want to deal with a merge conflict at all. If you have ever ran `git status` during a merge conflict you may have seen this line, `(use "git merge --abort" to abort the merge)`. Running `git merge --abort` undoes everything that the merge attempted to do and places you back into the state your project was in prior to the atempted merge.

## Fixing a Conflict


## Merge Conflicts on a Pull Request
