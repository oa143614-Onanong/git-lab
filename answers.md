Answer 1
git version 2.46.1.windows.1

Answer 2
diff.astextplain.textconv=astextplain
filter.lfs.clean=git-lfs clean -- %f
filter.lfs.smudge=git-lfs smudge -- %f
filter.lfs.process=git-lfs filter-process
filter.lfs.required=true
http.sslbackend=openssl
http.sslcainfo=C:/Program Files/Git/mingw64/etc/ssl/certs/ca-bundle.crt
core.autocrlf=true
core.fscache=true
core.symlinks=false
pull.rebase=false
credential.helper=manager
credential.https://dev.azure.com.usehttppath=true
init.defaultbranch=master
user.email=oa143614@ohio.edu
user.name=oa143614-Onanong
credential.helper=cache

Answer 3
It shows the list and defination of each commands.
usage: git [-v | --version] [-h | --help] [-C <path>] [-c <name>=<value>]
           [--exec-path[=<path>]] [--html-path] [--man-path] [--info-path]
           [-p | --paginate | -P | --no-pager] [--no-replace-objects] [--no-lazy-fetch]
           [--no-optional-locks] [--no-advice] [--bare] [--git-dir=<path>]
           [--work-tree=<path>] [--namespace=<name>] [--config-env=<name>=<envvar>]
           <command> [<args>]

These are common Git commands used in various situations:

start a working area (see also: git help tutorial)
   clone     Clone a repository into a new directory
   init      Create an empty Git repository or reinitialize an existing one

work on the current change (see also: git help everyday)
   add       Add file contents to the index
   mv        Move or rename a file, a directory, or a symlink
   restore   Restore working tree files
   rm        Remove files from the working tree and from the index

examine the history and state (see also: git help revisions)
   bisect    Use binary search to find the commit that introduced a bug
   diff      Show changes between commits, commit and working tree, etc
   grep      Print lines matching a pattern
   log       Show commit logs
   show      Show various types of objects
   status    Show the working tree status

grow, mark and tweak your common history
   branch    List, create, or delete branches
   commit    Record changes to the repository
   merge     Join two or more development histories together
   rebase    Reapply commits on top of another base tip
   reset     Reset current HEAD to the specified state
   switch    Switch branches
   tag       Create, list, delete or verify a tag object signed with GPG

collaborate (see also: git help workflows)
   fetch     Download objects and refs from another repository
   pull      Fetch from and integrate with another repository or a local branch
   push      Update remote refs along with associated objects

'git help -a' and 'git help -g' list available subcommands and some
concept guides. See 'git help <command>' or 'git help <concept>'
to read about a specific subcommand or concept.
See 'git help git' for an overview of the system.


Answer 4
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        README.md
        answers.md
        image.png

nothing added to commit but untracked files present (use "git add" to track)

Answer 5
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   README.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        answers.md
        image.png

Answer 6
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   README.md
        new file:   answers.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        image.png

Answer 7
[master (root-commit) 53a4f08] Initial commit
 2 files changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 README.md
 create mode 100644 answers.md

Answer 8
commit 53a4f08096afe8bf5f6cbf7be93df7a5c4a1c90f (HEAD -> master)
Author: oa143614-Onanong <oa143614@ohio.edu>
Date:   Mon May 12 20:31:51 2025 -0400

    Initial commit

Answer 9
PS C:\Users\annan\Documents\git-lab> git status
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   answers.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        image.png

no changes added to commit (use "git add" and/or "git commit -a")

Answer 10
changing online does not reflected in local copy.

Answer 11
After using git push command, it recieve the error.
To https://github.com/oa143614-Onanong/git-lab.git
 ! [rejected]        main -> main (fetch first)
error: failed to push some refs to 'https://github.com/oa143614-Onanong/git-lab.git'
hint: Updates were rejected because the remote contains work that you do not
hint: have locally. This is usually caused by another repository pushing to
hint: the same ref. If you want to integrate the remote changes, use
hint: 'git pull' before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

Answer 12
the local file information is similar as online file.

Answer 13
PS C:\Users\annan\Documents> cd .\git-lab-2\
PS C:\Users\annan\Documents\git-lab-2> ls


    Directory: C:\Users\annan\Documents\git-lab-2


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----         5/13/2025   8:17 PM            302 .gitignore
-a----         5/13/2025   8:17 PM             11 README.md


PS C:\Users\annan\Documents\git-lab-2>





