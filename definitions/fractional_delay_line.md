## [Fractional Delay Line](#fractional-delay-line)

A a simple digital [delay line](#delay-line) implementation might support delay times that are integer number of samples long, such as 10 samples.

A fractional delay line uses [linear interpolation](#linear-interpolation) to support delay times that fall between an integer number of samples, such as 10.687 samples long.