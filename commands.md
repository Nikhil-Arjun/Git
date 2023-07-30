# Important git commands

### Begineer level commands

- `git init` &rarr; it initializes a new git repository.
  Powers your folder to be managed by git, and initialises a new empty repository. It also creates a .git folder that has all the relevent logic to manage version of your project. <br><br>
  What is a repository ?<br>
  it is a folder managed by git where we can track all the changes we are making in the project.

- `Working Area` &rarr; There can be a bunch of files that are not currently handled by git. It means that changes done or to be done in those files are not managed by git yet.<br> A file which is in working area is considered to be not in the staging area. When we do git status and we see abunch if untracked files then these are actually called to be in the working area.

- `Staging area` &rarr; What all files are going to be part of the next version that we will create. This staging area is the place where git knows what changes will be done from the last version to the next version.

- `Repository Area` &rarr; This area actually contains the details of all you previous registered version. And the files in this area, git already manages them and knows their version history. <br>

- `git add <filename>` &rarr; starts tracking your new changes for the next commit.

- `git rm --cached <file>` &rarr; moves file back from staging area to working area <br>

- `commit` -> Commit is a particular version of the project. It captures a snapshot of the project's staged changes and creates a version out of it.

- `git commit -m "<message>"` &rarr; this creates a new version based on your previous changes.

- `git log` &rarr; list downs all the commits of the repository. If you want to exit out of git log prompt press q.
