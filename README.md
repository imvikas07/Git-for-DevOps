# Git For DevOps

## Study Material

Provided by: DURGASOFT  
Location: #202, 2nd Floor, HUDA Maitrivanam, Ameerpet, Hyderabad - 500038  
Contact: 88 85 25 26 27, 72 07 21 24 27/28  
Website: [durgasoftonline.com](http://www.durgasoftonline.com)  
Email: [durgasoftonline@gmail.com](mailto:durgasoftonline@gmail.com)

---

## Index

1. [Introduction to DevOps](#introduction-to-devops)
2. [Introduction to Version Control System](#introduction-to-version-control-system)
3. [Features and Architecture of GIT](#features-and-architecture-of-git)
4. [Life Cycle of File in GIT](#life-cycle-of-file-in-git)
5. [Git Installation On Windows](#git-installation-on-windows)
6. [Example-1 To Understand Working Directory, Staging Area, and Local Repository](#example-1-to-understand-working-directory-staging-area-and-local-repository)
7. [The 6 Git Commands With Example - init, status, add, commit, log, and config](#the-6-git-commands-with-example---init-status-add-commit-log-and-config)
8. [The Complete Postmortem of git log Command](#the-complete-postmortem-of-git-log-command)
9. [The Complete Story of git diff Command](#the-complete-story-of-git-diff-command)
10. [Helix Visual Merge Tool (p4merge) For Checking Differences](#helix-visual-merge-tool-p4merge-for-checking-differences)
11. [Removing Files by Using git rm Command](#removing-files-by-using-git-rm-command)
12. [Undo Changes with git checkout Command](#undo-changes-with-git-checkout-command)
13. [Git References (master and HEAD)](#git-references-master-and-head)
14. [Git reset Command](#git-reset-command)
15. [Git Aliases - Providing Our Own Convenient Names to Git Commands](#git-aliases---providing-our-own-convenient-names-to-git-commands)
16. [Ignoring Unwanted Files and Directories by Using .gitignore File](#ignoring-unwanted-files-and-directories-by-using-gitignore-file)
17. [Any Special Treatment for Directories by Git?](#any-special-treatment-for-directories-by-git)
18. [Branching and Merging](#branching-and-merging)
19. [Merging by Using Rebase](#merging-by-using-rebase)
20. [Stash in GIT](#stash-in-git)
21. [Working with Remote Repositories](#working-with-remote-repositories)
22. [Git Tagging (git tag Command)](#git-tagging-git-tag-command)
23. [git revert Command](#git-revert-command)
24. [Cherry-Picking (git cherry-pick Command)](#cherry-picking-git-cherry-pick-command)
25. [git reflog Command](#git-reflog-command)

---

## Detailed Index

### Introduction to DevOps

1.1. What is DevOps?  
1.2. Water Fall Model  
1.3. Agile Model  
1.4. Waterfall vs Scrum  
1.5. DevOps vs Agile Models  
1.6. Top Important Points about DevOps  

### Introduction to Version Control System

2.1. Need of Version Control System?  
2.2. How Version Control System Works?  
2.3. The Basic Terminology of Version Control System  
2.4. Benefits of Version Control System  
2.5. Types of Version Control Systems  
&nbsp;&nbsp;&nbsp;&nbsp;2.5.1. Centralized Version Control System  
&nbsp;&nbsp;&nbsp;&nbsp;2.5.2. Distributed Version Control Systems  

### Features and Architecture of GIT

3.1. What is GIT?  
3.2. Features of GIT  
3.3. GIT Architecture  

### Life Cycle of File in GIT

4.1. Untracked  
4.2. Staged  
4.3. In Repository/Committed  
4.4. Modified  

### Git Installation On Windows

### Example-1 To Understand Working Directory, Staging Area, and Local Repository

### The 6 Git Commands With Example - init, status, add, commit, log, and config

### The Complete Postmortem of git log Command

8.1. How to See History of All Commits in Local Repository  
8.2. How to See Log Information of a Particular File  
&nbsp;&nbsp;&nbsp;&nbsp;Option-1: --oneline Option to Get Brief Log Information  
&nbsp;&nbsp;&nbsp;&nbsp;Option-2: -n Option to Limit the Number of Commits to Display  
&nbsp;&nbsp;&nbsp;&nbsp;Option-3: --grep Option to Search Based on Given Pattern in Commit Message  
&nbsp;&nbsp;&nbsp;&nbsp;Option-4: Show Commits More Recent Than a Specific Time  
&nbsp;&nbsp;&nbsp;&nbsp;Option-5: Show Commits Older Than a Specific Time  
&nbsp;&nbsp;&nbsp;&nbsp;Option-6: Show Commits Based on Author  
&nbsp;&nbsp;&nbsp;&nbsp;Option-7: --decorate Option to Display Extra Information  

### The Complete Story of git diff Command

Case-1: To See the Difference in File Content Between Working Directory and Staging Area  
Case-2: To See the Difference in File Content Between Working Directory and Last Commit  
Case-3: To See the Difference in File Content Between Staged Copy and Last Commit  
Case-4: To See the Difference in File Content Between Specific Commit and Working Directory Copy  
Case-5: To See the Difference in File Content Between Specific Commit and Staging Area Copy  
Case-6: To See the Difference in File Content Between Two Specified Commits  
Case-7: To See the Difference in File Content Between Last Commit and Last But One Commit  
Case-8: To See the Differences in All Files Content Between Two Specified Commits  
Case-9: To See the Differences in Content Between Two Branches  
Case-10: To See the Differences in Content Between Local and Remote Repositories  

### Helix Visual Merge Tool (p4merge) For Checking Differences

### Removing Files by Using git rm Command

Case-1: To Remove Files from Working Directory and Staging Area (git rm)  
Case-2: To Remove Files Only from Staging Area (git rm --cached)  
Case-3: To Remove Files Only from Working Directory (rm Command)  

### Undo Changes with git checkout Command

### Git References (master and HEAD)

### Git reset Command

Utility-1: To Remove Changes from Staging Area  
Utility-2: To Undo Commits at Repository Level (--mixed, --soft, --hard Modes)  

### Git Aliases - Providing Our Own Convenient Names to Git Commands

### Ignoring Unwanted Files and Directories by Using .gitignore File

### Any Special Treatment for Directories by Git?

### Branching and Merging

18.1. What is Branching?  
18.2. Need of Creating a New Branch  
18.3. Various Commands Used in Branching  
&nbsp;&nbsp;&nbsp;&nbsp;1. To View Branches  
&nbsp;&nbsp;&nbsp;&nbsp;2. To Create a New Branch  
&nbsp;&nbsp;&nbsp;&nbsp;3. To Switch from One Branch to Another Branch  
&nbsp;&nbsp;&nbsp;&nbsp;4. Short-cut Way to Create a New Branch and Switch to That Branch  
18.4. Demo Example for Branching  
18.5. Multiple Use Cases Where Branching is Required  
18.6. Advantages of Branching  
18.7. Merging of a Branch  
18.8. What is Fast-forward Merge?  
18.9. What is Three-Way Merge?  
18.10. Differences Between Fast-forward and Three-way Merges  
18.11. Merge Conflicts and Resolution Process  
18.12. How to Delete a Branch  

### Merging by Using Rebase

19.1. Process of Rebasing  
19.2. Demo Example for Rebasing  
19.3. Advantages of Rebasing  
19.4. Disadvantages of Rebasing  
19.5. Differences Between Merge and Rebase  

### Stash in GIT

20.1. What is git stash?  
20.2. Demo Example for Stashing  
20.3. How to List All Available Stashes?  
20.4. How to Check the Contents of Stash?  
20.5. How to Perform Unstash?  
20.6. Partial Stash  
20.7. How to Delete the Stash?  

### Working with Remote Repositories

21.1. Need of Remote Repositories  
21.2. How to Work with GitHub?  
21.3. How to Create an Account in GitHub?  
21.4. How to Create a New Repository in GitHub?  
21.5. How to Work with Remote Repository?  
&nbsp;&nbsp;&nbsp;&nbsp;1. git remote  
&nbsp;&nbsp;&nbsp;&nbsp;2. git push  
&nbsp;&nbsp;&nbsp;&nbsp;3. git clone  
&nbsp;&nbsp;&nbsp;&nbsp;4. git pull  
&nbsp;&nbsp;&nbsp;&nbsp;5. git fetch  

