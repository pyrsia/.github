# Contributing to Pyrsia

We like to pronounce it `/pərsēə/` or _[ pir-see-ah ]_. 😉 [Listen here](https://www.youtube.com/watch?v=yvFiJGMqM_Q&t=77s).

The following summarizes the process for contributing to the Pyrsia project.

## Code of Conduct

We follow the OpenSSF's 🛡️ (Open Source Security Foundation) [code of conduct](https://openssf.org/community/code-of-conduct/).

## Dev-flow

Pyrsia follows the ["Forking Workflow"](https://blog.devgenius.io/git-forking-workflow-bbba0226d39c). You can see GitHub's
[About collaborative development models](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/getting-started/about-collaborative-development-models#fork-and-pull-model) for more details.

To contribute follow the next steps:

1. Comment in the corresponding issue that you want to contribute. If there is no open issue, we strongly suggest
   opening one to gather feedback from the team.
2. Fork the [Pyrsia repository](https://github.com/pyrsia/pyrsia/fork) and [create a branch](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-and-deleting-branches-within-your-repository#creating-a-branch)
   from the `main` branch and develop your fix and/or feature as discussed in previous step. See
   [About forks](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/working-with-forks/about-forks) for help.
3. Try to keep your branch updated with the `main` branch to avoid conflicts. See 
   [Syncing a fork](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/working-with-forks/syncing-a-fork).
4. Please make sure to [link any related issue](https://docs.github.com/en/issues/tracking-your-work-with-issues/linking-a-pull-request-to-an-issue)
   to the PR, referring to the issue of step 1.

The `pyrsia` organization maintainers will review and help with merge accepted changes. Simply request reivew from [`@pyrsia/collaborators`](https://github.com/orgs/pyrsia/teams/collaborators) and two members will be selected.

### Pull Requests

PRs are a great way to share what you are working on and get early feedback. Make sure to open as a draft so other know the state.
Before opening a pull request it's recommended to "clean your commit history", this makes it easier to review by breaking down the work
and removing some of the cluter and noise of regular development. Check out [this article](https://medium.com/@catalinaturlea/clean-git-history-a-step-by-step-guide-eefc0ad8696d) and [this guide](https://about.gitlab.com/blog/2018/06/07/keeping-git-commit-history-clean/) to learn more.

When PRs are "read for review", there's a few house keeping 🧹 items to keep in mind:

- Make sure to give your PRs a **great title**. These will be the commit messages and should be treated as such.
- Do _not_ worry about squashing, that is done automatically by GitHub.
  - It's ideal to clean up any commit messages before confirming the merge to reduce the noise.
- Try to avoid force pushing you branch. GitHub forces reviewers to restart since it loses their progress.
- When syncronizing your branch, prefer using merge. Check out [Syncing a fork](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/working-with-forks/syncing-a-fork) for more details and guidance.

#### Approval Processes

Request reviews from the [`@pyrsia/collaborators`](https://github.com/orgs/pyrsia/teams/collaborators) team to assign team members for the PR.
They are responsible for making sure the PR is reviewed in a timely manner; they are expected to make time. Approvals are **not** limtied to the assigned reviewers, anyone on the team can and should review each PR.

Specific indivudals or "topic teams" may also be assigned (only after collaborators has been assigned so the GitHub automation can work properly). Approvals from "topic teams" are highly sought after but pull requests are _strongly encouraged_ to include reviews from the team at large.

All pull requests require:

- 2 approvals (from any team member)
- All required checks passing

If there are optional checks that fail, it's best to ask the reviewers and bring up the failure at the next team meeting.

#### Merging Suggestions

- Cleanup the commit message and description, remove lines like "wip" or "fix typo" so the reader has less clutter to sort through

### Project Board

[Learn more](https://docs.github.com/en/issues/organizing-your-work-with-project-boards/managing-project-boards/about-project-boards)

All open tickets related to ongoing work are tracked in a [project board](https://docs.github.com/en/issues/organizing-your-work-with-project-boards). 
Upcomming, future and completed work [here](https://github.com/orgs/pyrsia/projects/2).

#### Labels

[Learn how](https://docs.github.com/en/issues/using-labels-and-milestones-to-track-work/managing-labels#applying-a-label)

Labels are used to sort and describe issues and pull requests. Some labels are usually reserved for one or the other, though most labels may be applied to both.

They may be used to:

- highlight the state of completion, such as "Triage" or "Blocked"
- organizing according to the source code relevant to issues or the source code changed by pull requests, such as "Blockchain", "Discovery", or "Network"

## Legal

You will need to complete a Contributor License Agreement (CLA) before your pull request can be accepted. This agreement testifies that you are granting us permission to use the source code you are submitting, and that this work is being submitted under appropriate license that we can use it.

For each pull request, all commit authors are required to sign the CLA. A copy can be found [here](https://jfrog.com/cla/). We are using [CLA Assistant](https://cla-assistant.io/) which requires commit email to match your GitHub account. You can view signed CLAs through their site. 
