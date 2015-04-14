---
layout: post
title: Rules-based Writing
---

{%comment%}
- Better title?
- Picture from thesis
- Examples from thesis
{%endcomment%}

Writing effectively is essential as an academic.  The Ph.D. experience varies
widely even within a field, but one nearly universal component is a ton of
writing.  My advisor burned through several red pens on my thesis, and I wanted
to capture some of what I learned for future (self-)reflection. Who knows?
Perhaps it'll come in handy when I have students of my own.

For me, writing is often a humiliating process: I wrestle with big ideas that
are all mixed with millions of details in my mind. I sometimes spend hours
boggling in vain, trying to organize and serialize the concepts. What comes out
in the end can be a disaster. It often has no clear flow with details
interjected at inopportune places.

Unfortunately, I've found that when I ask for feedback on these types of
drafts, I don't get what I need most.  The received feedback is often focused on
the details of the writing: "eliminate ornate language", "avoid passive voice",
and "use proper grammar". These things are all helpful for writing well, but
most of my struggles with writing are organizational, not
technical.  I think people give this type of feedback because its
easy: either they didn't understand the ideas well enough to see the problems
with the writing, they couldn't think of a way to organize the ideas any
better, or they are looking for a low overhead way to give nominal feedback.
(Consequently, don't take lack of feedback from peers as a sign your writing is
clear; it might be just the opposite.) I'm certainly guilty of giving this type
of feedback
{%comment%}
(as an aside, these days when someone asks for feedback, I try to
go as deep as a I can and then use a timeout to limit the total time cost).
{%endcomment%}

My advisor, [John Ousterhout](http://www.cs.stanford.edu/~ouster), always gave
great writing feedback. It was deep and deeply critical, but it *always*
provided a suggested next step. It's hard to guess how many hundreds of hours he
spent reading nonsense that I wrote.  Slowly reading and rethinking hundreds of
pages of my text gave him ample time to reflect on my writing pathologies.
Eventually, he began using a shorthand notation when the logical structure of
my writing went astray.

If you don't know John, the man is a walking ball of engineering-inspired
[aphorisms and proverbs](http://web.stanford.edu/~ouster/cgi-bin/sayings.php).
He seems to be a firm believer that, though life has complex problems, the
repeated application of a small set of rules can decompose any issue one might
face.

In the end, I became a believer. I've listed the set of sins that John
marked in my writing - often many times per page, often many types
of sin per paragraph.  These now serve as a set of assertions or invariants for
me: whenever I move my cursor out of a paragraph (either freshly-written or
just modified) I recheck for all of these red flags.

The rules are easy to verify - they are almost syntactic. Interestingly,
though, they easily identify conceptual and flow issues. I should say too,
neither my advisor nor I claim credit for the individual rules, but adhering
to this small collection of checks was potent for me. They significantly improved
the flow of ideas in my writing.

There are five rules, each with a pithy name: *topic sentence*, *cross
contamination*, *leading with details*, *finish the thought*, *vague and
mysterious*. Each is explained in more detail below.

**Topic Sentence (TS)**: *90% of paragraphs must start with a topic sentence.*
Is it sometimes advantageous to have topic sentences elsewhere in a paragraph?
Maybe, but don't bother. Putting the topic sentence first gives the paragraph a
clear direction, and it's hard to make an argument that it significantly harms
style.  Another benefit: it's easy to skim though a section (or whole paper)
and get the flow just by reading the first sentence of each paragraph.

*Cheating on TS*: Using a semicolon or colon can be useful to lead into a paragraph
with an independent clause that isn't the topic sentence. This should be
done sparingly, but it works well when transitioning between concepts.
The key here is that the reader shouldn't leave the first sentence without
knowing what the paragraph is going to cover.

**Cross Contamination (CC)**: *Each paragraph must only cover one idea.*  This is
critical to keep from derailing a reader's flow of thought and obscuring the
point that is being made.  As a detail-oriented engineering-type, I feel
the need to touch on everything that is related to the idea at hand. I think
this stems from a two issues.  First, engineers tend to wildly over-estimate
the importance of technical details, and, second, they worry that someone might
think they are dumb if something is omitted.

Paying attention to cross contamination has another important perk: it pushes
for each idea to have a clear "home" in the text. Often, I find that I cross
contaminate bits of the same idea into many points in a text or repeat the same
exception in many places. This is a key indicator that something important
isn't explained adequately. When this happens, it's best to refactor by
collecting the fragmented idea into a single place in the text.

*Cheating on CC*: Repetition of a detail is okay if it's a slippery idea that
the reader is likely forget along the way, but don't be paranoid by referencing
the saying the same thing all over the place. Often explicit repetition can be
avoided by using language that implies "there's more to it" and giving an
explicit reference to the sections that cover the matter to full detail.

{%comment%}
<div style='float: left; width: 50%;'><img src="{{ site.baseurl }}/public/blog/writing/ld.png"></div>
{%endcomment%}

{%comment%}Need an example.{%endcomment%}
**Leading with Details (LD)**: *Get to the key idea __first__ in each unit of
structure (paragraph, section, or chapter).* Suspense is for novels and movies;
in technical writing just give the reader the punchline up front. Write-ups of
evaluation and experiments are prone to this. Often paragraphs or sections
begin by describing configuration and axes rather than a clear description of
the specific problem being illustrated.

{%comment%}Need an example.{%endcomment%}
**Finish the Thought (FT)**: *Spell everything out; never force the reader to
draw inferences.*

{%comment%}Need an example.{%endcomment%}
**Vague and Mysterious (VM)**: *Avoid overloaded sentences that are heavy with
intent and merely confusing for the reader.*
It's tempting as a writer to fuse each sentence with the maximum amount of
meaning possible: crafting each word carefully to hint at and echo the subtle
ideas that draw together all the aspects of the paper. The hope is that the
sentence will read plainly and matter-of-factly for most readers, but for the
mythological "astute" reader it'll truly resonate. In the end, these vagaries
accumulate and wear on readers. They'll easily recognize that the writers think
a lot of themselves, but they're unlikely to be similarly impressed.

When my advisor first presented me with these rules, I was skeptical.  Why
would someone restrict the way they write so severely? Don't the rules generate
work by forcing the writer to jump through a set of hoops?

So, why do I now think these rules work so well? They play to my strengths as
programmer. Testing these rules is rote, mindless, and simple. It's not much
harder than scanning my code for syntax. Sure type systems are restrictive,
sure they force developers to jump through hoops. In the end, though they
reduce cognitive load by giving the developer/writer an easy sanity check. If
none of these rules are violated by a paragraph it's almost certainly clean and
understandable. Further, restricting choice in how to write is a good thing:
good technical writing should focus on organizing concepts rather than
impressing with style. These rules help by forcing focus and decision making on
flow rather style.

Finally, an something of an anti-rule: this style of writing can produce short
paragraphs, which seems to make many writers nervous. Don't sweat it if you
sometimes have paragraphs with just two sentences. Clearly separated and
grouped ideas are more important that textual density.

What simple tricks do you use to detect structural and conceptual issues in
your writing? Do you have simple techniques for guiding your thought and
writing process? I'd love to hear your thoughts.

[@rstutsman](http://twitter.com/rstutsman)
