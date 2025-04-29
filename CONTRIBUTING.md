<!--
SPDX-FileCopyrightText: Contributors to the Quantum Research project

SPDX-License-Identifier: CC-BY-4.0
-->

# How to Contribute

We'd love to accept contributions to this project in any forms. 
You do not need to be a programming or power system expert to make a contribution.
There are just a few small guidelines you need to follow before making a change.

## Ways of contributing

Contribution does not necessarily mean committing code to the repository. 
We recognize different levels of contributions as shown below in increasing order of dedication:

1. Test and use the project. Give feedback on the user experience or suggest new features.
1. Report bugs or security vulnerability
1. Fix bugs.
1. Improve the project with developing new features.

## Filing bugs and change requests

You can file bugs against and change request for the project via GitHub issues. Consult [GitHub Help](https://docs.github.com/en/free-pro-team@latest/github/managing-your-work-on-github/creating-an-issue) for more
information on using GitHub issues.

## Community Guidelines

This project follows the following [Code of Conduct](CODE_OF_CONDUCT.md).

## Signing the Developer Certificate of Origin (DCO)

This project utilize a Developer Certificate of Origin (DCO) to ensure that 
each commit was written by the author or that the author has the appropriate rights 
necessary to contribute the change. 
Specifically, we utilize [Developer Certificate of Origin, Version 1.1](http://developercertificate.org/), 
which is the same mechanism that the Linux® Kernel and many other communities use to manage code contributions. 
The DCO is considered one of the simplest tools for sign-offs from contributors as the representations are 
meant to be easy to read and indicating signoff is done as a part of the commit message.

This means that each commit must include a DCO which looks like this:

`Signed-off-by: Joe Smith <joe.smith@email.com>`

The project requires that the name used is your real name and the e-mail used is your real e-mail. 
Neither anonymous contributors nor those utilizing pseudonyms will be accepted.

There are other great tools out there to manage DCO signoffs for developers to make it much easier to do signoffs:
* Git makes it easy to add this line to your commit messages. Make sure the `user.name` and `user.email` are set in your git configs. Use `-s` or `--signoff` to add the Signed-off-by line to the end of the commit message.
* [Github UI automatic signoff capabilities](https://github.blog/changelog/2022-06-08-admins-can-require-sign-off-on-web-based-commits/) for adding the signoff automatically to commits made with the GitHub browser UI. This one can only be activated by the github org or repo admin. 
* [GitHub UI automatic signoff capabilities via custom plugin]( https://github.com/scottrigby/dco-gh-ui ) for adding the signoff automatically to commits made with the GitHub browser UI
* Additionally, it is possible to use shell scripting to automatically apply the sign-off. For an example for bash to be put into a .bashrc file, see [here](https://wiki.lfenergy.org/display/HOME/Contribution+and+Compliance+Guidelines). 
* Alternatively, you can add `prepare-commit-msg hook` in .git/hooks directory. For an example, see [here](https://github.com/Samsung/ONE-vscode/wiki/ONE-vscode-Developer's-Certificate-of-Origin).

## Code reviews

All patches and contributions, including patches and contributions by project members, require review by one of the maintainers of the project. We
use GitHub pull requests for this purpose. Consult the pull request process below and the
[GitHub Help](https://help.github.com/articles/about-pull-requests/) for more
information on using pull requests


## Attribution

This Contributing.md is adapted from Google
available at
https://github.com/google/new-project/blob/master/docs/contributing.md
