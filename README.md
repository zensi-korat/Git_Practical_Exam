# Git_Practical_Exam
# 1. Pull and Merge Difference
- Make example of pull request and two branch merge event.

        1. Created a branch named feature1.
        2. Commit the feature1 branch and after that push that new branch.
        3. Create a pull request on github.
        4. Merge the feature branch with main branch.

# 2. Rebase
- Rebase feature branch with master branch

    ```
   git rebase main
    ```
        1. I Create a branch named rebase.
        2. Then Pulled rebase branch's latest commits.
        3. Checkout in main branch.
        4. Pull latest commits of main branch.
        5. Checkout to rebase branch.
        6. Start to perform rebase.
        7. Once you finish rebasing,push immediately to remote

# 3. Change commit message
- Commit push on commit in feature branch and then change commit message

        1. I created a branch named changecommit.
        2. Then I created a file named commit.html.
        3. Then to change commit message I used and after that pushed it:
    
    ```
    git commit --amend -m "message modified"
    ```
    ```
    git push --force origin changecommit
    ```
This changes the message of commit in remote too.

# 4. Cherry pick
-  Pick some commits from feature branch to master branch

        1. I created a branch named cherrypick.
        2. Then I created a file named cherrypick.html.
        3. Then copy the hash code of commit that I wanted to add in main branch.
        4. Then I checked out to main branch.
        5. Then performed the command.
        6. After that push in remote.
    ```
    git checkout main
    git cherry-pick <hash-code of commit>
    ```
# 5. Drop commit
- Remove some commit from feature branch.
        1. For this, I created a branch named drop_commit and in that made 3 files.
        2. In drop3.html, I made one main container and 2 sub-containers.
        3. Later, I dropped the last sub container.
    ```
    git reset --hard HEAD^
    ```


    


