# Terminal Definitions
- pwd: Print working directory
- ls: List all of our files and directories inside of our current directory
- cd [new directory to move to]: Change current working directory to new directory
- mkdir [NameOfDirectory]: Makes a new directory
- touch [filename]: Makes a new file
- nano [filename]: Opens a file in nano

# Git Definitions
- Version Control: A system that records changes to a file or set of files over time so that you can recall specific versions later
- VCS: Version Control System that allows you to revert selected file or an entire project back to a previous state, compare changes over time and much more
- Distributed VCS: Instead of checking out a snapshot a developer clones the entire project with all its history to a local client
- Working Directory: a single snapshot of the current project
- Staging Area: a single file in the .git directory that stores information about what will go in the next commit
- Git Directory: the meta data and object database for your project 
- Unmodified: means the file is unchanged
- Modified: means you have changed a file but have not committed those changes
- Staged: means you have marked a changed file to go into the next commit (snapshot)
- Committed: means the data is stored in the local database
- git branch <branchname> - create a new branch with the given name
- git checkout <branchname> - switch to new branch
- git checkout -b <branchname> - create new branch and switch to it
- git branch -d <branchname> - delete existing branch with given name
- git merge [branchNameToMerge]: merges the branch named into the current branch you are working on
