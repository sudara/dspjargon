## [Convolution](#convolution)

Operation where a signal gets combined with an another signal, usually an [impulse response](#impulse-response), to form a third signal.

Mathematically, the operator used is a star ∗ which can be confusing since the star * is used to represent multiplication in most programming languages.

Algorithmically, you slide a reversed version of the impulse response over the signal.

Convolution in the [time domain](#time-domain) is equal to multiplication in the [frequency domain](#frequency-domain)

---

1. https://www.dspguide.com/ch6/2.htm
2. https://docs.juce.com/master/classdsp_1_1Convolution.html#details