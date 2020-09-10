## [Buffer](#buffer)

A bunch of values stored contiguously in memory.

Instead of expecting programs to handle real time audio one value at a time, values are batched into buffers for more efficient processing.

[Delay lines](#delay-line) are implemented with buffers.

Your [DAW](#daw) has input and output buffers to help insure artifact-free and CPU-overload free performance.