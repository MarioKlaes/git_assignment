```markdown
# Git Assignment - MarioKlaes
```

a. What is an _issue_?

> GitHub Issues are items you can create in a repository to plan, discuss and track work.
> 
> Source: https://docs.github.com/en/issues/tracking-your-work-with-issues/about-issues

b. What is a _pull request_?

> A _pull request_ is created whenver a change to the _main_ branch is required. It allow reviews before actually change the code on the _main_ branch.

c. How do I open up a _pull request_?

> At _github_ select the repo that you want to check por _pull requests_
> 
> Click the menu _Pull requesdts_ on the top-left of the page to see all _pull requests_

d. Give me a step by step guide on how to add someone to your repository.

> At the main page of your repo, click on _Settings_
>
> Click on the left-side menu, click on _Collaborators_
>
> At the center of the page, click on the green button _Add people_
>
> A pop-up window will open.
>
> Type the _user name_ or _full name_ or _email_ of the person you would like to add
>
> Once you find the person click on _Add ... to this repository_
>
> Note: the ... represents the user name of the collaborator

e. What is the difference between `git` and `GitHub`?

> git - it is a distributed version control system that manage file versions (source code, data, etc.)
> Github - it is an internet implementation/service that uses git and host git repositories

f. What does `git diff` do?

> `git diff` - list the differences (changes) between the local file not commited and the latest commit of the same file.
> 
> Note: when you Git Add then Git Commit a file the _git diff_ will no longer show any result. 
> Once you commit there will be no differences between the commited version and local version.

g. What is the `main` branch?

> The `main` branch is the _master_ branch and should represent the latest stable state of the repository.

h. Besides our initial commit if it is a new repository, should we directly push our changes directly into the `main` branch?

> A good practice is never _git push_ files directlu to the `main` branch.
> A collaborator should create a _branch_ to work on code changes.
> Once the changes are done: git add, git commit, git push the code on the branch
> After that the collaborator has to create a _Pull request_ so the changes can be reviewed/approved before change the 'main' code
> 
> To suport this good practice the owner of the repo should add a branch protection rule to prevent direct changes to it.
> This rule will enforce the good practice of use _Pull request_ to propose and review changes.
