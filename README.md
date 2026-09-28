# git-practice
This is a git practice repo, showcasing multiple git operations for practice puproses.

## Repository Layout


## Branch Creation
Any changes to the repo files should be done in a seprate branch then merged back into main via a PR

### Branch naming
branch should be split into paths feature, bug, docs or misc followed by the name of the issue/ticket.
i.e
feature/<issue-name>
bug/<issue-name>
docs/<issue-name>

## Pull Request (PR)
in order to create a PR a branch must be created, changes committed, then pushed to origin.


### PR template
Title: <Issue-Title>

Description: 

"""
## Reason for change
- <Reason for the change in plain english or from issue>

## Changes
- <list of changes>


"""

## Testing
Any Changes must run through internat testing script to ensure validaty of the changes in runtime and against real data.

### Requirements
Python 3 must be installed

### Execution
Run the test command line through python3 git-practive/tests/eval-all.py