# Example 3: 3D pipe with transverse crack

Corresponds to Section 3.3 and Figs. 13–16 of the manuscript.

| Parameter | Value |
|---|---|
| Mesh | Spectral elements with polynomial order 3 × 3 × 3 |
| Excitation | 5-cycle Hanning-windowed toneburst, f = 200 kHz, z-direction |
| Defect | Through-thickness transverse crack at mid-span |
| Parametric sweep | Crack lengths l = 0, 19.3, 34.8, 50.2, 65.7, 81.2 mm |

Run each crack-length case sequentially. Extract z-displacement time histories at receiving points C and D to isolate reflected and transmitted wave packets. Reflection coefficient R = A_R/A_inc and transmission coefficient T = A_T/A_inc (Fig. 16) can be evaluated from the corresponding peak amplitudes.
