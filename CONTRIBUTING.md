
# Commits

## Writing Style

Write commit messages according to the following guidelines:

* Write in the present tense, the active voice, and the imperative mood.
* Always write concise, title-only commit messages.
* Never punctuate the end of titles.

## Prefixes

Prefix commit messages with one of the following labels:

|Label|Meaning|
|-|--------|
|`Feature:`| Add or remove a feature.|
|`Fix:`| Fix a problem that affects the satisfaction of a requirement, or the implementation of a feature. |
|`Style:`| Changes that improve readability.|
|`Performance:`| Changes that improve space or time complexity.|
|`Doc`: | Adding, changing, or removing documentation.|
|`Test`: | Adding, changing, or removing test cases.|
|`Git`: | Operations that relate to `git`, such as resolving merge conflicts and rewriting commit messages.|
|`Meta`: | Modify code structure, manage dependencies, update versions, etc. |

# Issues

## Writing Issues

Write issues that are concise, informative, and actionable:

**Concise** issues deal with one problem at a time. Such issues can be closed as soon as the one related problem is addressed.

**Informative** issues discuss the context and motivation.

**Actionable** issues provide information on how to solve the problem.

## Resolving Issues

### Comment

Start issue comments with one of the following types:

|Comment Type|Meaning|
|-|--------|
|Accept|Acceptance of an external issue|
|Reject|Rejection of an external issue|
|Resolve|Resolution of an internal issue|
|Comment|Comment does not resolve the issue|
	
Following the type, note actions after acceptance (or resolution) and reasons for rejection, according to the following syntax:

![](media/main-issue-format.svg)


### Commits for Issues
In commits that address a particular issue, reference that issue. When closing an issue, reference all commits that reference that issue.

![](media/issue-in-commit.svg)

### Child Issues
Modifiers `future action` and `pending change` create child issues. Write child issues in reference to the parent.

![](media/issue-child.svg)

The workflow for spawning and closing child issues is as follows. Note to use `Resolve` and not `Accept`, since child issues are created by developers.

![](media/issue-resolution-process.svg)
