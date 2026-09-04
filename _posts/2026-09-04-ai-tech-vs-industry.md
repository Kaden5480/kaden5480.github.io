---
layout: post
title: "AI (Technology) vs AI (Industry)"
---

Before I begin, I would like to make it abundantly clear that what I am
referring to as "AI" in the title is a specific subcategory of AI, namely
Large Language Models (LLMs). AI itself has been around
[since the 1950s](https://www-formal.stanford.edu/jmc/history/dartmouth/dartmouth.html)
and has provided us with a variety of truly useful technologies. For example,
[path-finding algorithms](https://link.springer.com/chapter/10.1007/978-3-642-20662-7_20)
and deep learning, protein folding models like
[AlphaFold](https://alphafold.com/).
The former is often used to plot efficient, real-world routes from
point A to point B and the latter greatly accelerates protein structure
research, which is vital for progressing medicine and healthcare. LLMs
are yet another technology under the broad category of AI, but they are
primarily being referred using their more general name, "AI". For extra
clarity, the popular models since
[late 2022 (with the release of ChatGPT)](https://openai.com/index/chatgpt/)
have been based upon a transformer architecture, usually the [generative
pre-trained transformer architecture](https://openai.com/index/language-unsupervised/).
If you don't know what that means, don't worry. I won't be delving much into it and you
can research it in your own time if you so desire. I am purely mentioning it for the sake
of being pedantic.

Now that's out of the way, we can begin dissecting what I think is an
important distinction between a technology and the industry, marketing,
and general hype which has formed around it.

# The Industry

Since the release of ChatGPT and the resulting explosion of hype around LLMs,
the media has been absolutely infatuated by it. It feels as though everyone
is at least somewhat aware of these models and has often used, or is actively
using, them. It has been forced into many aspects of our lives, even in situations
where it is like trying to force a square peg into a round hole. We have seen
some
[highly dubious financial alchemy](https://gizmodo.com/nvidia-tries-to-defend-against-circular-dealmaking-accusations-2000803583)
all in the name of keeping the AI story alive. The
[cost of buying hardware has reached absurd heights](https://www.theregister.com/personal-tech/2026/06/01/memory-crunch-sends-pc-prices-into-double-digit-climb/5248525)
and, in some cases, people are paying
[significantly more for their electricity bills](https://fortune.com/2026/07/14/data-centers-23-billion-electricity-bills/),
are forced to live with constant
[noise pollution](https://www.usnews.com/news/national-news/articles/2026-04-28/living-in-hell-data-center-neighbors-grapple-with-noise-air-pollution),
or even
[lose their house due to power grid and data center expansion](https://www.youtube.com/watch?v=PApPd6p6lX0).
The AI businesses are
[actively scraping enormous quantities of data from the internet](https://tollbit.com/state-of-the-bots/q3-q4-2025/)
for training purposes and they have already consumed so much of said data, that they are now turning to
[scanning (and destroying) books, including rare or antique copies](https://uk.news.yahoo.com/ai-companies-buying-destroying-antique-195817074.html).
It is often recited to us that "AI will take over everything", "we'll lose all our jobs",
or that "AI is dangerous and needs to be carefully controlled", but the longer this goes on,
the more I'm believing this is part of their marketing tactics and not necessarily
something which is fully grounded in reality. Of course AI safety concerns are
something we should be considering long term, but are LLMs really going to be the
thing that brings the human race to its knees? I have my doubts.

This is the AI industry.

# The Technology

On the other hand, we have the technology itself. For my personal use cases and
with my own morals, I struggle to find a way to utilise LLMs effectively.

I have tried generating code before, even asking people I know for some time
with the latest models to see how they behave. I would say that the code
may often look more or less "fine" at a surface level, it *might* run/compile,
it *might* not have glaring issues, but when you scrape beneath that surface
level I don't believe the quality is really there. Engineering/developing a
piece of software is something which truly relies upon a deeper level of
understanding of what you're trying to do and what you're making it for.
You should be planning carefully for long term maintenance, you should
be writing sensible documentation, naming should make at least some sense,
and the code really needs clear logic for you and for others
(like future maintainers) to understand it.

Besides software, I know there are people that say how "good" LLMs are for
researching. For those people, I would suggest considering this: LLMs are
known to hallucinate, this is well-documented behaviour and is
[provably unavoidable](https://arxiv.org/html/2409.05746v1).
They have also been designed/trained in such a way that they are
[confident with their responses (and overly sycophantic)](https://www.forbes.com/sites/josipamajic/2026/08/24/ai-tells-you-what-you-want-to-hear-big-money-is-trying-to-fix-it/)
even when they are wrong. Even if you give an LLM access to a search engine,
can you truly rely on their output? To add onto this, an increasing proportion of
the top results from search engines seem to be AI generated. So, are you really
saving yourself any time by using these models for research, when you should
be double checking the responses anyway? Or should you stick to researching
the "old-fashioned" way, browsing the internet yourself, or maybe even borrowing
a book from the local library?

We also have creative works; music, videos, films, books, articles, essays, art.
I don't believe that these should ever be fully generated, I'd say the human aspect
is the most important part of it. When you lose that, these forms of media become
empty and meaningless. They lose their character and charm. Human creations have
nuance, personal experiences, viewpoints, opinions, and a real, distinct personality
behind them. When you listen to a piece of music, spend your time watching a video,
read a literary work, or immerse yourself in a piece of artwork, you focus your
attention on a story or message the creator is trying to convey, or a feeling
they're trying to invoke within you. When you remove the person, the result is
something which is flat and barren, devoid of any soul.

Onto the more positive side, I would say that I can imagine small versions of
these models running locally for handling very surface level communication
such as emails. Perhaps they may evolve into more specialised models for
translating languages. I have also seen a mention of their possible use
for spell checking, grammar checking, or more complex validation of the
general structure of your writing. These all seem like valid use cases, and
as long as a person is kept in the loop, it's probably fine. For generating
code, I think it might be acceptable to use LLMs to an extent, but retaining
that human overview is essential. To be precise, when using LLMs for a certain
task, you absolutely *should* have a person who is overseeing it and this
person *should* be knowledgeable in the field which the LLM is producing output
for, so they can catch the LLM's unavoidable mistakes and hallucinations.
If you are not knowledgeable in the field and/or are not paying attention,
gamble away, and don't be surprised when it backfires.

LLMs are a tool, not a drop-in replacement.

# Thinking Of Things Separately

The primary reason I have written this post is to try to separate the industry
from the technology. I think it's important as we can easily get too caught up in the
negative sentiment of LLMs, which drives us to berate and condemn any usage of
it anywhere. We should also keep in mind that what we have seen so far is a very
narrow implementation of what an LLM could be. Primarily the overly-generalised,
sycophantic, extremely confident, and verbose models. I won't detract from how
many people have been negatively affected by the increasing popularity of this
technology, but I will suggest that we at least try to keep a more open mind.
Approach each use of LLMs on a case-by-case basis, reflect on whether it helped
to progress something or was a complete waste of time. If it's for completing a
task that no person would ever want to do (note how I say *want to do*, not
*could do*), it's likely the former. Also keep in mind how we are early on in
the development of this technology, and once the hype inevitably dies down, we
will really get to see what sticks and what falls flat on its face.
