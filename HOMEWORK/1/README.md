# PROBLEM 1 PART 1

See [README.md](https://github.com/NicholasDotson/IDS2021F/blob/main/README.md) file in [main](https://github.com/NicholasDotson/IDS2021F)

# PROBLEM 2

The three types of Version Control Systems are:
  
- Local VCS

- Centralized VCS (CVCS)

- Distributed VCS (DCVS

# PROBLEM 3

The best VCS type is the Distributed VCS (DVCS) due to keeping a copy of the remote repository on the client's local storage. This way, data is saved from the most recent clone which can mitigate corruption issues if a server fails.

# PROBLEM 4

The following commands and descriptions are as follows:

- git pull
  - This command retrieves the latest project revision from the remote repository to the local repository. This allows multiple users to be working simultaneously.

- git status
  - This command monitors the remote repository.

- git add --all
  - This command adds all of the modified files from the local repository to the staging area before they are added to the remote repository.

- git commit -m"latest build"
  - This command both submits staged files to the remote repository with the -m being a flag for a note, in this case describing the files as the latest build. This is to avoid confusion if a remote repository is being worked on by multiple users.

- git push --all
  - This command permanently places committed files from the staging area into the local repository. This allows the files to be shared amongst users.
