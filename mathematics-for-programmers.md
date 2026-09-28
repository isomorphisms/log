# Mathematics for programmers

> **Draft status:** vibe-coded. These are working notes assembled from conversation, not the author's adopted wording.

First, we have to give it to people I disagreed with: just throwing more money at certain problems has worked.

Okay, perhaps it's a lot of money. Perhaps the oceans are being diluted, changing the salinity and perhaps even changing some fundamental flows or other basic characteristics of the natural environment. But throwing money at these problems did work.

That said, it's still worth reflecting, as programmers, on how mathematics really works. Not just in terms of respect, but in terms of opening our minds and correcting ourselves—in other words, not just for humility and not just for empathy, but for a truer notion of self-improvement.

The first thing to say is that computation is computation, and maps—i.e. functions—do not depend on any particular form of computation.

A prime isn't prime because of some algorithm. Certainly not because of something I may enjoy, or you may enjoy, such as figuring out how we actually fit numbers which don't fit into a register for purposes of a Euclidean sieve.

Programmers really do have our own problems of process and mechanism and interface, and those problems deserve their own hearing. But none of that should ever be confused with the mathematical objects themselves.

We should really stop naming things "vector" and "function" when they aren't vectors and functions.

A vector is not a list, and I won't tolerate it.

Don't use a fancier word that you're not sure you understand. You're going to end up looking like a fool, and regret is a bitch. Don't ask me how I know.

## Probability: turn the kaleidoscope

Probability distributions give another useful example. Nobody has discovered a master theory under which, if we simply program every probability distribution from a textbook into a machine, insight will magically drop out.

Think instead about the binomial, Poisson, and Gaussian distributions. One way of getting from the binomial to the Poisson is to let the number of trials go to infinity and the probability of an individual event go to zero while keeping the expected number of successes, (np = \lambda), fixed. Under another limiting regime, after appropriate centering and scaling, the binomial approaches a Gaussian.

That is a better picture of mathematics: a kaleidoscope.

Turn the thing slightly and another structure appears. Change what you hold fixed. Change what tends to infinity. Normalize differently. Look locally instead of globally. Replace one representation with another. Something which looked like one object becomes visibly related to something which looked completely different.

None of these viewpoints has to occur on a computer. A computer is one of many tools we can use to understand mathematics.

Even the observation about these probability distributions should not be promoted into some final understanding of probability. Somebody noticed: hey, you can look at all these things this way. Great. Now turn the kaleidoscope again.

Mathematics does not terminate in a theory of everything. At least I don't think it ever will. Part of its value is precisely that understanding something creates more ways of looking at it.

A programmer's encounter with mathematics may have happened mostly at a university, and university mathematics can leave behind a very different memory from the formal material itself.

I remember reading Stephen Hawking and wondering whether I could actually understand time—or even understand what it means that somebody can ask mathematical questions about space and time. I had a great time simply being a conscious human being having those thoughts.

A lot of calculus students have had some version of this experience. You make your own brain zoom in and zoom in again. You encounter infinity, approximation, limits, infinitesimals, curvature. Whatever eventually appears on the exam is almost beside the point. For a moment you get the phenomenological experience of forcing your own thought somewhere it has never quite gone before.

Many college freshmen over the last century got to have that experience.

I think the world's first trillionaire may even have made it that far, and no further.

## Matrices come after the maps

Matrices are another good example.

A matrix is not fundamentally a rectangular thing in computer memory, and matrix multiplication is not fundamentally a computation somebody happened to specify.

The computation comes afterward.

Start with linear substitutions of variables. Suppose

[
x' = ax + by, \qquad y' = cx + dy.
]

Then make another linear substitution:

[
x'' = ex' + fy', \qquad y'' = gx' + hy'.
]

Substitute the first pair into the second. Collect terms. The rule we call matrix multiplication falls out because we asked what represents the composition of these transformations.

That order matters.

First comes the mathematical structure: linear maps can be composed, and after choosing bases we can represent those maps by matrices. Then comes the question of how to calculate their composition in that representation.

Once we actually put the thing on a computer, a whole new collection of perfectly legitimate questions appears.

What representation should we use? What should update when something changes? Should we recompute something immediately or wait until somebody needs it? Should we store an intermediate result? In what precision? In what order should operations happen? Can two things happen at once? Which representation makes this machine fast? Which representation makes the program comprehensible?

Those are real questions. I like those questions. They are computer-people questions.

But they are not intrinsic parts of the mathematical thought. A linear map does not have an update schedule. Matrix composition does not have computation time. The mathematics does not care that I haven't figured out whether to keep some intermediate value around or calculate it again.

Sometimes we discover several ways to compute the same mathematical thing and don't know which one to use. That's an us problem.

Especially if we're getting paid to fool around with computers while other people do considerably less pleasant things for considerably less compensation, we ought to retain enough perspective to say: look, I didn't actually try hard enough to get this right.

Knowing some mathematical vocabulary does not rescue us from that obligation.

Don't act like you're smart because you've heard of a vector.

Don't act like you're smart because you took Calculus 101.

A vector isn't a list. A function isn't a procedure. A matrix isn't an array. Mathematics isn't whatever representation happened to fit inside the machine we were using that afternoon.

The computer is one more thing with which to look at the mathematics.

It is not the thing that makes the mathematics true.
