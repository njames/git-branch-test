03:41:00 /var/www$ git clone git@njames.github.com:njames/git-branch-test.git
Cloning into 'git-branch-test'...
remote: Counting objects: 4, done.
remote: Compressing objects: 100% (4/4), done.
remote: Total 4 (delta 0), reused 0 (delta 0), pack-reused 0
Receiving objects: 100% (4/4), done.
03:41:30 /var/www$ cde git-branch-test/
03:43:36 (master) /var/www/git-branch-test$ 
03:43:36 (master) /var/www/git-branch-test$ git co -b staging
Switched to a new branch 'staging'
03:45:29 (staging) /var/www/git-branch-test$ git co -b develop
Switched to a new branch 'develop'
03:45:43 (develop) /var/www/git-branch-test$ git co -b feature/GBT-Add-Content
Switched to a new branch 'feature/GBT-Add-Content'
03:46:18 (feature/GBT-Add-Content) /var/www/git-branch-test$ touch index.md
03:46:32 {feature/GBT-Add-Content} /var/www/git-branch-test$ vi index.md 
03:46:45 {feature/GBT-Add-Content} /var/www/git-branch-test$ 

This is what we have done so far. Created a new branch for master, staging, develop and feature branches.
