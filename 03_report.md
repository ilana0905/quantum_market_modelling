# Quantum Decomposition of Financial Markets: An Investigation into the Basis Frequencies that Dominate the FTSE 100 Fluctuations
In Quantum Physics, any physical state in the Infinite Square Well can be represented as a superposition of energy eigenstates. This project investigates whether a similar decomposition can be applied to FTSE 100 returns, identifying the leading frequencies behind market fluctuations and evaluating their stability through time.

## Physics Background: The Infinitely Deep Well
The Infinite Square Well is a quantum system in which a particle is confined to a finite region of space bounded by infinitely high potential. Since the particle cannot ever escape the well (due to the infinite potential barriers), only sinusoidal solutions are permitted, resulting in a quantised set of energy eigenstates which form a basis for all possible quantum states.
The key takeaway is that any quantum state can be decomposed into linear combinations of oscillatory basis states of discrete frequencies.

The energy eigenstates of the Infinite Square Well are sinusoidal functions:

$\psi_n(x) = \sin\left(\frac{n\pi x}{L}\right), \qquad n = 1,2,3,\ldots$

where $L$ is the width of the well.

Any quantum state may therefore be represented as:

$\Psi(x,t) = \sum_{n=1}^{\infty} c_n \psi_n(x) e^{-iE_n t / \hbar}$

where $c_n$ describes the contribution of each basis state and the complex exponential term governs how the state evolves through time.

## Drawing the Analogy between Quantum Mechanics and Financial Markets
A similar mathematical decomposition can be applied beyond quantum mechanics. Any sufficiently well-behaved signal may be represented as a weighted sum of sinusoidal basis functions of different frequencies. This also closely resembles a Fourier Decomposition.

In this project, we investigate whether fluctuations in the FTSE 100 can be analysed in this quantum-mechanical lens. By identifying which frequencies dominate, we aim to understand whether sinusoidal patterns exist in market behaviour and if these structures remain stable through time.

We begin by decomposing the FTSE 100 data into a sinusoidal basis:

$M(t) = \sum_{n=1}^{N} A_n \sin(\omega_n t + \phi_n)$,

where $A_n$ is the amplitude of each basis state, $\omega_n$ is its angular frequency and $\phi_n$ is a phase offset.
