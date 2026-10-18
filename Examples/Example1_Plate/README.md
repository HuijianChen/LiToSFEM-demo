# Example 1: 2D isotropic plate

Corresponds to Section 3.1 and Figs. 8–10 of the manuscript.

| Parameter | Value |
|---|---|
| Geometry | 100 mm × 100 mm plane-stress plate |
| Material | E = 70 GPa, ν = 0.3, ρ = 2700 kg/m³ |
| Element size | 3.3 mm; 6 GLL points per spectral element |
| Excitation | Hanning-windowed 5-cycle toneburst, f = 500 kHz |
| Boundary | Stress-free on all edges |

Import the plate input file in LiToSFEM. After solving, the total / x-directional displacement contours at t ≈ 10.27 μs reproduce the right panel of Fig. 8. Extract y-displacement time histories at points A and B to reproduce the benchmark comparison shown in Fig. 10.
