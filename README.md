# cookbook

Recettes de cuisine pour le fun

## Introduction

Git basically manages sequences of changes seen as change history. The change sequence *atomic* element is a **commit**.

A **commit** is identified by a **hash** key, with author, date, and a **diff** data, that lists all differences between files: added/deleted files, added/deleted/replaced text in files.

More than one commit can be chained on a given commit, thus creating parallel sequences usually name **branches**. Parallel sequences may also join into one commit, called a **merge commit**.

In GIT a **branch** points a sequence of commits. In fact it is only a label that can be moved to other commits in a sequence or a different sequence.

A **GIT repository** contains .git hidden file, the full commits database.

When **checking out** a branch or commit, GIT setups in the directory the full set of files to the commit state.


## Commit formatting

[https://green-motion.atlassian.net/wiki/spaces/SWDEV/pages/123863041/Git](https://green-motion.atlassian.net/wiki/spaces/SWDEV/pages/123863041/Git)

Semantic Commit Messages
See how a minor change to your commit message style can make you a better programmer.

Format: 

<type>(TicketNumber): <subject>
<scope> is optional
Example
feat(SSW-1515): add hat wobble
^--^  ^------------^
|     |
|     +-> Summary in present tense.
|
+-------> Type: chore, docs, feat, fix, refactor, style, or test.
More Examples:

- `feat`: (new feature for the user, not a new feature for build script)
- `fix`: (bug fix for the user, not a fix to a build script)
- `docs`: (changes to the documentation)
- `style`: (formatting, missing semi colons, etc; no production code change)
- `refactor`: (refactoring production code, eg. renaming a variable)
- `test`: (adding missing tests, refactoring tests; no production code change)
- `chore`: (updating grunt tasks etc; no production code change)

## References

- [https://green-motion.atlassian.net/wiki/spaces/SWDEV/pages/123863041/Git](https://green-motion.atlassian.net/wiki/spaces/SWDEV/pages/123863041/Git)
- https://www.conventionalcommits.org/
- https://seesparkbox.com/foundry/semantic_commit_messages
- http://karma-runner.github.io/1.0/dev/git-commit-msg.html