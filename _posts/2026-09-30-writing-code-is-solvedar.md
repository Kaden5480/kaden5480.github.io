---
layout: post
title: "Writing Code Might Be "Solved", Programming Isn't"
---

There have been a number of bold claims about how "smart" AI is
or will be in the near future. One claim in particular that
[coding is virtually solved](https://www.youtube.com/watch?v=jOdjfOYnpYA).
I've taken some time to reflect on how true this statement is
and whether coding is actually solved.

The first thing to consider is what these models are doing. Are they really thinking?
Are they really problem solving? The answer is no. A common analogy is that
LLMs are extremely advanced/powerful autocompletes. In the context of programming, you
could imagine them as very powerful language servers. They can predict a large number of
tokens into the future and these tokens are weighted in a statistical way, such that
it will reproduce common patterns, albeit with variations each time. It's important to distinguish
this from "understanding", these models are only good at finding and filling in patterns,
they don't understand what they're doing, they just produce a probable output based upon their
training data.

One major flaw you could point to is how the output can change significantly
each time you provide the same input, and subtle differences in the input can also
affect the output. As Tsoding once said, you can imagine these models as
[non-deterministic compilers](https://youtu.be/-eS5-kaTSD0?t=398)
from natural language to some other output. I agree with this take, considering the inconsistency
and unpredictability of the outputs. Furthermore, natural language is ambiguous which
can result in multiple interpretations of any given string. Something else which can
cause even more issues with predictability would be the constant changing/training
of these models and their "guard rails". Even switching from one model to another leads to
drastically different results.

The training data itself is another point to consider. If a model is trained on "well-engineered"
code (which is subjective), then you would hope it produces better results because of the "good"
patterns it's trained on. Perhaps this is true. On the other hand, if it's trained on a large quantity
of sub-par code (maybe with bugs, vulnerabilities, poor optimisation, etc.) then you would imagine
its outputs would also be more likely to carry those same problems.

As for the LLMs provided by the big companies right now, you may have the idea that they have been
trained on so many problems and so much data, that they must be good.
[Even the benchmarks](https://llm-stats.com/benchmarks) suggest it.

Despite this, I'm not convinced. Sure, these models can
regurgitate code which seems to make sense. They know how to produce solutions to problems which
have already been solved, since it's in their training data. And when it isn't, they can still
produce an output which seems probable.

But firstly, there is a distinction to make between the idea of something being
"probable" and being "correct". Languages have rules which must be followed. These rules
determine what tokens can appear after one another. Programming languages are extremely strict.
They are almost always designed in such a way that
there is only one interpretation of the code which is written. A "valid" or "probable" program
is simply one which adheres to rules laid out by a given language's grammar. For example, here's a
valid C program:

```c
#include <stdio.h>

int add(int x, int y) {
    return x / y;
}

int main(void) {
    printf("%d\n", add(2, 3));
}
```

Something you may have noticed is that the `add` function actually divides. In the context
of the program being "valid" or "probable", this isn't an issue, but if we have a specification
or expectation that the `add` function should add its inputs, then this program is not "correct".
This should hopefully give you a rough idea about the difference between "valid"/"probable" and "correct".

Yes, you can provide specifications to these LLMs so they are more likely to produce an output which
you expect, but they are still rooted in probabilities. The lack of thought and understanding means
they can and will make mistakes, they don't have the "gut feelings" that people have. We can get
feelings that something isn't quite right and act on them, an LLM won't. Sometimes these models may even
produce outputs which aren't valid programs either.

One of the other things I considered was scaling and long term
development. Whenever you are actively programming instead of offloading your brain to a slot
machine, you are constantly making decisions. These decisions are based upon all of your past
experiences and what you believe makes the most sense for the project you're trying to create.
You have clear goals in mind, you can visualise how the project breaks down into its individual
problems, you can spot and analyse patterns as you go along and choose what things should be
optimised and how they should be optimised. Whether that be for storage, time of writing the code,
speed, memory usage, or thinking in the long term about how this code can fit into the large picture
to possibly save you time and mental effort later on. As you're writing the code, you can encounter
unexpected problems or reach a breakthrough where you suddenly see a new way of thinking about the problems.
In the end, all of this changes the final result. You end up with something which is catered
based upon all of that experience and those decisions.
This is the hard part of programming, and what I'd consider the real skill of writing software to be.

The overall point I'm trying to make is that the act of writing code is kind of "solved", even
with LSPs you could say it's sort of "solved" to an extent, since these servers can suggest
reasonable next tokens. But the thing is that writing code was always the easier part.
The hard part is figuring out what to write in the first place. That takes a lot of practice
and experience. You constantly improve over time with the experience you gain and the more
projects you tackle, and the route you take will be unique to you. All of this will
shape how you engineer your projects, how you break down those problems into their core
components, how you prioritise your time and effort. I don't think an LLM can or ever will
be able to achieve these same skills. You can't just reuse the same ideas everywhere, every
project has its own unique requirements which needs a level of creativity and critical thinking.

So, I'd say for now we have not solved programming and we are far from it. Real, talented
software developers are still going to be a requirement because we need someone to make
those hard decisions. Best case scenario, we still let those developers write the code,
since that will expose problems that may not have been considered.
