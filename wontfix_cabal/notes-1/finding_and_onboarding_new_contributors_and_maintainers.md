## Conversation
## Conversation

* Gregor - hoodie
* Ferass - webtorrent project. have a lot of contributors that send one-off PRs and even with contributor power don't feel enough ownership to contribute further
* Daniel - linux kernel project. attempting to fix that community a bit.
* Paul - maintains too many projects RE electron.
* Kat - maintains the npm cli.
* Laura - kernel maintainer. interested in bringing new people into the project. how to find them is near and dear to my heart.
* Patrick - does things open source and infrastructure wise RE tor and noisebridge hackerspace. looking to find mentorship patterns that work.
* Jaana - open source go programming language work @ google. have a dominant google presence on the project. dealing with different code review systems and tooling in the project. finding it difficult to find consensus on issues due to the language level stability required. trying to ease the entry for new contributors.
* Noah - works @ EFF. Works on certbot, the CLI utility for the Lets Encrypt CA. Loads of people use it and have problems with it, but few contribute. We're somewhat irresponsible when dealing with this, and we want to figure out how to do a better job in making people feel empowered.
* Michael - works on Go with Jaana. Feels like I've benefited greatly from contributing to Go, but at the same time feels intimidated in making contributions, and suspects that there are many others who would benefit but are intimidated and don't do so. Wants to remove barriers
* Mindy - MirageOS, a hard problem set which makes it difficult to keep people interested when they've invested a bunch of time already. Wanting to be respectful of people's time
* Daniel - how long does it take for people to walk away from PRs @ mirageOS?
* Mindy - days to maybe a week. doesn't take too long
* Jaana - do you you have any metrics or dashboards to monitor your response times?
* Mindy - hard to do because of large repository fragmentation. hard to find tooling that fits this purpose given the distributed repos. We have people to what their own focus interests, but don't have 100% coverage. I put the "Diffusion of responsibility" on the board
* Daniel - There's an issue if you split things too much for one person then when that one person's time isn't available it proves problematic. Bus factor issues.
* Gregor - I think we should first focus on contributors then we can take on the maintainer issues later. Let's define a contributor: what do you all mean by this term? What is a contribution?
* Jaana - Do we consider a contributor to the community a contributor? Or just a code committer?
* Gregor - how is this defined in the Golang project?
* Jaana - we don't have an official term, but we say that anyone that filed an issue, opened a PR would be considered a contributor. We don't have hard rules or terminology for this. There's a bunch of people who want to make this process more structured, so that they might have a greater understanding of their scope and understand progression etc... There's currently not clear different levels of contributors.
* Michael - we go to length to not define structures for people. For instance getting committer rights, it's a "when we feel you're good enough and understanding it well enough" you get the bits. But what does that mean? What is the responsibility placed on you? What does it mean that you're responsible enough? When there's no structure then it's all about your relationships with the people. I found this easier because of the fact that it's a company project, and I can schedule meetings etc... but outsiders cannot.
* Laura - I'm curious to hear how people deal with growing contributors from one project to being more involved. Is it mostly people that are excited enough to do it on their own? In the kernel people come in with style fixes but it's hard to define next steps.
* Patrick - Getting information on tickets of high value is hard - I find it can only be done with relationships with mentors.
* Kat - the issues of being employed to do this creates a natural hierarchy with the implied weight of the corporation behind the paid contributors. "Internal" decisions carry a bunch of weight that's not available to external contributors
* Daniel - "internal" decisions are an anti-pattern, the external contributors need to be suitably bought into the decision also. The kernel has a large mix which causes problems for newer hobbyists or students etc...
* Kat - even beyond "hazing" (getting used to doing things internally) is a hard communication problem.
* Gregor - it does appear that the fact that paid contributors experience different issues.
* Kat - how many of us are maintainers for projects with a single main stakeholder.
* Feross - The dynamic that you're talking about with companies happens also with webtorrent, as people generally defer to those associated with the employer.
* Gregor - what appears to be the case is that committer == "code contributors", but code isn't the only contribution. At hoodie we've stopped using coder/non-coder terms to signal this. This allows people to find contributors that mentor people, that work on documentation, issues etc...
* Daniel - Giving people the tools is not enough, you need to gives them encouragement, trust and help. How do you find people that can do it for you.
* Gregor - hypothesis. take npm, the most amazing contribution for the project would be if you'd go through our issues and help triage things.
* Kat - we used to send people socks for docs.
* Gregor - we should make it demonstrably valuable for people.
* Janna - we have a policy for "gardening", triaging. but there's still permissions issues (who can create milestones etc..) and so there's a lack of structure here that hinders this.
* Laura - the fedora project has a system of "badges" for various contributions. It covers things like wiki edits, answering FAQ, stack overflow, and other non-coding exercises. Fully formed contributors don't just come out of nowhere and a lot of emotional labour is involved.
* Michael - this is potentially a skewed perspective on my part, but as a contributor I want to contribute code and triaging issues is hard work. It does have to be done and I'll do it when I'm being paid happily, but when I'm an outside contributor I don't want to triage issues.
* Janna - maybe, but there are people that really enjoy this.
* Gregor - I've heard from two people, designer and contributor, that they'd always thought of open source as a private coders club.
* Kat - we have limited time, loads of stuff to talk about. Are most open source contributors solving a work need? Why do people contribute? If we can find one example and optimize for it. I'm not so interested in random contributions from community hobbyists mostly due to ill feelings of exploitation and I'm wary of asking people for energy without payments. I'm interested in helping dayjob people become more effective. I want to make people who aren't being exploited more effective.
* Ferass - I guess I don't always see it as exploitation.
* Noah - I also feel somewhat differently, a bunch of people want to contribute out of like of our project and org. Building people up from weekend hobbyists to maintainers is important because opportunities do come up for them to be paid full time (grants, GSOC etc..) and we feel like it's important to have potential candidates for this.
* Kat - I don't think it's good for people to do this for exposure.
* Gregor - there's some amount of people who contribute out of a desire to work with people
* Manish - most of the open source project contributors that I see are students. their idea is that instead of writing a toy application, that they can make better use of their time, contributing and communicating with people and ultimately benefiting in kind from the interaction.
* Gregor - it's a gray zone.
* Kat - It's about who I'm optimizing for, and I don't want to close the door to hobbyists. But I want to make sure that they're doing it for themselves. I want to advocate your contributor base such that people in corporate environments can contribute without a lot of meta-work in onboarding. 

## Summary
 * understanding the dynamics between unpaid and paid contributors. Don't expect free labour in things that you don't do yourself (issues)
 * being aware of the "internal" decision dynamics in mixed paid and unpaid contributors.

 * defining contributions outside of code, using clear terminology to encourage people
  * undoing the "open source is just coders" myth
  * valuing mentorship and positive reinforcement to help people become repeat contributors.

 * being respectful of contributors time, both in onboarding and responding to their PRs and other input.
  * lowering barriers of tooling that prevent people from contributing.
 * having a good list of low hanging fruit that potentially interested people can use as their first contribution.
 * communicating and empowering people that the should be able to contribute, that once they have the requisite permissions that they can make changes.
 * having good processes for people officially becoming "contributors" and maintainers.
 * creating or seeking opportunities for people to become paid contributors through grants etc... having a list of people that you think can step up.
