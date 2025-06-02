<!-- // git and github  -->

git--> software
github ---> online service of git

**vcs(version control system)
# Atomic commit --> commit the file in every small peace of code or function
#  ls -la   --> hidden file in command line.
<!-- ===== git basic command ====== -->
1. git --v  ---> checking the version of github

<!-- //repo creating -->
2.  git status ---> exist or not
3.  git init ---> intialization   (write add commit)
4.  git add . (for all the file uploading) --> staging area
    git add filename (for single file)
    git rm --cached filename ---> for unstage the file. 
5.  git commit -m "message"  (for write some message) --> repo area
6.  git log (what's change you've done till now. it give commit id)
7.  git ignore ---> (if you want to hide any file in your repo (.env file) )
8.  git push origin main (push your data in current repo)
9.  git branch (where your file or folder are stored)
10. git switch filename( and what the branch you want write the name.. )
11. git merge branchname ---->(merge more than one branches)   (git graph-tool)
12. git merge --abort (handle conflict file )
13. git diff (informational command to find the diff between two file/folder/branch.. )
14. git stash --->(change in temp location/store)
15. git tag tagname (just like sticky note)
