# Android tutorial

Documentations

## GIT commands

frequently used and useful commands 

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

## References

Cheet sheet

https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet

Syntax highlighting

https://github.com/github/linguist/blob/master/lib/linguist/languages.yml
