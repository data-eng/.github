# Collaborating on Git

## Branching off to work on something

All work should be towards resolving an Issue, even if you open the Issue,
finish the work, and close it without collaborating with anybody else for
this issue. This is for the sake of having all commits link back to a
description of a feature or a fix, and can help when our future selfs will
be wondering why a certain change was made.

Create the new branch from the Issue page or link an existing branch to the
Issue from the "Development" button.

Commit often while working on the issue, trying to separate individual
steps of the solution into different commits. Ideally (although practically
this is not always possible) all commits are revertible, so individual
commits bundle together inter-dependent changes. Do not be worried that you
may have too many commits, but do be worried that you may have too few
commits.

If you want to curate the history, do not be shy about rebasing the branch
to squash together two or more commits that, in hindsight, should be one.
If acrively collaborating on the same branch, warn you collaborators that
you are about to rebase, so they know that they must checkout a fresh copy
of the branch.

Once you are ready, open a Pull Request to merge the branch onto the `master`
branch (or the `dev` branch for bigger projects with a two-step process
to publish a new feature).

