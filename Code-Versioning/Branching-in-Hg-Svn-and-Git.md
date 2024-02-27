Why is branching with Mercurial or git easier than with SVN?
Subversion (SVN):

SVN is a centralized version control system (VCS) where there is a single central repository that stores all files and their history.
Branching in SVN involves creating a copy of the entire repository or a specific directory within the repository. This can be done using the svn copy command.
Branches in SVN are typically created within the repository structure, and merging changes between branches often requires explicit tracking of revisions and can be somewhat manual.
Branches in SVN are heavy in terms of storage and can be slow to create and manage, especially for larger projects.
Mercurial (Hg):

Mercurial is a distributed version control system (DVCS) where each user has their own repository, complete with the entire history of the project.
Branching in Mercurial is relatively straightforward. You can create a new branch using the hg branch command, and it's a lightweight operation because branches are stored as part of the repository's metadata.
Mercurial has efficient mechanisms for merging changes between branches, often with automatic tracking of changesets and merging of divergent development lines.
Git:

Git is also a distributed version control system like Mercurial.
Branching in Git is extremely lightweight and is considered one of its defining features. Creating a new branch in Git is as simple as running git branch <branch_name> or git checkout -b <branch_name> to create and switch to a new branch simultaneously.
Git branches are just pointers to specific commits in the repository, which makes them incredibly cheap to create and manage.
Git's powerful merging and rebasing capabilities make it relatively painless to merge changes between branches, and it often automates much of the process.
Git's branching model, particularly with workflows like Git Flow or GitHub Flow, encourages frequent branching and merging, making it easier to manage complex development scenarios.
Comparison:

Ease of Creation: Both Mercurial and Git offer lightweight branching, making it easy to create and manage branches compared to SVN. However, Git's branching model is considered slightly more intuitive and efficient.

Merging and Tracking: Mercurial and Git both provide efficient mechanisms for merging changes between branches, but Git's tooling and branching model arguably make it easier to track changes and manage merges, especially in complex scenarios.

Centralization vs. Distribution: SVN is centralized, which affects how branching and merging are handled, whereas Mercurial and Git are distributed, allowing each user to have their own repository, which simplifies branching and merging operations.

Community and Tooling: Git has a larger community and ecosystem with more extensive tooling and resources available, which can make branching and merging workflows more streamlined and accessible.

In summary, branching with Mercurial or Git is generally considered easier than with SVN due to their distributed nature, lightweight branching models, and more advanced merging capabilities. Among Mercurial and Git, Git's branching model and tooling often make it the preferred choice for many developers.
