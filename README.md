# semantic-release-example

Example semantic release setup. 
This setup is language-agnostic.
It creates a Github release, it does not compile or push any software.
A workflow can be linked to the release event to start the language-specific release process.

## Setup

- [Conventional Commits](https://www.conventionalcommits.org) as the commit message specification
- [Semantic PR](https://github.com/Ezard/semantic-prs) to enforce semantic PR titles
- [semantic-release-action](https://github.com/cycjimmy/semantic-release-action) to automatically create new Github releases based on commit messages
