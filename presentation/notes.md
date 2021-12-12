1) State goal

2) Methods
  - Textbook multiplication
  - Karatsuba
  - Tom Crook

3) DFT
  - Kind of fourier transform
  - Discrete signals
  - Inverse DFT
  - Can be defined over various fields and rings
  - Can be calculated efficiently using FFT (FFT is *algorithm* to compute DFT)
    - `O(n * log(n))` for n-length signals

4) Convolution theory
  - General idea: Combine two signals into one
    - Continuous signals in signal processing
    - Here: Discrete case
  - Two `D`-length signals `x`, `y`
  - Cyclic, negacyclic, acyclic convolution
