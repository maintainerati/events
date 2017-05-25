# Dealing with large & Growing PR Backlog

Some of this also applies to issues, though most of the discussion was focused on PRs

## Stopping at source

How can we stop issues & PRs from being raised in the first place?

* Define what's out of scope
  * Negative Roadmaps
    * Useful place to record common requests that the project isn't interested it
    * Need to document *why* this decision has been reached
    * GitHub Issue template should link to this
* Make it easy to find duplicates
  * GitHub labels make it easy to find related PRs & issues
  * Triage process needs to include updating summary line to make future searching easier
  * For PRs having a bot that lists other PRs in flight that touch similar areas may help avoid duplicates and get extra reviewers

## Process

* Is it obvious to a (first time) contributor what the full process is from PR being raised to merged and released is
  * Is it clearly documented how you progress from one stage to the next
  * If a contributor asks "What do I need to do next" this may be an indication that further improvements in the process & communication are needed
* Help people to help you, what can they do to help you review the backlog
* Transparency - Link to roadmaps for version: n+2 which includes rough ideas of how we'd expect the feature to be implemented
* Point to documentation/rules, not a personal view

Documentation is key to helping with the above


## Automated (Style) Testing

* A good thing
* Thoughts on style review do vary from person to person, and organisation to organisation
* Having documented and enforced via CI can reduce discussion in PR that are not relevant
* Pointing to documentation allows you to say "They are the guidelines" rather than "my personal views are you need to do X,Y,Z"



## When do you close PRs

Why might a PR (or issue) need closing:
* Scope - Is the scope/issue that the PR is trying to do
* Duplicate/similar PR existing PR exists - Requires you
* Missing context
* Attacking the wrong problem
* Divide and concur approach needed - rather than single huge (unreviewable) PR
* Old PRs: No one has responded/commented in a while, possible indication that this isn't that important

General feel of our group was we need to close issues earlier, rather than giving "false hope" that someone will look at it


## Reviewing the whole backlog

* When reviewing the whole backlog and finding something simple you could
  * Just do it
  * Add a label to indicate this is possibly a good task for a contributor
    * contributing.md should reference this, make it easy for people to help
  * If the PR just needs a rebase, cherry pick and do it yourself rather than forcing the contributor to do so
  * If the PR just needs a simple fix
    * Possibly fix yourself and push to their branch and merge
    * Detail what and why you've made the change - educate them
    * Avoids another loop around with the contributor
    * Careful balance needed, it may not be right for you to work on every PR
* Possibly create a triage rota for incoming issues
* Possibly have each team member review the whole backlog (doesn't have to be in one go)

## Misc discussions

* Popular but abandoned projects
  * These can have very varied rates of activity
* Two stage reviews
  * 30,000 foot review - At a high level does this make sense. Can be done as part of triage to give quick feedback
  * Low level - More detailed review can take place afterwards
* Burden should be on the contributor
  * Project must setup the contributor for success though
* Some people are only interested in adding a new feature in, but not maintaining it - Should the feature be added in?
* Don't be afraid to remove code if it's obviously been broken for n-releases
* Have a deprecation policy
* Documentation: Give end users better guidance for troubleshooting - Can help reduce issues being raised
* GitHub suggested reviews - Can be useful
* Once a PR is merged add a comment saying "This will be released in $VERSION" - Read from Version file in Git Repo

