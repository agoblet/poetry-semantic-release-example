# semantic-release-example

This repository contains an example semantic release setup.
It automatically creates Github releases, increasing the version based on the commit message of a merged pull request.
This setup is language-agnostic since it just creates Github releases and does not compile or publish any software.
A workflow can be linked to the release [event](https://docs.github.com/en/actions/using-workflows/events-that-trigger-workflows#release) to start the language-specific release process.

## Setup


- [Conventional Commits](https://www.conventionalcommits.org) as the commit message specification
- [Semantic PR](https://github.com/Ezard/semantic-prs) to enforce semantic PR titles
- [semantic-release-action](https://github.com/cycjimmy/semantic-release-action) to automatically create new Github releases based on commit messages
