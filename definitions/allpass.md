## [Allpass](#allpass)

Formally a [filter](#filter), but it doesn't change the frequency content, only the phase.

All frequencies pass through unaffected, hence the name "all pass."

A building block used in reverbs.

It's made by adding a [feedforward delay](#feedforward-delay) and then subtracting a [feedback delay](#feedback-delay) — both using the same [coefficients](#coefficient).

It was invented specifically to create a digital delay that doesn't impact the frequency response of a signal, like a [comb filter](#comb-filter) does.

---

1. http://www2.ece.rochester.edu/courses/ECE472/resources/Papers/Schroeder_1961.pdf