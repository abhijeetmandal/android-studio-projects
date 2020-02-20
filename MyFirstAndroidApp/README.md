# Android tutorial

Documentations

## GIT commands

git init , add , commit , add remote , push

```AppleScript
Abhijeets-MacBook-Air:AndroidStudioProjects abhijeet$ pwd
/Users/abhijeet/AndroidStudioProjects
Abhijeets-MacBook-Air:AndroidStudioProjects abhijeet$ git init
Initialized empty Git repository in /Users/abhijeet/AndroidStudioProjects/.git/
Abhijeets-MacBook-Air:AndroidStudioProjects abhijeet$ git add README.md
Abhijeets-MacBook-Air:AndroidStudioProjects abhijeet$ git commit -m "adding README.md template"
[master (root-commit) 7133ca9] adding README.md template
 1 file changed, 88 insertions(+)
 create mode 100755 README.md
Abhijeets-MacBook-Air:AndroidStudioProjects abhijeet$ git remote add origin https://github.com/abhijeetmandal/android-studio-projects.git
Abhijeets-MacBook-Air:AndroidStudioProjects abhijeet$ git push -u origin master
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 1.20 KiB | 617.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0)
To https://github.com/abhijeetmandal/android-studio-projects.git
 * [new branch]      master -> master
Branch 'master' set up to track remote branch 'master' from 'origin'.
```

avoid add remote again

```AppleScript
Abhijeets-MacBook-Air:AndroidStudioProjects abhijeet$ cp README.md README-template.md
Abhijeets-MacBook-Air:AndroidStudioProjects abhijeet$ git add README-template.md
Abhijeets-MacBook-Air:AndroidStudioProjects abhijeet$ git commit -m "adding README-template.md as a reference backup template"
[master 3a5f795] adding README-template.md as a reference backup template
 1 file changed, 88 insertions(+)
 create mode 100755 README-template.md
Abhijeets-MacBook-Air:AndroidStudioProjects abhijeet$ git remote add origin https://github.com/abhijeetmandal/android-studio-projects.git
fatal: remote origin already exists.
Abhijeets-MacBook-Air:AndroidStudioProjects abhijeet$ git push -u origin master
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 288 bytes | 288.00 KiB/s, done.
Total 2 (delta 0), reused 0 (delta 0)
To https://github.com/abhijeetmandal/android-studio-projects.git
   7133ca9..3a5f795  master -> master
Branch 'master' set up to track remote branch 'master' from 'origin'.

```

pull code

```AppleScript
Abhijeets-MacBook-Air:AndroidStudioProjects abhijeet$ git pull
remote: Enumerating objects: 5, done.
remote: Counting objects: 100% (5/5), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (3/3), done.
From https://github.com/abhijeetmandal/android-studio-projects
   babbd1f..921c94b  master     -> origin/master
Updating babbd1f..921c94b
Fast-forward
 README.md | 3 ++-
 1 file changed, 2 insertions(+), 1 deletion(-)
```

git status

```AppleScript
Abhijeets-MacBook-Air:AndroidStudioProjects abhijeet$ git status
On branch master
Your branch is up to date with 'origin/master'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        .idea/
        MyFirstAndroidApp/

no changes added to commit (use "git add" and/or "git commit -a")
```

## References

Cheet sheet

https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet

Syntax highlighting

https://github.com/github/linguist/blob/master/lib/linguist/languages.yml
