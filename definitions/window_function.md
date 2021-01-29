## [Window Function](#window_function)
*Windowing*

Smooths out the input to a [FFT](#FFT) to increase accuracy, as the FFT assumes the input is one cycle of a periodic signal.

It fades in and out the input signal so that it's loopable without [discontinuities](#discontinuities).

---
1. [Understanding FFTs and Windowing](https://download.ni.com/evaluation/pxi/Understanding%20FFTs%20and%20Windowing.pdf)