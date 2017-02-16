# Saying No

Two relevant articles:

- [The Art of Closing](https://blog.jessfraz.com/post/the-art-of-closing/) by Jess Frazelle
- [Kindly Closing Pull Requests](https://github.com/blog/2124-kindly-closing-pull-requests) by Mike McQuaid



 feature requests:

 - low quality contribution... can help them land them, or can close it

- sunk cost
  - it can be hard to say no when people have invested a lot of time/energy
  - consider what you can put into place so people know not to put in the effort
  - it would be nice if we could have a document people could read when they click fork (before they go write the code)
  - feels important to say "yes, and"... but that is a huge time commitment
- don't let things linger
- it's easier to take rejection when it's clear that it's not personal
  - have clear policies that you can point to
  - use bots and automation
    - you know the bot is not mad at you
    - can help set expectations (linting, CI, issue templates)
- explain _why_ you're closing something
  - when people understand they're less likely to get aggressive and argumentative
  - what can go really wrong is when people are not feeling heard.
  - err on the side of verbosity
  - use well-crafted canned replies
  - categories of rejection
    - we're not going to work on it, but will accept a PR (issue)
    - out of scope, will not accept it even if it's a PR (issue, PR)
    - low quality, can close or help land it (PR)
  - "I'm closing this, you are free to convince me that I'm wrong"
- Kind is not the same as nice.
  - _nice_ comes from a place of fear. It bends over backwards to please. It's a doormat.
  - _kind_ comes from a place of strength, from doing the right thing. It has boundaries.
- incomprehensible or incomplete issues
  - wall of text
  - "I literally have no idea what you're talking about"
  - includes irrelevant detail (e.g. time of day), but missing crucial information (issue templates help here)
  - do you auto-close or help them get the issue into a "solvable" place?
  - Atom is looking into using [PRobot](https://github.com/bkeepers/PRobot) to auto-close issues that haven't filled out the issue template
- for support requests: close the issue, tell them where to go post it (and canned reply)
- sometimes the code is fine, the patch is fine, they wrote tests, etc, but... it's clear the reason they added the patch is that they're using the project wrong.

- "logical fallacies are a great excuse for closing issues"
- "I feel super powerless to argue against the hacker news type arguments"

For new contributors, even when something can't be merged, if they have the excitement, suport them and use it as an opportunity to redirect them to other parts of the project where they _can_ contribute.
