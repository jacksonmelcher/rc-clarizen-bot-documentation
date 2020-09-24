# Glip Clarizen Bot

Clarizen Bot lets you stay up-to-date with your projects without leaving Glip. Get immediate information you need without having to remember tricky commands.
Once you’ve connected with Clarizen, Clarizen Bot can retrieve project statuses, project states, task statuses, and task states for you, with more features coming soon.

# Availibility

Clarizen bot is in its first stages of development and is only available only to RC employees at this time.

# We want your feedback

We'd love to hear your feedback about Clarizen Bot. If you spot bugs or have features that you'd really like to see, please check out the [bug and feature sumbission form](https://forms.gle/KKYKVVoxUN5z32dY7).

# Getting started

### Installation

Clarizen bot has already been installed on Glip and all you need to do is run a global search for "Clarizen" and click the bot that looks like this:
![Global Search screenshot](images/search.png)

# Commands

Right now, Clarizen bot understands a few commands. For help with syntax please refer to the [syntax section](#Syntax).

```
{ project | task } status [ on-track | off-track | at-risk | not-active ]
```

```
{ project | task } state [ active| not-active ]
```

```
help
```

# Examples

![](images/exapmle.gif)

`project status` - Lists all projects and their status
`project state` - Lists all projects and their state
`task status` - Lists all tasks and their status
`task state` - Lists all tasks and their state
`task status on-track` - Lists all tasks with a status of 'On Track'
`task status off-track` - Lists all tasks with a status of 'Off Track'
`task status at-rist` - Lists all tasks with a status of 'At Risk'

### Syntax

##### Required commands

-   Required commands look like this: `example`
    -   this means you must type `example` or the command won't work.
-   Required commands where there is a choice are wrapped with `{}`.
    -   `{yes | no}` - means you must choose `yes` or `no` or the command won't work.

##### Optional commands

-   Optional commands are wrapped in `[]`
    -   `[cat | dog]` - means you can choose to add cat or dog at that location but its not required.
