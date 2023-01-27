# Contributing to this Repository

This is a default CONTRIBUTING file designed for all projects (coding projects and otherwise) owned and maintained by the Innovate for Vegas Foundation ("Innovate for Vegas"). This file may be modified per project and where appropriate, but should not compromise the fundamental ethos of the Innovate for Vegas Foundation and its population of Contributors of Creative Works.

An Innovate for Vegas Project ("project") is the sum of the time and creativity ("creative work") of those who add their creative work to a project in any way, and may be composed of zero or more Git Repositories located on GitHub.com or elsewhere, but may include other elements, such as multimedia, visual artwork, written word, and any other relevant items ("components") stored and tracked by other means ("repository"). Each of the components, stored and tracked in whichever form by whichever tools and techniques, shall adopt and be governed by the default LICENSE and CONTRIBUTOR terms of the project to which each belongs, unless otherwise indicated per repository.

A Contributor is any individual person or entity ("contributor") adding materially to a project or repository, by way of new creative work stored or otherwise included as a component of the project ("contribution").

Contributions may also include but are not limited to the following, which we include as creative work:

* Reporting a bug
* Discussing the current state of the code or other parts of a project
* Submitting a fix or other change
* Proposing new features or useful changes
* Becoming a maintainer of a project or project repository or other component(s)

Contributors and contributions to this project repository should adhere to the following rules and guidelines:

## Copyright, Copyright Assignment, and Licensing of Contributed Creative Work

Any and all creative work contributed to this project repository by any contributor must be owned by that contributor, or that contributor must obtain permission from the owner of the creative work explicitly granting permission to contribute that creative work to this repository.

A contributor to this repository shall make any contributions such that they comply with, and will be governed by, the selected license for that project repository, irrevocably and in perpetuity. Contributor agrees to assign copyright of contributed creative work to the Innovate for Vegas Foundation, irrevocably and in perpetuity.

A particular project repository will be developed with a stated license, for example the selected software coding repository default is likely the gpl-3.0 license, though lgpl-3.0 or some similar license might be appropriate in some cases. If at any time during the life of a project or its component repositories, a change in license is necessary, contributors agree to such license changes and will be apprised if possible if and when such changes occur.

Visit the [Choose a License Appendix](https://choosealicense.com/appendix/) for a table of licenses and basic information about them as a starting point for license research and selection.

In many case, a particular project component may not be software. Graphical assets, logos, video, audio, or other media content, written word content for marketing, documentation, etc may be contributed to any project, under a license that is more appropriate for this type of content. A common selection might be one of the Creative Commons licenses, or Open Hardware license schemes.

Visit the [Choose A License non-software page](https://choosealicense.com/non-software/) for some ideas here.

In cases where one single repository contains creative work with different applicable licenses, specific items must be associated with the specific license under which they are made available for use. Ideally, repositories can be constructed and combined to allow a simpler, single-license-per-repository approach.

## Inclusivity + Diversity + Accessibility

Contributors to this repository may be anywhere on a skills/experience spectrum. Teaching and learning are a part of the Innovate for Vegas mission and project development process, and so there may be instances where an incomplete or incorrect repository commit is attempted, a commit must be reversed, perhaps a comment updated, perhaps there was a forgotten file that needs to be added. These things happen. Learn from these and be aware that others may also be learning.

Most source code is typically authored in the development programming language of choice, with variable names, comments, and other documentation created for English-speaking developers (this may also apply to non-code projects, such as documentation, marketing materials, visual cues, audio content, etc). Be aware that some contributors may not speak English as a first language, such that spelling and grammar issues may arise. These are easily edited and are learning opportunities for all.

If possible, projects (code and otherwise) should be designed to be compatible with internationalization and localization (typically i18n and l10n) norms, and should additionally be as compatible as is possible with WAI-ARIA and any other relevant accessibility standards and practices.

At any given point in the development of any project component (repository or otherwise), there may be deviations from these ideals. For example, if a translation to a particular language is not available, if internationalization is not completed for an entire project, if WAI-ARIA compliance is not completely implemented, etc. Every effort must be made to move any project in these directions to meet these goals when possible.

When in doubt, check the CODE_OF_CONDUCT document associated with this repository and with Innovate for Vegas in general. When all else fails, be a [Good Person](https://www.thefreedictionary.com/good+person).

## Project Repository Details

The following are applicable to creative works that are source code or similar and which shall follow common and useful Best Practices for software development, described herein. Best Practices not described herein are left to project and repository teams to adopt and use in order to make developing the project and its components productive, educational, and enjoyable.

**Note:** Top-level projects will usually have a Project Overview repository (ov-project-name convention) and will be tagged, along with other project repositories, with a cfv- naming convention. To become familiar with existing projects if considering participation in one of these, or to suggest a new project, remember that this hierarchy enables contribution of new components to an existing top-level project in addition to starting a new top-level project.

### Main Branch Naming

To be clear immediately, the global transition to *main* as a preferred default branch name over the legacy *master* is in effect for all Innovate for Vegas Foundation project repositories.

### Join a Project

At any given time there may be more than one top-level project in progress in the Innovate for Vegas organization, found on GitHub or perhaps elsewhere for non-code-like projects. Until a better system is identified and implemented, projects participation is managed through the GitHub Teams feature, identifying the team members involved and meeting with them to discuss participation is a great early step. We encourage those interested in joining a project to bring curiosity, skill, or both, as long as there is also interest!

### Start a Project

If there is not an existing project already in progress, suggest one! At the time of this writing, a new project topic begins each month as the previous topic wraps up from ideation and innovation to the full stack of ideation, innovation, implementation, and integration. The project topics align for the most part with a capstone project, and also lean heavily toward civic utility, whether working directly with municipal partners from the start, or later as a project reaches some level of usability for consideration and possibly continued development. With all of this in mind, new project topic ideas, and new components to add to an existing project, are both welcome by way of additional discussion and consideration.

### Getting Started

A new repository should contain at least a README.md stub (always updatable), with at least a reference to this CONTRIBUTING.md and the CODE_OF_CONDUCT.md via links in that README.md file, if there are not to be overriding versions of these files in the new repository. That is, anyone cloning a repository should be able to locate these two files, whether included in the repo clone, or referenced in the organization special community health file locations. For example:

### Project Policies

Unless otherwise and specifically indicated with replacement files in this repository, this project will adhere to the default Innovate for Vegas Foundation policies for Code of Conduct and Contributing, found at

* [Code of Conduct - Innovate for Vegas Foundation](https://github.com/InnovateForVegas/.github/blob/main/CODE_OF_CONDUCT.md)
* [Contributing to this Project - Innovate for Vegas Foundation](https://github.com/InnovateForVegas/.github/blob/main/CONTRIBUTING.md)

### Naming Things

Each Project will be comprised of many parts, some contained within repositories, others elsewhere. A top-level repository with this consistent naming scheme will help others to locate this top level and navigate the project component hierarchy: **ov-(project-name)** .

This is the top-level OverView repository, which will contain a high-level description of the project itself, a project specification if available, and any other relevant high-level resources and information.

Additional repositories added to the project should adhere to a similar naming scheme, for example, **be-(project-name)** for backend code, **fe-(project-name)** for frontend code, **doc-(project-name)** for separate project documentation (perhaps including i18n and l10n work), and more may be added. This convention will, ideally, make navigating the GitHub repository organizational scheme (which is not much) easier as more repositories are added. Note that adding a suffix to **project-name** is acceptable to indicate more detail (eg if there is more than one backend or frontend repo for a given project, for experimentation or other).

Here is a tabular example summary of some naming convention ideas that could make navigating a sea of repositories easier:

| Example Name       | Description                                                                                   |
|--------------------|-----------------------------------------------------------------------------------------------|
| ov-project-name    | Overview repository, top-level summary README, specs, etc                                     |
| be-component-py    | A backend part of the project, written mostly in python                                       |
| fe-component-js    | A frontend part of the project, written in javascript                                         |
| api-project-name   | A stand-alone API coded spec (OpenAPI, etc) separated from language/platform implementation   |
| db-project-sql     | A database schema definition in sql                                                           |
| doc-project        | Project documentation intended for external use (users, developers, etc)                      |
| app-project        | A stand-alone or native application component of a project                                    |
| ui-project         | User Interface designs and elements, possibly in html, svg, or similar textual forms          |

Organization of each repository, and of project components not stored within GitHub or a git repository in general, are likely to have their own particular needs based on programming language, architectural choices, and sensibility. Aside from inclusion of LICENSE and other standard files to comply with the Innovate for Vegas open source development and publishing scheme, naming conventions and repository organization are left to the contributors and consensus per repository.

### Testing and Test Driven Development

Always test your code. This is good advice anywhere and everywhere if you are a software developer (or really, if you make things of any kind, try them out and make sure they work).

While each project, each repository, and each team or group of contributors working on any of these may adopt their own Best Practices by experience, practicality, consensus, etc, it is usually best to make a choice and follow through with it, and to inform newcomers of these practices.

By default, Innovate for Vegas Projects should follow [Test Driven Development](https://www.agilealliance.org/glossary/tdd/) practices and methodologies. There are countless documents, tutorials, demonstrations, and examples in written, audio, and video form, and you yourself likely know someone who is an advocate of TDD. You may also know someone who is most definitely not an advocate of TDD.

If TDD is not for you, the bare minimum **requirement** is that test code be available, that test code is run and passes before code is committed to a repository (on any branch), and that these tests be executable in any automated or manual integration and deployment scheme, and that these tests pass.

If a test fails in an automated or manual integration and deployment pipeline or workflow, **resolving the test failure is the highest priority**.

### GitFlow vs CI/CD

With distributed teams and schedules, voluntary time commitments and differing timelines, the use of [GitFlow](http://datasift.github.io/gitflow/IntroducingGitFlow.html) to organize code changes, feature changes, and other Pull Requests and Branching and whatnot, is sensible. A functional rhythm within a particular development team on a particular project component may deviate slightly from this workflow, but in order to enable easier on-boarding of new contributors of varying skill levels, the GitFlow workflow baseline is a reasonable standard.

However, GitFlow is not strictly compatible with Continuous Integration and Continuous Delivery/Deployment ideals. Using the typical *CI/CD* label is not always applicable.

Use of GitHub Actions (for example) to automate

* pre-commit testing as a form of Continuous Integration is reasonable in combination with GitFlow. While not strictly continuous, it comes close.
* something like Continuous Delivery may be of some use in the case of library code or other shared resources, but is still not strictly continuous in the GitFlow context.
* something like Continuous Deployment is unlikely to be useful during active development, especially if a given project or component are released for general use

It is more likely that a CI/CD pipeline will be useful if a project has been released for wider use (private testing, public beta, full public release), to automate releases which address and fix issues and bugs, and which follow a version release cycle.

There has been much written and said about the compatibility of GitFlow (or most branching strategies) with CI/CD practices, there is likely to be discussion about this per project.

Note that because a project may be made up of multiple repositories, not all code repositories on GitHub.com, some care must be taken to construct a monorepo if that is the desired strategy. Use of Git Submodules and Subtrees is one possibility, multi-repo tools in general should be adopted as needed per project.

Since there may be so much variation in different types of projects and project components, best practices and the better judgment of participants and contributors shall take precedence, so long as the best interests of the Innovate for Vegas Foundation and its overarching goals are a guide (for example, enable and encourage others to spend time contributing to projects, not trying to reverse engineer how they are supposed to build and deploy).

### Commits and Comments

Useful commit messages are helpful in the near term, and throughout all time.

We will generally follow the advice found at [Conventional Commits](https://www.conventionalcommits.org) and you should, too.

### Versioning Things

Version numbers can be confusing once software is released, especially if there are different versions used for testing, release, etc.

We will follow the spec for [Semantic Versioning](https://semver.org/) and you should, too.

### Issues, Bugs, Discussions

Unless there is a specific need for coding projects, the basic services available on the GitHub.com platform for issue tracking and discussion can be used. The creation and use of a GitHub Issue Template per project component is left to the project component maintainer(s) to author as needed.

[Introduction to GitHub Issues](https://docs.github.com/en/issues)

[Introduction to GitHub Discussions](https://docs.github.com/en/discussions)

Because many contributors will not be using GitHub.com for their (non-software or other) contributions, and since it is not common for a casual person to even have a GitHub account, other means will be needed and employed where necessary, with project maintainers making best efforts to track issues, bugs, and fixes.

## Attribution

The Innovate for Vegas Foundation believes completely and totally in the notion that contributors of creative works, with as liberal a definition of "creative works" as can be imagined, shall receive attribution for their time, effort, and creativity.

Where applicable, and where contributions are material and where the contributor has rights to contribute their creative work, attribution shall be made anywhere it is reasonable and useful to do so, including, but not limited to, an AUTHORS file within a repository, in project and component documentation, using attribution schemes on GitHub.com and with other similar tools and platforms, in any InnovateForVegas.org website content, any related website content, and elsewhere. This is not an exhaustive nor comprehensive description of accomplishing this intent, rather an indication that this intent is of the utmost priority.

Wherever creative works and attribution can be added to a CV or used to indicate real world experience for the purposes of career development or job placement, the Innovate for Vegas Foundation will always provide references and detail based on all available attribution information. Thus we will ask that contribution of creative works be properly and correctly attributed throughout a project lifecycle.

Note that GitHub (and GitLab, and less specifically but without causing any issues, git itself) supports several ways to attribute participation:

* [GitHub CODEOWNERS Files](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/about-code-owners)
* [GitHub CITATION Files](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/about-citation-files)
* [GitHub Co-author commit attribution](https://docs.github.com/en/pull-requests/committing-changes-to-your-project/creating-and-editing-commits/creating-a-commit-with-multiple-authors)

GitHub et al. also support AUTHORS and CONTRIBUTORS files per repository, which enable explicit inclusion of (by convention):

* **AUTHORS File** Copyright Holders and other legally responsible parties. For example, if you contribute to a project on behalf of a company or other entity, with permission, that company or entity would be listed in the AUTHORS file. Since copyright of the creative works in the Innovate for Vegas Foundation organization on GitHub, and elsewhere, is assigned to Innovate for Vegas Foundation, but individual contributors might retain copyright on their own original contributions outside of the organization project repositories (and elsewhere), Authors may include all or some of CODEOWNERS contributors.
* **CONTRIBUTORS File** Any and all contributors to a project repository, including testers, collaborators, and any others who directly or indirectly enabled a particular project repository to become more valuable, useful, etc, and who would like attribution (opt-in).

### Privacy

Some may wish to obscure their email address(es), to enable this GitHub provides a *noreply* email address which may be used in place of a public email address for commit attribution and in other places listed above.

For example, the original author of this file, Dan Hugo, could be referred to in commits, AUTHORS, and other places, as one of

* DanHugoDanHugo <1445564+DanHugoDanHugo@users.noreply.github.com>
* DanHugoDanHugo <dhugo@reallycool.com>

The former is provided by GitHub to obscure a public email address, the latter is the default GitHub email address for user DanHugoDanHugo.

For more information please visit:

[GitHub Email Addresses](https://docs.github.com/en/account-and-profile/setting-up-and-managing-your-personal-account-on-github/managing-email-preferences/setting-your-commit-email-address)

## Warranties

Contribution of creative work to any Innovate for Vegas project or project repository is made without warranty, express or implied.

## Code of Conduct

All participation in any aspect of contribution of creative work, and in the activities surrounding those contributions, whether virtual or in-person gatherings and work sessions, written correspondence, code comments, commit comments, issue reports and comments, project and repository discussions hosted on GitHub.com or elsewhere, or anything attached in any way to the Innovate for Vegas Foundation, shall adhere to the published CODE_OF_CONDUCT, available where you found this CONTRIBUTING document.

## This Document

This original CONTRIBUTING document has been composed by and for the Innovate for Vegas Foundation by [Dan Hugo](https://github.com/DanHugoDanHugo). Please find the revision controlled version of this document with history in the GitHub.com [Innovate for Vegas Foundation organization](https://github.com/InnovateForVegas) top-level repository at [CONTRIBUTING.md](https://github.com/InnovateForVegas/.github/blob/main/CONTRIBUTING.md).

This document is published with Copyright 2022 by the Innovate for Vegas Foundation

This document is made available under the license of the repository in which is found, or under the [Creative Commons Attribution-ShareAlike 4.0 International License (cc-by-sa-4.0)](http://creativecommons.org/licenses/by-sa/4.0/) if there is no specified license present or available.
