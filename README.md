# seattle-201d49-lab05a
lab05$ pwd
/mnt/c/Users/Lyndsey/desktop/code_fellows_201/lab05
lab05$ git add .
fatal: not a git repository (or any parent up to mount point /mnt)
Stopping at filesystem boundary (GIT_DISCOVERY_ACROSS_FILESYSTEM not set).
lab05$ git pull
fatal: not a git repository (or any parent up to mount point /mnt)
Stopping at filesystem boundary (GIT_DISCOVERY_ACROSS_FILESYSTEM not set).
lab05$ git checkout -b "workdamnit"
fatal: not a git repository (or any parent up to mount point /mnt)
Stopping at filesystem boundary (GIT_DISCOVERY_ACROSS_FILESYSTEM not set).
lab05$ git_discovery_across_filesystem
git_discovery_across_filesystem: command not found
lab05$

lab05$ git add .
fatal: not a git repository (or any parent up to mount point /mnt)
Stopping at filesystem boundary (GIT_DISCOVERY_ACROSS_FILESYSTEM not set).
lab05$ git commit -m "function two, multiplication, completed"
fatal: not a git repository (or any parent up to mount point /mnt)
Stopping at filesystem boundary (GIT_DISCOVERY_ACROSS_FILESYSTEM not set).
lab05$ git init
Initialized empty Git repository in /mnt/c/Users/Lyndsey/desktop/code_fellows_201/lab05/.git/
lab05$ git remote add origin [seattle-201d49-lab05a]
lab05$ git add .
warning: adding embedded git repository: seattle-201d49-lab05a
hint: You've added another git repository inside your current repository.
hint: Clones of the outer repository will not contain the contents of
hint: the embedded repository and will not know how to obtain it.
hint: If you meant to add a submodule, use:
hint:
hint:   git submodule add <url> seattle-201d49-lab05a
hint:
hint: If you added this path by mistake, you can remove it from the
hint: index with:
hint:
hint:   git rm --cached seattle-201d49-lab05a
hint:
hint: See "git help submodule" for more information.
lab05$
lab05$ git commit -m "multiplication function added, commit one"
[master (root-commit) a82805d] multiplication function added, commit one
 1 file changed, 1 insertion(+)
 create mode 160000 seattle-201d49-lab05a
lab05[master !]$ git push
fatal: The current branch master has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin master

lab05[master !]$ git push origin master
fatal: ']' does not appear to be a git repository
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.
lab05[master !]$ git push origin seattle-201d49-lab05a
error: src refspec seattle-201d49-lab05a does not match any.
error: failed to push some refs to '[seattle-201d49-lab05a]'
lab05[master !]$
