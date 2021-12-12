# Fast Fourier Transform (2021-11-23)

- Fourier analysis: Decompose signal into frequencies
- Discrete fourier transform DFT: *more* related to Fourier series (of a
  discrete function), *less* to Fourier transform
- DFT can be done as matrix multiplication: Data series times magic matrix
  gives us the ratios of frequencies contained within the signal (i.e. the
  Fourier analysis)
  - O(n^2)
- Fast fourier transform: Algorithm to compute DFT
  - O(n * log n)

## Multiplying polynomials in O(n log n)

- Naive polynomial multiplication in coefficient form: O(n^2)
- But: In point form O(n)
- Naive conversion coefficient to point form O(n^2)
- But DFT allows in O(n log n)
- Hence multipliation as O(n log n) + O(n) + O(n log n) = O(n log n)
