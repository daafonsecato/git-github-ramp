# Git Flow Katas Exercise

An exercise for learning the [git-flow branching model](http://nvie.com/posts/a-successful-git-branching-model/), inspired in a [previous exercise](https://github.com/rferri-gr8/git-flow-exercise). This exercise will walk your team through a full release cycle for an example application.

##  OBJECTIVES
1.	Apprehend basic and most used Git commands
2.	Apprehend GitHub
3.	Extra: Apprehend Git Flow


## Background 

The print magazine _Onlyrics_ has asked your firm to build and maintain an app so they can share song information and fun facts with their rhythmic audience.

The typical development cycle for the project is as follows:

- On the 1<sup>st</sup> of every month, your team receives a list of each writer's picks for the song of the month.
- On the 15<sup>th</sup> of every month, the new version of the app is pushed to a staging server where the magazine's editors can do a final review.
- On the last day of the month, the new version of the app is pushed to production.

Development for this project began in June. It is now the beginning of July and the development cycle for `v1.1.0` of the app has begun.

## Getting Started

Your team will have both roles of Developers and Maintainers for all the people in the team. As Maintainers, you will be responsible for cutting new releases and accepting Pull Requests from other team members. As Maintainers you should have write access to this repository and as Developers should have read access in the other teammate repositories.

### Project Structure
* Application code can be found in the [`/app/`](/app/) folder.
* The application contains a file named [`VERSION`](/app/VERSION) that contains the major, minor, and patch numbers for the project.
* Source files are written in markdown and can be identified by the `.md` file extension.

## Next

Next, we will walk through the process of creating a GitHub Fork and the local clone of this repository.

[Go](/walkthrough/1-setup.md)

## Quick Links

- [1. Setup](/walkthrough/1-setup.md)
- [2. Feature Branches](/walkthrough/2-feature-branches.md)
- [3. Code Review](/walkthrough/3-code-review.md)
- [4. Fetching the Latest](/walkthrough/4-fetching-latest.md)
- [5. Hotfix](/walkthrough/5-hotfix.md)
- [6. Release Branch](/walkthrough/6-release-branch.md)
- [7. Release Bugs](/walkthrough/7-release-bugs.md)
- [8. Completed Release](/walkthrough/8-completed-release.md)
