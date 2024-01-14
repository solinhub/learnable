# learnable-task-2

**Version control** is a system that records changes to a file or set of files over time so that you can recall specific versions later. It helps software developers manage, track and collaborate on code seamlessly.


-**Git** is a Distributed Version Control System software installed locally on computer to manage and keep track of source code history. It can be used on the original command line-tool, and many other user interfaces of varying capabilities.   
**GitHub** on the other hand is a web-based hosting service. It is the single largest host for Git repositories, and is the central point of collaborations for millions of collaborators and projects. Many open source projects use it for Git hosting, issue tracking, code review, and other things.


-**AWS CodeCommit, SourceForge, and BitBucket** are GitHub alternatives.


-The **Git Fetch** command fetches all the changes from the server that you do not have yet to the local repository without modifying your working directory at all. **Git Pull** will look up what server and branch your current branch is tracking and bring the copy of the remote directory into the working directory. It simply fetches data from a server you originally cloned from and automatically tries to merge it into the code you are currently working on.


-**Git Rebase** is used to integrate changes from one branch into another. With it, you can take all the changes that were committed on one branch and replay them on a different branch. The command to perform the standard rebase is ***git rebase <base>***


-**Git Cherry-pick** is used to take the change introduced in a single Git commit and try to re-introduce it as a new commit on the branch you are currently on. The command for it is ***git cherry-pick***