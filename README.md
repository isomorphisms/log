# log

*Captain's log, more or less.*

The old word was **weblog**, then **blog**. This is not quite a weblog: the native object here is a Git repository. Entries are plain text, history is commits, and publishing is pushing. GitHub gives the repository a web face, but the log should remain useful when cloned, grepped, diffed, copied, or read somewhere else.

GitHub accepts Git traffic over SSH, though it is not a general interactive shell account. That distinction fits the point of this project: the Web does not need to swallow every other protocol.

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
