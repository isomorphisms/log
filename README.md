# log

*Captain's log, more or less.*

The era of vibe coding is upon us, and that means good and bad. Among the beneficiaries is the concept of free software. I don't know how the culture of free software is going to change, but for the moment people have given of themselves for many, many years. They put their code out there, I think often sincerely hoping that somebody else will do something with it, and now I and other people are supercharging that.

If you ever said software wants to be free, then you are being proven absolutely correct, because the cost of creating this stuff and forking is very low: several orders of magnitude lower than most of us are used to it being.

After a couple months of vibe coding, I'm not sure that I could even type. I mean, I still remember the insert and escape commands in Vim, but the knowledge that seemed to exist more in my fingers than in my brain is quickly being converted into ideas for how I can keep my agents on track.

The old word was **weblog**, then **blog**. This is not quite a weblog: the native object here is a Git repository. Entries are plain text, history is commits, and publishing is pushing. GitHub gives the repository a web face, but the log should remain useful when cloned, grepped, diffed, copied, or read somewhere else.

GitHub accepts Git traffic over SSH, though it is not a general interactive shell account. That distinction fits the point of this project: the Web does not need to swallow every other protocol.

## The long project

What are the overall goals of what I'm trying to create here? These are things that—just to put a number on it, without any precision—will take 6 months to a year at minimum.

Number 10 is an app factory. Software is not completely free. If software is not completely free in the next year, then it will be completely free within the next couple years. Imagine that improvements are made to these coding tools so that anyone with an app idea can get it built by paying a sufficient amount of money to OpenAI or Anthropic. For someone like me, it's time to act a little differently.

Number one, to rebuild software foundations the way I always wish they had been. Now even with all the new tools, this process may take a couple years. But of course already within 2 months I have drafts in some degree of working order at the assembly level, at the sensor hardware level, at the PIN level, at the operating system level, and at the language level. There's some question of whether my appetite has grown just as big as the tool sizes have grown and whether that might not even be a good thing.

So for me and for people in my position, the actual apps are not quite an afterthought but at least a result of better foundational work. Of course this is the same in construction. The actual process of putting up the wood for a house, fascinating and watchable and tool/work entrancing and mathematically/engineering enchanting though it may be, it's absolutely senseless to begin these things without checking level and square and indeed checking whether the gravel or bedrock or clay or whatever underneath the slab is going to shift under the weight of tens or hundreds of tons over decades.

I've never seen an actual house go up slow nor have I ever seen a construction site look the same month after month as I drive by and see that apparently some sort of foundational work or digging is happening.

So I'm patient in this sense although of course I did quickly make up a couple things with the new tool set—that's what showed me that these things are so good at translating existing software, that I now use that ease of translation as a fundamental process in how I build. Find—look, if it's that good at translation, if it's good at bootstrapping, then I can put all those things to work and design my vibe coding process around that. First step is to download a lot of books or instructions, architectures, or documentation with ideas that I want to double check and make sure that that's locally available within the repository to guide the machine and also perhaps a bit to remind myself what the initial goal was. Write up a lot of issues, but as Andres noticed back in the day issues used to outpace pull requests. Now the meaning of an issue has become so completely different it's more like a note that I didn't feel like spending compute on or perhaps that I didn't feel like spending my own thoughts on.

Of course kids' science museum apps. The goal here is that an app is so small that it's really just a toy if you play with it one time. So for example if a human being were giving a lesson they might cover two or three topics in a 1 hour lecture, and if they wanted to say go home and play with this there might be even a dozen toys that are worth playing with. And of course this has always been true: the toys of mathematics are worth picking up and playing with many times, different levels of passivity and activity.

For example let's say I animate a couple different theorems of Euclid. The notable difference with Byrne's Euclid is that I'm not expecting you to pick up a whole book. I'm expecting that you download one APK and play one game which may not even correspond to one theorem; it may just be a game that's related to one or more theorems. This differs from GeoGebra¹ in that GeoGebra has a lot of different lessons. You have to sort of guide yourself; you have to know what games to play. The GeoGebra engine is perfect as far as I can tell, but the bite size is a little too large and only people like myself are going to occasionally pull up GeoGebra and have a good time with it.

¹ If I remember correctly, GeoGebra was touted by Steve Jobs as the bright new educational future in the 90s (and just look how smart we all didn't get).

§ And I'm certainly not saying that for all the peasants of the earth to learn some Euclid will sufficiently lift their spirits to make up for the differences in income. If anything the evidence is very strongly against that, and due to Wikipedia and Internet Archive and other similar sources I know this much more confidently than I would have 50 years ago.

So speaking of geometry, how about all those great Geometry Center videos from the 80s and 90s? For me and I think for most people who read it, *Geometry and Topology of Three-Manifolds* by Bill Thurston is a life-changing book. Of course like any book recommendation you sort of have to find it yourself and it has to be the right time for you. I'm not going to say go read this or go pick it up, although I can obviously make an Indra's Pearls explorer and give you a very quick hyperbolic geometry game.

So a dozen years ago of course I would fantasize to some programmer friends how we should certainly make some video games where you can walk around various non-Euclidean spaces, I guess all of which are locally Euclidean. Now I did this in my mind of course and it may not be the same on an APK, but this is the vibe coding era. What the heck, let's just go for it. And it's this kind of cowboy app which remotivates me to have some deeper considerations and to aim a little bigger.

Yes the economics are probably such that I can just make an app for free for the hardware store I shop at and see if that helps them compete against Home Depot. I don't think that that can possibly shift the overall cost economics. The hardware store I shop at is supplied by Do it Best just like the comic store I shop at is supplied by Diamond, so there's still some scale in terms of a wholesaler or distributor who supplies little businesses with what they need to feed their customers or at least have an expensive Milwaukee tool on hand when I come in to buy a left-handed drill bit. And everybody is competing against the economics of warehouse direct to customer, and our political system still doesn't see fit to treat the people who do this very much appreciated work with full dignity.

I wouldn't call my attitude towards the possibility of software creating positive economic change pessimistic. I just want to acknowledge that our place is a very small one, especially since so many opinions with money behind them seem to treat software itself as capable of changing the world for the better. Sure we have a couple successful examples like ordering groceries or products directly from the warehouse and communicating amongst the network of taxi drivers so the taxi drivers don't have to stand idle. Let's just please wince a bit when someone tries to blow smoke up our asses. Of course I'm going to do this work or try to, and of course I hope it's helpful, but anyone who has even a slightly engineering hard head has to look at reality and not take yourself too seriously.

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
