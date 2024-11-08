**1.**
    check git repo =>git remote -v
    remove repo => git remote remove origin
    add repo => git remote add origin URL


**2.  What is a conflict?**
         
        Git usually handles feature merges automatically but sometimes while working in a team environment, there might be cases of conflicts such as:

   **1.** When two separate branches have changes to the same line in a file
   **2.** A file is deleted in one branch but has been modified in the other.    


**3. difference between Git and GitHub?**

| **Git**                                                                 | **GitHub**                                                            |
|-------------------------------------------------------------------------|--------------------------------------------------------------|
| Git is a distributed version control system installed on local machines. It allows developers to track changes in code, manage commit histories, and collaborate on code. | GitHub is a cloud-based platform that hosts Git repositories. It provides a central repository where code can be stored, shared, and collaborated on using Git.             |
| It is maintained by "The Linux Foundation."                             | It was acquired by "Microsoft" in 2018.                                |
| Competitors include SVN, Mercurial, etc.                                | Competitors include GitLab, Atlassian Bitbucket, etc.                 |
| Focuses on version control and local repository management.             | Offers additional features like forking, user management, pull requests, and issue tracking, making collaboration easier.           |

In simple terms, **Git** is the underlying tool for managing versions of your code, while **GitHub** is a platform that makes it easier to share and work on Git repositories online.   



**4.What is the difference between git fetch and git pull?**

   **git fetch:**
            The git fetch command retrieves changes from a remote repository to the local repository. It updates the remote-tracking branches **(e.g., origin/master)** in the local repository to reflect the state of the remote repository, but it does not update the working directory or merge any changes into the current branch. This means that after fetching, you can review the changes made in the remote repository without affecting your local work.

   **git pull:**
            The git pull command also retrieves changes from a remote repository, but it goes a step further by fetching changes and merging them into the current branch in one step. It essentially performs a git fetch followed by a git merge to incorporate the changes from the remote repository into the current branch. 
            
