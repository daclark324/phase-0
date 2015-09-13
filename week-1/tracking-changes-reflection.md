How does tracking and adding changes make developers' lives easier?

Tracking and adding changes allows developers to re-visit previous commits/"check-points" to identify errors in new code as well as identify who worked on particular portions of a shared project, what they did, and when.

What is a commit?

A commit is a version or checkpoint. When changes are made to a project, the changes get added first then once all the revisions you want are ready you commit those changes into a new version.

What are the best practices for commit messages?

Best practices for commit messages include being as descriptive and specific as possible while using unique identifiers rather than generic terms and names.


What does the HEAD^ argument mean?

HEAD^ refers to the last commit.


What are the 3 stages of a git change and how do you move a file from one stage to the other?



Write a handy cheatsheet of the commands you need to commit your changes?

1.  start with master branch [IN TERMINAL]
2.  git pull (check for update) [IN TERMINAL]
3.  git checkout –b ‘branch_name’ (create new branch) [IN TERMINAL]
4.  do work in new branch [IN TERMINAL]
5.  git add [IN TERMINAL]
6.  git commit –m “commit message” [IN TERMINAL]
7.  git checkout master [IN TERMINAL]
8.  git pull [IN TERMINAL]
9.  git checkout ‘branch_name’ [IN TERMINAL]
10. git merge master [IN TERMINAL]
11. git push origin ‘branch_name’ [IN TERMINAL]
12. in github, go to appropriate repo make pull request, compare master to ‘branch_name’  [IN GITHUB]
13. delete branch [IN GITHUB]
14. Git checkout master
15. Git fetch origin master
16. Git merge origin/master
17. Git branch –d ‘branch_name’


What is a pull request and how do you create and merge one?

A pull request is essentially a request to ammend the changes you were working on remotely with the master file data from GitHub. See above steps to see how to do one.

Why are pull requests preferred when working with teams?

Pull requests are preferred when working with teams because it allows for tracking and management of multiple revisions by multiple individuals on the team.