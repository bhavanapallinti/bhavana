# docs
The open-source repo for docs.github.com
CLI Design Template

! Do not edit this template directly. Please make a copy ! 
 





















-----

Components

Syntax

[branch]
(label)
owner/repo


Prompts

? Yes/No Prompt [y/N]

? Short text prompt (Auto fill)

? Long text prompt [(e) to launch vim, enter to skip] 

? Single choice prompt [Use arrows to move, type to filter]
> Choice focused
  Choice 
  Choice

? Multi select prompt [Use arrows to move, space to select, type to filter]
> [x]  Choice selected and focused
  [x]  Choice selected
  [ ]  Projects
  [ ]  Milestone



State

#123 Open issue or pull request
#123 Closed issue pull request
#123 Merged pull request
#123 Draft pull request

✓ Checks passing
✓ Approved
- Review requested
+ Changes requested

✓ Success message
! Alert
✗ Error message (ideal)
error message (current)

✓ Item closed
✓ Item merged


Loading spinner

⣟ Action...



Lists

$ gh issue list 

Showing 3 of 222 issues in cli/cli

#1360  Ability to ski...                     about 2 days ago
#1358  Provide extra ...  (enhancement)      about 3 days ago
#1354  Add ability to...  (enhancement, ...  about 3 days ago



Detail view



Ability to skip confirmation via a flag
Open • AliabbasMerchant opened about 2 days ago • 1 comment


#1330 proposes to add confirmation to risky commands. It is a nice feature to have, but in order to support proper scriptability, we should support a flag (preferably  -y , like in most CLIs), to skip asking for confirmation. So for each of the 4 commands mentioned there (and possibly even more in the future), we should add support for the  -y  flag                                       


View this issue on GitHub: https://github.com/cli/cli/issues/1360


Headers


Creating issue in cli/cli

Showing 30 of 226 issues in cli/cli

Relevant pull requests in cli/cli

cli/cli
GitHub’s official command line tool

Default branch is not being prioritized
Closed • tierninho opened about 6 months ago • 1 comment



Empty states

Current branch
  There is no pull request associated with [master]

Created by you
  You have no open pull requests

Requesting a code review from you
  You have no pull requests to review

No pull requests match your search in cli/cli

No issues match your search in cli/cli

There are no open issues in ampinsk/create-test




Help page

$ gh

Work seamlessly with GitHub from the command line. 

USAGE
  gh <command> <subcommand> [flags]
  Commands are run inside of a GitHub repository.

CORE COMMANDS
  issue:       Create and view issues
  pr:          Create, view, and checkout pull requests
  repo:        Create, clone, fork, and view repositories

ADDITIONAL COMMANDS
  help:        Help about any command
  config:      Set and get preferences
  completion:  Generate shell completion scripts

FLAGS
  -h, --help:              Show help for command
  -v, --version:           Show gh version

EXAMPLES
  $ gh issue create
  $ gh pr list
  $ gh repo fork

LEARN MORE
  Use "gh [command] [subcommand] --help" for more information about a command.
  Read the manual at <http://cli.github.com/manual>

FEEDBACK 
  Fill out our feedback form <https://forms.gle/umxd3h31c7aMQFKG7>
  Open an issue using “gh issue create -R cli/cli”


