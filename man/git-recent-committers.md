# git-recent-committers(1)

## NAME
git-recent-committers - List people who committed in the last N days

## SYNOPSIS
`git recent-committers` [-n <days>]

## DESCRIPTION
Lists authors who made at least one commit in the last N days, 
with their commit count in that period.

## OPTIONS
-n <days>
: Number of days to look back. Defaults to 7 or GIT_RECENT_COMMITTERS_DAYS.

## ENVIRONMENT VARIABLES
GIT_RECENT_COMMITTERS_DAYS
: Default number of days to use if -n is not provided.

## EXAMPLES
Show committers from the last 30 days:
    $ git recent-committers -n 30