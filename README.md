# Quantum Decomposition of Financial Markets

This project investigates whether FTSE 100 market fluctuations can be decomposed into sinusoidal basis states in an analogous manner to the decomposition of quantum states in the Infinite Square Well.

Using 10 years of FTSE 100 data, I:
- Calculated log returns
- Applied Fast Fourier Transforms (FFT)
- Constructed power spectra
- Compared dominant frequency components across different years

## Technologies
- Python
- NumPy
- Pandas
- SciPy
- Matplotlib

## Key Findings
Fourier decomposition showed that FTSE 100 returns can be represented as a superposition of sinusoidal basis states, but no set of consistent frequencies was found to dominate market behaviour. Whilst frequency bands corresponding to periods of approximately 2-7 and 7-15 trading days appeared repeatedly across multiple years, their strength varied significantly over time. The most pronounced spectral structure was observed in 2020 during the COVID-19 market shock. Overall, the results suggest that the FTSE 100 behaves as a dynamic system whose frequencies evolve with changing market conditions rather than being governed by a fixed set of cycles.
