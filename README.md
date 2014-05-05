3Pillar Open-Source Guidelines
===

This document aims to provide some simple guidelines for publishing
projects under an Open-Source License.


Checklist
---
 * doulecheck code for credentials (including history)
 * pick a license
 * provide a README
 * building instructions
 * tests and instructions on how to run them
 * code style


Credentials
---
Make sure you don't have any passwords, api keys, etc. in your
codebase. This includes past commits.

If you do, and are willing to sacrifice codebase history, you can
always start a fresh repo and copy over your code.

Alternatively you can use git rebase --interactive to rewrite past
commits.


Picking a license
---
Simply pushing something to a Github public repo doesn't make it
Open-Source. You need to explicitly add a license to your project.


Providing a README
---
What is this project about?
Who should use it?
What are the steps to contribute to this project?


Building Instructions
---
Should be contained in a INSTALL file and should provide detailed


Development practices
---
* Provide information on how to run the testsuite.
* Consider using [Travis-CI](https://travis-ci.org/) to get Continuous
  Integration for your project.
* Consider using
  [github's pull request system](https://help.github.com/articles/using-pull-requests)
  to code review and integrate proposed patches
* Make sure you have (preferable annotated) tags for stable releases
* When uploading for the first time an existing project to github, try
  to preserve the existing history as much as possible
* Have responsible for each project which can integrate pull requests


Code Style
---
Try to use a recognized style for the programming language

* Python - [PEP8](http://legacy.python.org/dev/peps/pep-0008/)
