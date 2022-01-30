# DSP Jargon

Every technical field has its technical terms.

However, Digital Signal Processing has a few historical contexts that amplify the obscurity of these terms:

1. Most DSP concepts are rooted in electrical engineering and physics. In some cases they are exact emulations of what happens in the analog world. Components like oscillators and filters existed long before anything digital came on the horizon. The Fourier transform was first described when studying heat transfer, not audio. So remember that the names and concepts make more sense when thinking about manipulating voltage than manipulating float values.

2. It's an academic field rooted in math and physics. Digital algorithms were first developed on mainframes with punch cards by scientists. Remember that academia incentivizes individuals to give a specific name to each and every novel variant of a concept, which results in large organic families of similar sounding terms which are often defined after their technical attributes rather than their pragmatic merits (see: filters).

3. Audio DSP is only one subfield of DSP. Many concepts and terminology are shared by other applied fields, such as power systems, control systems, finance, seismology, etc.

## The Goal

The main goal is to provide a useful, pragmatic and clear way to think about the term. 

The definition should provide that critical but often difficult to find first "hook" for someone trying to wade through muddy waters to understand a term means and where it applies.

A learner might need their memory jogged. A learner might have terms confused and want to clarify the difference or relationship between terms. Or it might be their first time looking the term up and just want the high level concept and context.

The goal is not to teach how a concept works, illustrate its history or show details about it is applied. There are no long explanations, diagrams, illustrations or chunks of code.

Only that first hook...

## Style Guide

1. Concise and plain language is encouraged. Aim for one-liners.
2. Multiple short "angles" or contexts of the word are nice to provide. Provide the most pragmatic and big picture one first (the "what/why") and the more technical definition (the "how") afterwards.
3. Avoid using part of the term in the definition. For example, don't rely on people knowing the word "phase" when defining "linear phase"). 
4. Don't redundantly define sub terms and related terms that the definition depends on. Instead, link to them. For example, "circular buffer" should link to, but not explain "buffer". The exception: when parts of the term need defining but don't need their own entry, such as "shift register" in "linear feedback shift register."
5. Code and math blocks can supplement words when there are canonical recognizable examples. They should be as concise and simple as possible.
6. External links (wikipedia, coursera, etc) belong in the footnotes, not the definition body.
7. Definitions should be singular (cycle vs. cycles).
8. When multiple terms refer to the same thing, the primary definition should be the most colloquially common, and synonyms should be listed inside the definition file.

## Syntax

1. Filenames are all lowercase with underscores between words (snake case)
2. Internal links to other definitions (including the primary h2 title link) are lowercase with hyphens between words (kebab case).
3. Acronyms like SIMD and DAW are an exception. The filename and the link name are then uppercase.
4. Synonyms are listed immediately below the title, one per line


For a file named `term_being_defined.md`
```
## [Term Being Defined](#term-being-defined)
*Some Synonym*
*Some Other Synonym*

Text definition about what it does and maybe a contextually related [term](#term).

Link to some [other definition](#other-definition).

---
1. Visit [External link](http://google.com) on Google.
2. Watch [Some Video](http:///coursera.com/video/link) on Coursera.
```