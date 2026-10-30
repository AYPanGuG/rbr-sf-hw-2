1. What is the difference between a working directory, the staging area, a commit, and a remote repository?
Working directory can save what i edit in local pc.
staging area put the file before commit.
commit will save the stage chage and the message on local repository.
remote repository will save data what we upload to github.
2. What do `HEAD`, `main`, and `origin` refer to in a normal repository?
Head is what branch i editing now.
main is the default main branch.
origin is the last version i cloned from github.
3. Why should you pull or fetch recent `main` changes before starting new work?
Because i can ensure that the work which i am doing is the lastest version.
4. What is the difference between fetching and pulling?
fetch will make a new folder while pull will update or merges to current branch.
5. What is the difference between merging and rebasing? When is rebasing a shared branch dangerous?
merging will joins two branches to one and having hestory while rebasing will not. It may overwrite other version.
6. Why are pull requests useful even though they are not part of Git itself?
As pull can compare income and currect change, we can review what have been changed every version easily.
7. In Task 4, Git created a new commit called `Merge branch 'can'`. Why was a new commit needed?
main version update the read me and can version update the main.cpp. To keep both of then, we need to merge.
8. In Task 5, both branches changed `src/main.cpp`. Why did `can_id` merge by itself but `@version` and `loop()` did not?
As can_id change main brange only but the other have two different update, we need to confirm which is correct.
9. In Task 6, which workflow ran when you pushed to `ci`, and which did not? Why? What does the CI workflow protect the team from?
Working directory ran but Doxygen GitHub Pages Deploy Action no because it only run when uploaded to main brach. CI can ensure the code is work before upload to main branch.
10. What does a .gitignore file do, and why does it not remove a file that was already committed? Why is `.pio` in `.gitignore`?
It can tell github ignore what file. It will not affect the file already committed. .pio is ignored because it contains generated PlatformIO build files.
