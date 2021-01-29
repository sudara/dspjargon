## [Fast Fourier Transform](#fast_fourier_transform)
*FFT*
*Radix-2 FFT*

Algorithm invented in 1965 making it efficient to compute the [discrete Fourier transform](#discrete_fourier_transform).

The FFT is built to treat input as if it loops, so except for the case where the input signal is an integer number of cycles, you'll need to use a [window function](#window-function) to improve accuracy.


---
1. [An Algorithm for Machine Calculation of Complex Fourier Series](https://www.ams.org/journals/mcom/1965-19-090/S0025-5718-1965-0178586-1/S0025-5718-1965-0178586-1.pdf)
2. https://www.earlevel.com/main/2002/08/31/a-gentle-introduction-to-the-fft/
3. https://betterexplained.com/articles/an-interactive-guide-to-the-fourier-transform/