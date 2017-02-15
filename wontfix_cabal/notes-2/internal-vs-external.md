## Summary

Our discussion was on internal vs community/open prioritization.

The topics we discussed were partly sharing examples/anecdotes about how
various companies dealt with this and problems we hit.

Examples we talked about included the problem of open source bits heavily
dependent on closed source bits, internal paying customers prioritizing things
vs community, convincing the company the community bit even matters at all.

We talked a little about google and how it has a reputation. It has many projects that are incredibly diverse.
We talked a bit about the sway paying customers can have.

We talked about what the value to the company even is for doing this.
MJG pointed out that it helps with mindshare to have community maintained and used projects (e.g. that helped CoreOS gain brand recognition).
It also helps get external developers, which hey, means code!
It makes the project more healthy overall to have more people involved.
It can be difficult to justify to PMs or managers though.
It can be seen as just a process that slows things down (though you can have escape hatches). 

Larger topics we talked about were things like project governance (sorta a
solution to the problem of closed-door decision making), About talking to
management about community, about sharing internal decisions with the community
well, about doing RFCs and other governance-things.
Governance helps set expectations.

We also talked a bit about how some projects don't need to be "community", but
how you should be explicit / clear up front about what sort of project it is.
It's better to have open source code, even if it's not intending to ever take
community contributions, than it just remaining closed source in many cases.

We talked about tooling here.. and that mailing lists are basically what we've got.
We talked a bit about nodejs's community, governance, using github issues.

We mentioned the case of the company wanting something bad for the community.
As a maintainer you have power to say no, to speak up on behalf of the community.
The community and you also potentially have power to fork, which might help sometimes.


Solutions:
Finding and pointing to good examples of governance models.
Documenting recommendations around that in the opensource guides.

The same for making it clear that a project is or isn't community-contributable.
One thing that can help here is just having a split in orgs for community vs
company vs dead etc.


## Internal vs Open Prioritization

Show of hands for working at a company and doing open source: roughly 66%

Datapoints:

Noah: EFF, so sorta. Certbot which is open, but lots of figuring out what to add. There's floods of community issues in addition to that internal.

Mike Burns: 20% time on open source, so everyone does some maintainership. Often try to do something the company will care about

Kat: SAS/Enterprise products, but the client connector bit is open source. The client is thus open source, but it's enterprise driven. Weird dynamics between the open source thing which is hard-tied to a company. Hard to get contributors. No path to dedicated maintainership.

Luis Ville: Lawyer, so causing the problems :P

mjg59: Lots of open source background, working at google now and the team isn't necessarily doing the best job at community creation/etc.

Cicilia: Clients worried about open sourcing because the prioritize from the community might overwhelm. Company say vs open say.

Lucas: Benevolent dictatorship company (mapbox), but open source. It's used by people, has paying clients though, so open / community / company dichotemy.

Euan: CoreOS / Container Linux / Kubernetes

Iliana: Amazon Linux, AWS Customers have a lot of pull. Some internal vs community stuff (for some definition of community)

Rishi: No paying customers yet, but one day!

Micheal: Google, golang, just here to listen in since the project could have these problems.

Seth: Chef, open source company, commercial projects. Sometimes have to work
with product a little to fix things that will help open source and ultimately
will help customers, but isn't obvious that it will.

Ahmed: Webdev agency, microsoft stack. Here to just learn more about OSS community

Nathan: Work at Docker, with docker machine/toolbox. Another example of the community vs internal situation.



----

Rainer: Google people are here. Google has a reputation about this. Why?

MJG: There are so many internal forces that it's difficult to take on community things. (recent starter, insights my own etc).
Publish many projects, and they have disparate levels of engagement. Projects
like Go/K8s have a real effort behind them. K8s specifically is an export to
the industry with that intent. Only possible with a community. Kinda same for Go. Not just for google use.

MJG: Something like android, where the people making demands are the phone users vs regular users ends up with diff dynamics.
Other things are just "wrote for myself, released. Throw it over the wall"

Euan: Google does have one org with a lot of things. E.g. cayley, which is 20% is under google, glog is internal-only but is under golang, lmctfy is deprecated, but still under golang.

Iliana: Split of the aws/aws-labs helps for amazon.

Rainer: Microsoft has that split including a graveyard.

Cicilia: How many people have governance policies (1 hand, k8s sorta does). A way to make decisions.

Luis: Part of the value of governance is transparency about expectations. Internal vs external. having a way to resolve that is important.
Better to have a public policy than none at all. Has to be documented.

Kat: The point of this is to find solutions? (maybe sorta!)

Kat: What is the value.. you have a company. Do you get anyhting out of loosening your grasp on the project? Tell your boss you want to be less of a dictator.
What do you offer the company? The outside maintainers.

Cicilia: Company: you get people using it in new ways, you get offshoots. Also contributions themselves.

Euan: There's the class of projects that wish to be community owned, vs not community owned. E.g. golang/k8s are intended to be community. Some projects *want* it to be community owned.
Luis: Yup, some company projects aren't really community, company just doesn't care
MJG: There's impact of having code out there for mindshare. That value is tenuous.
A lot of people aren't using CoreOS technology, still make use of small components. Gains mindshare!

Euan: Hard to quantify, hard to talk to a manager about that.
Kat: Does community contribution necessarily correlate to popularity?
MJG: It can, you can get mindshare if you make something more generally usable (plumber-stuff)

Noah: When it's a company owned project, how do you make people comfortable? Community governence! If you make it explicit, it makes people feel better about contributing.
datapoint: certbot was called lets-encrypt. Community member made it basically. One of the community members had a differing with a "internal member" who override it, causing the community member to 'ragequit'. Was bad for the contributor, bad for the tool, but also hurt the community in that people couldn't feel as comfortable conributing.

Mike: We organize a time where we work with other maintainers and help triage
low-hanging-fruit, etc, etc, and then group people together in a bootcamp to
help intro people to OSS and these projects.
Starts the convo with the users on our side :)

MJG: Design discussion / decision making should be visible. Even if the community doesn't having weigh-in.
Long ago, a project I worked on started more community, but ended up with more
conversations moving internal, which was frustrating for community
contributors. If you don't get it right to begin with, it's difficult to fix.

MikeB: Remote teams have that too.
Rainer: Same, internal discussions, we have to publish a design doc or something.

Euan: I second the 'publish discussions' 100%.

Kat: RFCs, even for product stuff, there's an internal round, and then an external round. Recently added, so not sure how well it's working yet.
Still gives us power, but lets them say something.

Nathan: The more that people have a say, even if they don't use it, the more agreeable they'll be.

MikeB: Are there well documented governance models.

Luis: Many companies/projects have them. There are foundations and such. It's harder when there's only a single company which likes having control.
Not a ton of great models for that. Employees have to push for the building blocks of transparency.
Sometimes there's a pereception of transparency slowing things down (let people weigh in on mailing list, slows things down).
Making sure to bring that expectation in line, e.g. telling people some things will be fast, or some things won't, etc is important.

Euan: Redhat/openstack have governance models, dunno how well they work
Iliana/Luis: Redhat doesn't. Fedora does.

Luis: Important to note that e.g. fedora/rhel, rhel doesn't have to be threatened by redhat's governance etc. Selling support helps for that.

nathan: Foundation/governance are things we talk about, but threatening a fork is an important way to make companies get their stuff together.
Do we threaten that hammer?

Rainer: Some things aren't forkable.

Luis: Sometimes legit to fork things, some things can't be (e.g. wikipedia which people have talked about it).
Diff projects, it has different viability.

Kat: Node vs iojs, that was an interesting example.

## Solutions

## Explicit about what type a project is

Is it internal code dump? Is it going to ignore the community? Just be explicit about that! Sometimes it's okay.

### Governance models

Add it to the github opensource guide. Find examples of good models?

MJG: We're talking about how to build a project with healthy community. Don't always have to. Some things should be open source, but don't need to be community. You just need to be open about that.
Governance models depends on that.

Lucas: There's not a good place for this is there? Where do we do it?

Euan/Iliana/etc: Governance is often on mailing lists! We don't really have a better solution sadly.

Lucas: Do I need a mailing list then?

MJG: Might still be the best we've got. E.g. k8s does vidio calls (sig meetings), but there's still a mailing list.

Rainer: video calls have helped, but not great for some things like small components.

Kat: Node does use the issue tracker for governance stuff. E.g. the promise one is a cool example. Lots of summary everywhere!

Rainer: What about people without enough context?

Kat: RFCs with revisions often help with that. Helps give context for the discussion.

Nathan: Good point. eg. at docker, we have a dedicated person for summarizing, corralling, synthesizing.
Kat: Cool to have that position.
Nathan: Helps a lot probably.

Lucas: Is it ever too burdensome?
Euan: Force internal contributors to go through it too, that's the only way to make sure it gets fixed.
Kat: Breaking changes, big things are needed. Don't need an RFC for everything for sure.

Iliana: Rust project funnels things into RFCs, but you don't need to write an RFC just to have a say.

Rishi: There's a core team, half internal/half external. 

Lucas: Is node basically all github issues? How is that working?
Kat: Everything is issues really. Ultimately. There are IRC and such, but it's basically all issues.

Rich (driveby participation :) Moderation also happens, that's uh. Yeah, that happens. Lots of room for improvement.

Rainer: example of a basically stagnated issue because it's just super hard to explain.
Nathan: Yeah, sometimes people suggest issues that seem easy, but aren't. (See also, saying no).
Helpful to have architecture docs to point people to.
What about sometimes just 'ripping the bandaid off', shutting it down right away.

Mikeb: How to say no.

Lucas: Lack of negative results in issues, as in science.
Rishi: Having a pointer to a doc helps for saying no too.

MikeB: Having a goals overarching for the project helps to point people at too.

Nathan: What about if the company wants something but the community doesn't?

Rainer: Example: Mandate from management on high about a change in focus... Not best for the users or as an external contributors.

Euan: One solution sometimes is to fork it into your own project that removes it.

Seth: Contributors do have power for what's best for the community. You can fight back
Nathan: Yup. Worked out for the best in some cases when a user did that.
