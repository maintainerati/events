# Metrics

* what do you work on
* how to decide what do you work on right now

* measuring everything
* bryan liles
* 13k developers, 1k dev teams. metrics important
* dashboards w/ commits, turn-around-time, resolution itme. Used for OS too.

* rust team/grimoire lab has a neat tool for this.



## ranking issues

mapbox/top-issues : number of comments, age, number of reactions. Naive combination of
these metrics correlates well with what people are saying through other
channels.

how to understand the lay of the land with > 70 repos. Who's doing the work,
who should be a maintainer. What's a good contributor, and when should we give
them commit. 

Custom dashboard for pulling issues across repos (carol willing). Figure otu
what is on fire on any given day.

Docker gets a notification if an old issue suddenly gets lots of comments. 

go proactively closes/locks issues so information doesn't get lost if they
become an issue again. github/PRBot. lock (or freeze) issues on go.

andre of libraries.io has project "org pulse" which will give basic metrics
over timeframe. generates markdown report.

Time to first response is thoerized to be correlated with engagement.

github archive/google bigquery tool. ad-hoc and costs money.


## tracking the people and not the issues.

who's doing a good job. how can we reach out to them, be engaged with them.

- prioritize code reveiws from known-good people -- brad. slow response time
  = slow reviews.

- github "curator" role gets requested often. Can modify issues but not commit
  to code. could be done through bot, as with cap1.


opensource@digitalocean. email them and they will give you credit for working
on opensource projects.

## code metrics.

debian popularity conntest.

rust does tracking.

chef habitat does that. Opt-in happens on first run

Homebrew does this.


## map owners to modules.

juipiter had bot to enforce. Drupal does, but they built a number of tools and
are not on github

google have owners files. for access controls. 

facebook has a tool that looks at commit history and tries to guess an
appropriate reviewer. Mention-bot.

chef has sentinels that does that. 

todo-group collection has an "awesome list" of OSS mgmt tools.
github.com/todogroup/awesome-oss-mgmt


## metrics.

intuition vs numbers. 

community will change depending on what's built into it.

development community can be an echo chamber. Need to see past it.

"you are what you measure". Measuring more means perhaps you develop to
metrics, and might miss the bigger picture.


## sentiment analysis.
foss-heartbeat by mozilla does this.

## github opensource guides has metrics page.

"what do I do today" - tldr

personal list separate from issue list to manage priorities.

morning - work on community. afternoon - things you want to do. The downside is
PR latency. 
