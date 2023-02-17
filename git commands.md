#git init#

A git repository must first be created before you can make commits or do anything else with it. We’ll use the git init command to create a new Git repository. The init subcommand stands for “initialise,” which is useful because it’s the command that handles all of a repository’s initial setup. In a moment, we’ll look at what it does. The git init command creates all of the necessary files and directories for Git to keep track of everything. All of these files are kept in a directory called .git (note the . at the beginning; this indicates that it will be hidden on Mac/Linux). The “repo” is this .git directory!

#git clone#

The command we’ll be doing on the terminal is git clone, which is how cloning is related to Git. The git clone command takes a path (typically a URL) to the Git repository you want to clone. The command is git clone, and the path to the Git repository you want to clone is passed as an argument. This is the URL for the project we’ll be working on throughout the course. git clone produces a local working copy of a remote repository’s source code. When you clone a repository, the code is downloaded to your machine automatically. If you have permission, this command will add the original location as a remote location, allowing you to grab changes from it and push changes to it.

#git status#

The git status command is our key to Git’s mind. It will inform us of Git’s thoughts and the state of our repository as seen by Git. When you’re first getting started, you should always use the git status command! Seriously. It’s a good idea to start running it after any other command. This will assist you in learning Git and avoiding making (potentially) inaccurate assumptions about the state of your files/repository.


#git add#
To move files from the Working Directory to the Staging Index, use the git add command. The git add command saves your changes in a file to the staging area, allowing you to compare your local version to the remote repository’s version. Before committing your new or changed file, use the git add command to add it to the staging area. To add specific files:



#git commit#
This command saves a log message along with the commit id of the modifications made to the git repository. The modifications are saved in your local repository with git commit. You must include a brief description of the changes made every time you commit your code changes. This commit message aids others in comprehending the changes made.



#git push#
This command pushes the contents of your local repository to the remote repository you’ve added. This pushes your master branch’s commits to the newly added remote repository. If a named branch does not exist in the remote repository, it will be created.



#git pull#
The contents of the remote repository are fetched and integrated into your local repository using this command. git pull pulls the most recent changes from the remote server into the local repository, ensuring you have the most up-to-date information from your coworkers.



#git log#
The git log command is used to show all of a repository’s commits. This command displays a log of all commits made to the current branch so far.
