# Git Commands Cheat Sheet - **_Vocabulary_**

**Bare Repository**: Repository that doesn’t have a working directory.<br>
**Branch**: An active area of development in Git. The newest commit displays the end of the branch.<br>
**Blame**: Refers to the most recent alteration to every line in the file. Shows Author, Revision, and Time.<br>
**Checkout**: This is talking about the process whereby a particular commit is chosen from the repository and the condition of the file associated with it and the directory tree are reproduced in the working directory.<br>
**Commit**: Record of a moment in Git history containing details of a changeset.<br>
**Diff**: The difference in changes between saved changes or two Commits.<br>
**Detached Head**: The state in which a specific commit is checked out rather than a branch.<br>
**Fetch**: Retrieves the most recent changes in the branch and the local or remote repositories.<br>
**Fork**: When you Fork the repository, you can add Commits and add Pull Requests.<br>
**Hash**: A unique SHA1 code for each Commit<br>
**Head**: The name of the Commit at the end of a Branch<br>
**Index**: A group of files that hold state information.<br>
**Merge**: Includes changes from named commits (from when their histories split from the current branch) into the current branch.<br>
**Master**: Git’s default development Branch<br>
**Origin**: This is the default Upstream Repository<br>
**Pull Request**: Suggests changes into the Master Branch<br>
**Push**: Pushes new changes once they’ve been committed<br>
**Repository**: A group of Commits, Branches and Tags to identify Commits.<br>
**Working Tree**: The directory of files that you are currently working on<br>

# Git Commands Cheat Sheet – **_Configuration_**

**git config –global user.name**: Sets the username to be used for every action<br>
**git config –global user.email**: Sets the email to be used for every action.<br>
**git config –global –edit**: Opens global configuration file in the text editor to enable manual editing.<br>

# Git Cheat Sheet – **_Set Up a Git Repository_**

**git init**: Initializes an empty Git repository in the current project.<br>
**git clone (Repo URL)**: Clones the repository from GitHub to the project folder.<br>
**git clone (Repo URL) (Folder)**: Clones the repository to a specific folder.<br>
**git remote add origin https://github.com/username/(repo_name).git**: Creates a remote repository that points to your current GitHub repository.<br>
**git remote**: Displays the name of remote repositories.<br>
**git remote -v**: Displays the name and URL of remote repositories.<br>
**git remote rm (remote repo name)**: Gets rid of a remote repository.<br>
**git remote set-url origin (git URL)**: Changes a repository URL.<br>
**git fetch**: Obtains the most recent changes from the origin but doesn’t merge them.<br>
**git pull**: Obtains the most recent changes from the origin and merges them.<br>

# Git Cheat Sheet – **_Local File Changes_**

**git add (file name)**: Adds current file changes to staging.<br>
**git add .**: Adds changes for the whole directory to staging but without deleting files.<br>
**git add -A**: Adds every new, modified, and deleted file to staging.<br>
**git rm (file_name)**: Stops tracking a file and gets rid it.<br>
**git rm –cached (file_name)**: Stops tracking the current file.<br>
**git mv (file_name) (new_file_name)**: Alters the filename and gets it ready for Commit.<br>
**git checkout <deleted file name>**: Undeletes a file and gets it ready for Commit. <br>
**git status**: Displays the status of modified files.<br>
**git ls-files –other –ignored –exclude-standard**: Displays a list of each ignored file.<br>
**git diff**: Displays staged changes in the working directory and index.<br>
**git diff –staged**: Displays differences in files between the most recent version and staging.<br>
**git diff (file_name)**: Displays changes between a single file and the most recent Commit.<br>

# Git Commands Cheat Sheet – **_Declare Commits_**

**git commit -m “(message)”** : Saves changes along with a custom message.<br>
**git commit -am “(message)”** : Adds all changes to staging and saves them with a custom message.<br>
**git checkout**: Switches to the provided Commit.<br>
**git show**: Outputs content changes and metadata for a particular Commit.<br>
**git reset –hard**: Rolls back all history and changes for a specific Commit.<br>
**git reset –hard Head**: Rolls back all local changes in the working directory.<br>
**git log**: Displays change history.<br>
**git log -p**: Displays the full page for each Commit.<br>
**git log -oneline**: Displays a list of Commits and a simple message.<br>
**git log –follow (file_name)**: Shows the history of the present file.<br>
**git blame (file_name)**: Displays all changes and the user’s name.<br>
**git stash**: Does an Interim save of all tracked files that have been modified.<br>
**git stash pop**: Restores files that were stashed most recently.<br>
**git stash list**: Displays all stash changesets.<br>
**git stash apply**: Applies the most recent stashed contents.<br>
**git stash drop**: Gets rid of the most recently stashed files. <br>
**git stash apply (stash id)**: Re-applies content of a particular stash by ID. <br>
**git stash drop (stash_id)**: Drops particular stash content by ID. <br>
**git push**: Pushes changes to the Origin. <br>
**git push origin (branch_name)**: Pushes branch to the Origin. <br>
**Git push -f origin (branch_name)**: Force pushes the changes to the Origin.<br>
**git tag (tag_name)**: Specifies a tag for a version.<br>

# Git Commands Cheat Sheet – **_Branching_**

**git branch**: Displays a list of every branch.<br>
**git branch**: Makes a new branch.<br>
**git branch -m**: Changes the name of a branch.<br>
**git branch -a**: Lists both local and remote branches.<br>
**git checkout -b**: Creates a branch and switches to it.<br>
**git checkout**: Changes to a particular branch.<br>
**git checkout -b origin/** : Puts a remote branch from the origin in the local directory.<br>
**git branch -d**: Deletes the specified branch.<br>
**git merge**: Merges the current branch with the master (first checkout to master)<br>
**git rebase**: Integrates changes from one branch into another by rewriting the commit history to produce a linear succession of commits.<br>
**git rebase**: Rebases the current branch onto the base, which can be a Commit ID or a branch name.<br>
**git fetch remote**: Fetches the specified branch from the repository.<br>
**git diff ..** : Shows the differences between two branches.<br>
**git pull –rebase**: Fetches the remote copy of the current branch and rebases it into the local copy.<br>
**git push** –all: Pushes all the local branches to the specified remote repository.<br>

- **_Elements_** shows you the HTML used to build the page you’re looking at, together with any inline CSS.

- **_Console_** deals with JavaScript. It gives you information about interactive elements on a page. In Console, you can write JavaScript to interact with the web page you’re viewing, and it also lets you write messages to yourself in the JavaScript of websites you’re building, which then show up in Console to show that the JS was executed.

- The **_Sources_** tab shows you where all the files that were used to make the website are stored and lets you inspect them.

- The **_Network_** tab shows you all the files that are loading in the URL you’re looking at.You get a waterfall and deep data on all the items loaded, including initiator and time to load that element.

- **_Application_** shows you what’s in your browser storage: in-browser databases like Web SQL, local storage, and more. It also gives you granular control over your cookies.

- **_Security_** gives you basic security information, letting you view a site’s HTTPS certificate and TLS status.

- **_Performance_** panel helps in checking your website performance, such as page speed

- **_Audits_**, which autogenerates reports on site functionality and structure to help developers improve performance.
