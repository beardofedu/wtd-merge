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


## Fixing a Conflict
We have fantastic <a href='https://help.github.com/articles/resolving-a-merge-conflict-using-the-command-line/' target='_blank'>merge conflict resolution steps in our help docs</a>.

## Merge Conflicts on a Pull Request


## Exercise 
The repository for example merge conflicts can be found here: https://github.com/beardofedu/wtd-games

### Simple Merge Conflict
1. Fork the `wtd-games` repo from https://github.com/beardofedu/wtd-games
1. Clone the project locally.
1. `cd` into the repository and checkout the **stats-update** branch using: `git checkout stats-update`
1. Run `git merge gh-pages` and you will encounter a merge conflict.
1. Open the **index.html** file in your favorite text editor. 
1. Lines **14-18** will have a merge conflict.
1. Select which color you want the score to be and remove the excess code. You should be left with a single line of code that looks like this: `#score    { color: yellow; font-weight: bold; vertical-align: middle; }`
1. In the command line, enter `git add index.html`
1. In the command line, enter `git coommit` 
1. Celebrate your victory over the merge conflict!

## Advanced Merge Conflict
1.
1. 
1.
1.
1.
