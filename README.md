# DSP Jargon

Every technical field has its technical terms.

However, Digital Signal Processing has a few historical contexts that amplify the obscurity of these terms:

1. Most DSP concepts are rooted in electrical engineering and physics. In some cases they are exact emulations of what happens in the analog world. Components like oscillators and filters existed long before anything digital came on the horizon. The Fourier transform was first described when studying heat transfer, not audio. So remember that the names and concepts make more sense when thinking about manipulating voltage than manipulating float values.

2. It's an academic field rooted in math and physics. Digital algorithms were first developed on mainframes with punch cards by scientists. Remember that academia incentivizes individuals to give a specific name to each and every novel variant of a concept, which results in large organic families of similar sounding terms which are often defined after their technical attributes rather than their pragmatic merits (see: filters).

3. Audio DSP is only one subfield of DSP. Many concepts and terminology are shared by other applied fields, such as power systems, control systems, finance, seismology, etc.

## The Goal

The definitions aim to provide "the most useful or pragmatic way to think about X."

The goal is to provide a reference to jog one's memory or provide the high level concept. It's not to teach how a concept works or how it is applied. Therefore there are no detailed explanations or diagrams.

## Style Guide

1. Concise and plain language is encouraged. Aim for one-liners.
2. Multiple short "angles" or contexts of the word are nice to provide. Provide the most useful one first.
3. Avoid using part of the term in the definition (for example, don't rely on the word "phase" when defining "linear phase")
4. Code and math blocks are encouraged to supplement words if there are canonical and recognizable examples. These should be as generic as possible.
5. Link to (instead of define) sub terms and related terms that the definition depends on. For example, Buffer should link to, but not explain Circular Buffer.
6. External links (wikipedia, coursera, etc) belong in the footnotes, not the definition body.
7. Definitions should be singular (cycle vs. cycles).