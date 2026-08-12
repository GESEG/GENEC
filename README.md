# GENEC
Welcome to the Geneva stellar evolution code.

To copy the code to your computer, run:

git clone git@github.com:GESEG/GENEC.git

git tutorials can be found here:
https://www.atlassian.com/git/tutorials/

The "develop" branch (which you download with the command above) is the main development branch.

To get started, read and follow the main [GENEC manual](https://github.com/GESEG/GENEC/blob/release_202603/docs/GENEC.pdf). We are assembling more instructions in the [Wiki](https://github.com/GESEG/GENEC/wiki).


For code developers only:

Before making any changes, please create your own branch off the development branch using a command like this:

git checkout -b feature/my_feature develop

[meaning that you create a new branch called "feature/my_feature" starting from the "develop" branch]
[my_feature should be replaced by the topic of the feature you are working on]

When you want to save changes to the git repo, use this command (after running git status, add, commit):

git push origin feature/my_feature
[this pushes the changes you made to your (local) branch to the remote (origin) repository]

