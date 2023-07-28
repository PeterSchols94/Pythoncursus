# Introduction to Git

In this module you will learn the basics of Git.

Git is a so-called version control system (VCS). It is, simply put, a Microsoft Word Track Changes for source code: it keeps track of every single change made to a piece of code i.e. which lines are added/delete by whom, when and why. Changes are bundled in commits and each commit is stored on disk alongside a message describing the applied changes. Past commits are browseable which makes it easy to follow the implementation process from start to finish.

GitHub/GitLab are online services for collaborating on Git-versioned software projects. You can share your code, others can browse, download and keep it in sync by `pull`ing it regularly, and easily contribute additions/fixes through `merge requests`. Issues, bugs and feature requests are submitted in the `issue tracker` where they can be discussed and `closed` once fixed/implemented.

Git enable an open, transparent and traceable, and collaborative software development workflow. A perfect match for today's call for open data and open science.

The best way to come to grips with Git, the Git-based online platforms and the workflow they allow/induce is to roll up your sleeves and dive in. To fully appreciate Git's added value we believe it is best to interact with it first and reflect on it later. In this chapter you will therefore complete the exercise first and only then move on to the bigger picture. Curious to know why you should bother with Git? Jump straight to the Reflection section.

## Rationale

In recent years Git has become the corner stone of open source software. It sits at the basis of GitHub and GitLab both of which host thousands of open source software projects. A basic proficiency with Git and GitLab/Hub will give you access to this treasure trove of software libraries and the broader open source software ecosystem that has grown around them.

More importantly, proper use of Git (or any version control system for that matter) will greatly aid you in your software development activities. Keeping code in a VCS relieves you from manual versioning and the resulting "version hell" formed by a multitude of files named `version2-final_reviewed_final.txt`. VCSs reduce change anxiety i.e. the reluctance to change/improve/experiment with a piece of code born from the fear of braking or losing working code. Finally, the commits messages force you to divide your work in small(er) (and therefore manageable) chunks; the commit messages force you to keep the bigger piture in sight and reason about your coding/design decisions on a more abstract level.

Git's benefits become really apparent once you need to share your code and/or collaborate with others (e.g. tutors, colleagues, fellow researchers). Git's changelog keeps track of who added which functionality when and why; accepting code from others is fairly straightforward; going back to a previous snapshot in case something goes wrong is doable as well.

Git's collaborative features have become extremely popular in recent years. An increasing number of people are starting to apply the Git-based workflow to non-coding projects.

## Outcomes

- basic proficiency in interacting with Git through the command line: checking diffs and logs, and commiting files and changes
- familiarity with Git: browsing files, viewing a project's history and submitting issues
- basic proficiency with the Git-induced collaborative workflow: forking projects, creating merging requests and submitting issues
