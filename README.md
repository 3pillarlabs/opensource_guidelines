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
Make sure you don't have any passwords, api keys, etc. in your codebase.
This includes past commits.

If you do, and are willing to sacrifice codebase history, you
can always start a fresh repo and copy over your code.

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


Building Instructions
---


Tests
---
Provide information on how to run the testsuite.

Consider using [Travis-CI](https://travis-ci.org/) to get Continuous
Integration for your project.


Code Style
---
