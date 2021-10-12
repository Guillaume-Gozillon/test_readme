# Contributor's Guide for MarbleBowl

'HOW TO CONTRIBUTE TO MARBLEBOWL PROJECT' accepts PR's (pull requests) with **GitFlow** branching model.
This file is to help **newbies** get familiar with the Marble Bowl's contribution processes.

**Contents**

- [Why GitFlow](#why-gitflow)
- [Getting Started](#getting-started)
- [Submitting a Pull Request](#submitting-a-pull-request)
- [Adding to the Main README](#adding-to-the-main-readme)
- [Adding to the Project File](#adding-to-the-project-file)
- [Helpful Resources](#helpful-resources)


### Why GitFlow

**Parallel Development**

MarbleBowl is a **collaborative open source project**, the development process is done by **iterative cycle**, each feature have to be worked on parallel branches to separate the development from eachother.

GitFlow offer the capability to makes **parallel development very easy**, by isolating new development from finished work. New development (such as new features) is done in feature branches, and is only merged back into main body of code when developers are happy that the code is ready for release.

**Collaboration**

Feature branches also make it easier for multiple developers to **collaborate on the same feature**: each feature branch is a sandbox where the only changes are the changes necessary to get the new feature working. That makes it very easy to see and follow what each collaborator is doing.

| Attempt | #1 | #2 | #3 | #4 | #5 | #6 | #7 | #8 | #9 | #10 | #11 | #12 |
| :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| Seconds | 301 | 283 | 290 | 286 | 289 | 285 | 287 | 287 | 272 | 276 | 269 | 254 |
