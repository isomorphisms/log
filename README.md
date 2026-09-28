# log

*Captain's log, more or less.*

The era of vibe coding is upon us, and that means good and bad. Among the beneficiaries is the concept of free software. I don't know how the culture of free software is going to change, but for the moment people have given of themselves for many, many years. They put their code out there, I think often sincerely hoping that somebody else will do something with it, and now I and other people are supercharging that.

If you ever said software wants to be free, then you are being proven absolutely correct, because the cost of creating this stuff and forking is very low: several orders of magnitude lower than most of us are used to it being.

After a couple months of vibe coding, I'm not sure that I could even type. I mean, I still remember the insert and escape commands in Vim, but the knowledge that seemed to exist more in my fingers than in my brain is quickly being converted into ideas for how I can keep my agents on track.

The old word was **weblog**, then **blog**. This is not quite a weblog: the native object here is a Git repository. Entries are plain text, history is commits, and publishing is pushing. GitHub gives the repository a web face, but the log should remain useful when cloned, grepped, diffed, copied, or read somewhere else.

GitHub accepts Git traffic over SSH, though it is not a general interactive shell account. That distinction fits the point of this project: the Web does not need to swallow every other protocol.

## The long project

The things I am trying to build now are not weekend projects. Just to put a number on it, without any precision, I expect the larger goals to take six months to a year at minimum. Some may take a couple of years.

Software is not completely free yet. If it is not completely free in the next year, I expect it to get much closer over the next couple of years. Improvements in coding tools point toward a world in which anyone with an app idea can get it built by spending enough money on machine work.

For someone in my position, that changes what is worth doing.

The first goal is to rebuild software foundations the way I always wished they had been. Even with the new tools, that process may take years. But after only a couple of months I already have drafts, in some degree of working order, at the assembly level, sensor-hardware level, PIN level, operating-system level, and language level.

My appetite may be growing as fast as the tools do. That might even be a good thing.

The actual apps are not quite an afterthought. They are downstream of the foundational work, and they test whether the foundations are any good. Goal 10 is an **app factory**: a system for producing applications quickly, correctly, inspectably, and from reusable pieces. If ordinary application code becomes cheap, the valuable work shifts toward deciding what the layers mean, how they fit together, how they fail, and how much of the stack remains understandable and replaceable.

Construction gives me the model. Putting up the wood for a house can be fascinating, watchable, tool-entrancing, and mathematically and engineering-wise enchanting. Starting with the wood still makes no sense before checking level and square and asking whether the gravel, bedrock, clay, or whatever sits underneath the slab will shift under tens or hundreds of tons over decades.

I have never seen an actual house go up slowly, but I have often watched construction sites look almost unchanged month after month while some kind of digging or foundational work continued. Software foundations can look like that too.

So I am patient in that sense. I did quickly make a few things with the new tool set. Those experiments showed me how good these systems already are at translating existing software. That ease of translation now shapes the process itself.

If translation is cheap and bootstrapping works, use both deliberately. Find an existing implementation, paper, manual, architecture description, book, or body of documentation that contains ideas worth preserving. Download the important source material into or alongside the repository when licensing permits, record its provenance, and make the relevant knowledge locally available to guide the machine and remind me what the original goal was. Translate working systems into the vocabulary and architecture I actually want instead of repeatedly starting from memory.

That changes the role of an issue too. Issues used to outpace pull requests. Now an issue often means something closer to: this thought was worth recording, but I did not yet want to spend the compute or my own thought on turning it into working code. A pull request can follow surprisingly soon once the question becomes concrete.

The point is not to generate the maximum number of apps. The point is to use cheap translation, bootstrapping, testing, and machine labor to make another pass at the foundations, then let applications fall out of foundations good enough to deserve them.

## Motivation

I want a durable record close to the work itself.

That means:

- writing things down while they are still concrete;
- keeping experiments, mistakes, changes of mind, and dead ends rather than presenting only a cleaned-up final story;
- being able to point at a commit, file, issue, or other artifact instead of vaguely remembering what happened;
- keeping the writing portable and easy to back up;
- avoiding a content-management system when ordinary files are enough.

This is closer to a lab notebook, ship's log, or developer notebook than to a publication schedule.

## Goals

The repository should stay simple enough that:

1. a clone is a useful copy;
2. entries are readable as ordinary text;
3. Git history provides chronology and provenance;
4. links can connect an entry to the code, issue, paper, book, conversation, or other work that prompted it;
5. the presentation can change without trapping the writing in the presentation layer.

A polished essay can grow out of an entry later. The entry does not have to pretend it was polished from the beginning.

## Tools

The basic stack is intentionally unremarkable:

- **Git** for history, copying, branching, and synchronization;
- **Markdown** for text;
- **GitHub** as one public view and remote;
- **SSH and HTTPS** as transport where appropriate;
- ordinary editors, shell tools, search, and scripts for everything else.

Other views can be added later: an index, generated HTML, feeds, topic maps, or whatever proves useful. None of them needs to become the canonical form.

## Keep the network messy

One of the best ideas I picked up from an early programming boss was that the Web was more interesting when it remained part of a messy network of different tools and protocols instead of becoming the interface to everything.

I still like that idea.

A Git repository does not have to imitate a conventional website just because GitHub can render it as one. Files can remain files. Git can remain Git. SSH can remain SSH. Links can cross between systems. Different tools can do different jobs.

The mess is not necessarily a defect. Sometimes it is modularity.

## Appreciation

Almost none of the machinery here is mine. This repository rests on decades of work by people who built Unix and its descendants, the Internet protocols, SSH, the Web, Git, Markdown, free and open-source tools, hosting systems, editors, shells, and the innumerable libraries and utilities underneath them.

More personally, it also owes something to people I learned from who had strong ideas about how software and networks should work. I will try to name and link specific influences when I can rather than quietly absorbing their work into my own story.

The point of keeping a log is partly to preserve those connections.

I am keeping the longer thank-you note in [GRATITUDE.md](GRATITUDE.md).
