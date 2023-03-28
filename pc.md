## Research Questions 

Now that you are all set up, it's time to learn a little more about the tools of the trade. Edit this file and answer the following questions. You are going to need to start familiarizing yourself with the [GitHub docs](https://docs.github.com/en). Docs (short for documentation) are the instructions on how to use a languge or program. A large part of your job as a developer will be learning how to read and work with documentation. Please reference the GitHub docs when answering the questions below. If you cannot find what you are looking for in the docs, you can always start to practice your Google skills!

1. What is Git? A free, open source distributed version control system that is designed to handle projects from small to large with speed and efficiency.  
2. What is the difference between Git and GitHub? Git is a version control system that lets you manage and track source code history, while Github is a cloud based hosting service that lets you manage Git repositories. 
3. Why do we create a branch? A branch allows you to isolate developmental work without affecting other branches in each repository. It allows you to safely develop, fix bugs, or experiment with new idea in a contained area of your repository. 
4. What is the purpose of a Pull Request? To share changes you've made to the branch of a repository. 
5. What is the command you can use to switch between branches? For example you are working on the FIRSTNAME-LASTNAME branch and you want to switch back to main. git checkout "branch name" 
6. Explain the difference between `git fetch`, `git merge` and `git pull`. What does each command do? 
git fetch - downloads a branch from another repository, along with all of its associated commits and files, but doesn't try to integrate anything into your local repository. This gives you a chance to inspect changes before merging them with your own project. 
git merge - incorporates changes from the named commits into the current branch, it is Git's way of putting a forked history back together. 
git pull - used to fetch and download content from a remote repository and integrate it into the local repository. 
7. What is a merge conflict? A merge conflict happens when people make different changes to the same line of a file, or when one person edits a file and another person deletes that same file. 
8. How do you resolve a merge conflict? You can resvole simple conflicts, involving competing line changes, with the GitHub conflict editor, but for all other types of merge conflicts, you must use the CL prompt by choosing which changes to incorporate from the different branches into a new commit. 
