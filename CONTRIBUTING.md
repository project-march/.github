# Contributing to Project March
The following are a set of guidelines and steps to contributing to the
[Project March organization] on GitHub.

[Project March organization]: https://github.com/project-march

## Code of Conduct
This project and everyone participating in it is governed by the [Project
March Code of Conduct]. By participating, you are expected to uphold this
code. Please report unacceptable behavior to info@projectmarch.nl.

[Project March Code of Conduct]: CODE_OF_CONDUCT.md

## What should I know before I get started
Project March builds the March exoskeleton using the [ROS] framework. Before
contributing code, you must have [ROS Melodic] installed and have Project
March workspace installed. See
https://docs.projectmarch.nl/doc/getting_started/create_your_workspace.html
for steps on how to do this.

[ROS]: https://www.ros.org
[ROS Melodic]: https://wiki.ros.org/melodic

### Repositories


### ROS Packages


### Documentation


### Committing


## Contributing steps

1. Create a new branch from the latest `develop`, if it exists in the
   repository, otherwise create a branch from `master` (or [fork], if you are
   not a member of the org). The branch name should start with `feature/` or
   `fix/`, if you are implementing a new feature or fixing something
   respectively. The branch name should end with a Jira issue key (if you have
   one) and a short description of the issue separated by `-`. Some examples
   include: `feature/PM-79-add-coverage-report` and
   `fix/PM-341-mock-as-dependencies`.
2. Implement your new feature or fix.
3. Add tests for your new feature or fix when possible. See
   https://docs.projectmarch.nl/doc/development/testing.html for more info on
   testing.
4. Make sure your code style adheres to the guidelines. See
   https://docs.projectmarch.nl/doc/development/style_guide.html for checking
   your code style.
5. Push your changes.
6. Create a pull request against the branch you branched from.
7. Fill in the pull request template to describe your changes.
8. Wait for review 🎉

[fork]: https://guides.github.com/activities/forking/

