# Documentation session

## Technologies

- Best library is best-documented one
- Sphinx and RTD are perfect for Python
- Varnish and Linux kernel are using Sphinx now, too. Improvement over manpages
- A lot of Markdown bc GitHub is ubiquitous. But Markdown has limitations, easy to get stale
- ASCIIdoc - they tried to switch, but went back to Markdown bc it was easier to use (when do you prioritize usability?)
- Something less crufty than restructured text would be nice, but restructured text + Markdown are still pretty good
- Can't just auto-generate docs perfectly. Need lots of examples and narrative
- Need different technologies for different types of documentation
- GitHub Wikis
  - Docs need to live next to the code, in the repo
  - Use the same edit tools for code as for documentation
  - Too much abuse in the wikis, not enough controls for it
  - Ex. D3, lots of issues, ppl get banned and then create new accounts
  - Not structured enough, doesn't feel connected to the code
  - There are no guardrails for approving contributions vs. not
  - No versioning for wikis
  - Org-level notifications for wikis don't show in your notification feed, so manually watching stuff is also a pain
  - Balance between low friction vs. not - making it easy for people to edit, vs. putting up guardrails
  - Culturally, wikis are sort of falling out of favor anyway. These days, you can use web UI to edit READMEs etc which is just as easy

## Content

- How much base material should you teach as part of the implementation?
- Should I tell you when to use it, or suggest something else?
- You're already on this page, I could give you a statistics lesson
- Illustrations help reduce documentation fatigue - pay friends looking to make a buck to do a couple illustrations ($20-30 per picture)
- "Reward for myself" after having written docs - it's fun to get custom illustrations for my libraries
- They're not logos: illustrations, not graphic design
- Are you a maximalist with docs, or do you target a specific set of users?

## Project scope

- Documentation for a library is different from that for an application
- Do you need a user guide, API guide, etc

## Contributions

- Balancing between being robust vs. easy to use. If there's too much friction, nobody will contribute
- How literal do you get about stuff? Guiding the user to the right behavior, when do you disclose what you can/can't do, vs. trying to gently dissuade them
- Do you want contributions on documentation, or do you want to be the person who writes docs for others' contributions?
- Writing docs for everyone else is good bc it forces you to be able to articulate that contribution's value and how to use it
- If it came pre-packaged it'd be harder to articulate the value
- Is documentation actually a great first contribution? Systems can be complex, sometimes more of a headache than contributing code
- CI in docs is less of a thing (Inch does it for docs)
- Not always a real place for people to jump in and submit documentation
- Large monorepo that's been around for a decade: when people leave, they have to leave a README on their section that they managed, so future ppl know how to use it

## Documentation about documentation

- On Writing Well - book about writing documentation
- Do you use prose linters, CI, etc?
- Do you use style guides?
- They don't always help lead to better documentation, can interfere with natural flow
- Style guides/rules can be more helpful almost as a neutral policy to guard against bad writers, vs. over-engineering perfect rules for ppl who already write well

## Keeping things up-to-date

- What tooling do you use?
- Code examples in particular go out of date quickly, deprecated or don't work at all
- Doc tests can help
- JS doc test - runs examples as tests
- Testing your own documentation is hugely helpful
- Have a directory with examples that you add CI to
- Then have a custom role that pulls those files and dumps them into place
- It's surprising that doc tests haven't been taken beyond those one-liners
- How do you enforce things like in-line text or links that get out-of-date?
- Use a canonical, ground truth Markdown file with constants in it. Human edited, but have one person who's focused on keeping that one file up to date
- Wikipedia facts go out of date all the time
  - They're going to use wikidata to manage it, esp across languages
  - Ex. what's the population of Belize? If one Belizean person can update the article that changes that for everyone, it would be easier than ex. the Farsi Wikipedia knowing to update it when the US Wikipedia changes
- Most scientific papers are not reproducible. No versioning, etc. They're in even worse shape than your average software documentation
- How do you use contributions to keep docs up-to-date?
  - Get Stack Overflow people to community edit and keep things up to date
  - If not kept up-to-date, those old answers are causing ppl to write software like it's 2008 (bc that's when those answers were written)
  - Host dedicated events to clean things up and get them up-to-date
  - Some projects have dedicated documentation contributor groups who are self-organized around this stuff and will take care of it
- Casual contributions: but the people who need it most are also the least qualified ppl to fix it (they're reading it bc they don't know the answer!)
  - Copy editing can be a great first contribution though
  - You need a narrative of what the docs are to make it easy for ppl to make those fixes/contributions
  - FAQs are an easy way to contribute - if it's been asked even once, make it a FAQ
- Other people push all questions to Stack Overflow as a way to manage projects at high scale
- SQLAlchemy has a great process for managing documentation

## Cultural Norms

- When you look at newer communities like Rust, they're starting a new community and looking at documentation with a fresh eye
- But is it possible to change conventions for a community that's already formed, that DOESN'T have a tradition around documentation?
- It's true for established communities too, though - you're often teaching to a first-timer within an established community
