# CRT-RSA_LatticeAttack_Analysis
R&amp;D on Coppersmith's modified lattice attack on CRT-RSA combined with Gröbnerbasis computation. An analysis, implementation of tools, and extensions to published attacks for recovering CRT-RSA moduli with (unusually) small decryption-exponents.

## Features

- Implementation of the full attack; Given a (vulnerable) CRT-RSA instance, we factor the modulus $N=p*q$.
- Experimental results and tools
- Tests for analysing different $\delta = \log_N(d)$: asympotical, theoretical, practical
- Plot heatmaps of lattices for visual inspection and pattern recognition
- Tests determining upper bound for successful factor-recoverery
