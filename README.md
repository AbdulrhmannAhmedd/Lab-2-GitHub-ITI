git branch -d test


To delete a remote branch:
git push origin --delete dev


To list tags locally:
git tag


To delete tag locally:
git tag -d v1.2

To delete tag remotely:
git push origin --delete v1.2


What is rebase?
Rebase is a command that allows you to reapply commits from one branch onto another, effectively moving or "replaying" your work onto a different base.
It helps in maintaining a clean and linear commit history by avoiding the "merge commits" that are created when you merge branches.

Example:
You want to update your feature branch with the latest changes from main before merging it back into main?

Rebasing will:

1-Temporarily remove your feature branch commits.
2-Update your feature branch with the latest commits from the main branch.
3-Reapply your feature branch commits on top of the updated main branch.


What is pull request?

It's a way for merging and pushing but in organized way for review process:

1-Propose changes: Submit your work (commits) for review.
2-Review changes: Team members or collaborators can review, discuss, and suggest improvements.
3-Merge changes: After the review process, the changes can be merged into the target branch


![Hey Enginner!!!](https://cdn.create.vista.com/api/media/small/57087087/stock-photo-sunset-over-nerja-andalucia-spain)
