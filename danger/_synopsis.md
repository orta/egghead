Danger is a CI tool which you use to create tests for a GitHub PR. For example:

* Check for a CHANGELOG entry (rxjs)
* Always include a JIRA ticket reference in a PR
* Check that app code changes includes test code changes (apollo-client / react-native)
* Warn on edits to specific files (styled-components)
* Warn on large PRs (rxjs) 

It provides feedback inline inside your PR, and as new commits come in it will update that message. Danger is generally used on larger OSS projects and it’s great for ensuring team-wide project consistency.

* Introducing Danger to a repo (setup + hello world on a PR)
* Writing a check that someone is assigned to a PR ( exploring `danger.github.x` )
* How to make changes to a Dangerfile locally and test against an existing PR ( understanding the workflow )
* Understanding message, warn, fail and markdown ( exploring how to give feedback )
* Writing a rule that fails if you don’t include a CHANGELOG entry ( more DSL exploration, with application )
* Taking the results of a CI script and passing it back to the PR ( e.g. making a linter provide details in a message )
* Creating a danger plugin with some of your rules (e.g. how to share common rules )
* Setting up Flow/TypeScript for you Dangerfile ( how to have better tooling )
