

// ANSWER 1:
"git version 2.36.1.windows.1" 


// ANSWER 2:
diff.astextplain.textconv=astextplain
filter.lfs.clean=git-lfs clean -- %f
filter.lfs.smudge=git-lfs smudge -- %f
filter.lfs.process=git-lfs filter-process
filter.lfs.required=true
http.sslbackend=openssl
http.sslcainfo=C:/Program Files/Git/mingw64/ssl/certs/ca-bundle.crt
core.autocrlf=true
core.fscache=true
core.symlinks=true
pull.rebase=false
credential.helper=manager-core
credential.https://dev.azure.com.usehttppath=true
init.defaultbranch=master
user.name=Ben Hannon
user.email=bh700719@ohio.edu


// ANSWER 3:
When entering the command "git --help" we get get a table of commands and their usages for git.


// ANSWER 4:
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        README.md
        answers.md

nothing added to commit but untracked files present (use "git add" to track)


// ANSWER 5:
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   README.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        answers.md


// ANSWER 6:
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   README.md
        new file:   answers.md


// ANSWER 7:
On branch master
nothing to commit, working tree clean


// ANSWER 8:
commit 05ca64673b1621658b6e3f441dee5ece3b40094f (HEAD -> master)
Author: Ben Hannon <bh700719@ohio.edu>
Date:   Fri May 13 20:39:00 2022 -0400

    Initial commit


// ANSWER 9:
info: please complete authentication in your browser...
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 227 bytes | 227.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/ben-hannon/git-lab.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.


// Answer 10
No they did not, it looks to be blank.


// ANSWER 11
To https://github.com/ben-hannon/git-lab.git
 ! [rejected]        main -> main (fetch first)
error: failed to push some refs to 'https://github.com/ben-hannon/git-lab.git'
hint: Updates were rejected because the remote contains work that you do
hint: not have locally. This is usually caused by another repository pushing
hint: to the same ref. You may want to first integrate the remote changes
hint: (e.g., 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.


// ANSWER 12:
Yes, the pull command updated README.md with my text.


// ANSWER 13:
    Directory: C:\Users\bennh\2400\git-lab-2


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----         5/13/2022   9:17 PM            302 .gitignore
-a----         5/13/2022   9:17 PM             11 README.md



