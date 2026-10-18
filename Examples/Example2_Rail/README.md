# Example 2: 3D steel rail

Corresponds to Section 3.2 and Figs. 11–12 of the manuscript.

| Parameter | Value |
|---|---|
| Mesh | Spectral elements with polynomial order 2 × 2 × 2 |
| Excitation | Hanning-windowed 50 kHz sinusoidal surface force (y-direction) |
| Wave mode | SH₀-like guided wave |
| Snapshot time | t = 190 μs (y-displacement contour in Fig. 11) |

Import the rail input file and run. Displacement histories extracted at x = 0 / 310 / 610 mm reproduce Fig. 12; the inferred group velocity (~2950 m/s) is consistent with the reference in Ref. [39].
