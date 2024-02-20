
# Commits

## Writing Style

Write commit messages according to the following guidelines:

* Always write commit messages in the present tense, the active voice, and the imperative mood
* Always write concise, title-only commit messages.
* Never punctuate the end of titles

## Prefixes

Prefix commit messages with one of the following labels:

|Label|Meaning|
|-|--------|
|Feature:| Add or remove a feature.|
|Fix:| Fix a problem that affects the satisfaction of a requirement, or the implementation of a feature. |
|Style:| Changes that improve readability.|
|Performance: | Changes that improve space or time complexity.|
|Doc: | Adding, changing, or removing documentation.|
|Test: | Adding, changing, or removing test cases.|
|Git: | Operations that relate to `git`, such as resolving merge conflicts and rewriting commit messages.|
|Meta: | Modify code structure, manage dependencies, update versions, etc. |

# Issues

## Writing Style

Write issues that are concise, informative, and actionable:

**Concise** issues deal with one problem at a time. Such issues can be closed as soon as the one related problem is addressed.

**Informative** issues discuss the context and motivation.

**Actionable** issues provide information on how to solve the problem.

## Process

Close issues with comment. Write issue comments in the following form:

```
<type>[<modifier>].

<comment> 
```

The following table lists values for `<type>`:
|Type|Meaning|
|-|--------|
|Accept||
|Reject||

The following table lists values for <modifier>:
|Modifier|Meaning|
|-|--------|
|In part||
|With future action||
|Pending change (#issue)||

Close child issues with comment. Write issue comments for child issues in the following form:
||


### Link Pull Requests