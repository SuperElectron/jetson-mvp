Contributing
============

All contributions are welcome to this project!
Any questions you have, please don't hesitate to reach out!

```text
matmccann@gmail.com
```

How to contribute
-----------------

-  **File an issue** - if you found a bug, want to request an enhancement, or want to implement something (bug fix or feature).
-  **Send a pull request** - if you want to contribute code. Please be sure to file an issue first.


Pull request best practices
---------------------------


## Step 1: File an issue

Include these main fields in your issue

- **summary** : a high level summary to recap the type of issue with a TLDR for quick review.
- **description** : detail the issue, feature, bug, feature etc.
- **request** : describe `work to be done`, or ask for guidance.


## Step 2: Set up your development

Fork the repository so that you have your own copy of our repository.

You MUST add `upstream source` like this:

```bash
git remote add upstream git@github.com:SuperElectron/jetson-mvp.git
```

Then, then create a branch with a descriptive name AND start coding.

```bash
git branch -b feature/add-docker-security
```

## Step 3: Submit a pull Request

**Submit a pull request**

Please squash your commits into a single commit before merging your PR.
- [reference for squash](https://kubernetes.io/docs/contribute/new-content/open-a-pr/#squashing-commits)

Mention the issue number - it helps us track better.

```bash
# commit with issue number for final commit
git commit -s -am "Add security to docker image (issue #112)"
git push 
```

**Rebase**

Add your changes on top of what's already in upstream, minimizing merge issues.
Before sending a pull request, rebase against upstream, such as:

```bash
git fetch upstream
git rebase upstream/master
```

## Step 6: Send the pull request

Submit it, and email here to connect with me.

```text
matmccann@gmail.com
```
