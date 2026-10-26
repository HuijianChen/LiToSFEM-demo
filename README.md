# LiToSFEM Demo (v1.0.0)

LiToSFEM is an object-oriented, GUI-driven software for modelling elastic wave propagation based on the time-domain spectral finite element method (TDSFEM). This repository accompanies the manuscript *LiToSFEM: A time-domain spectral finite element method software with interactive GUI for modelling elastic wave propagation* (MEG26-AR-00017R1).

## Contents

| Path | Description |
|---|---|
| `installer/LiToSFEM_demo_setup.exe` | Windows x64 demo installer (uploaded as GitHub Release asset) |
| `Examples/Example1_Plate/` | 2D isotropic plate (corresponds to Figs. 8–10) |
| `Examples/Example2_Rail/` | 3D steel rail SH₀-like guided wave (Figs. 11–12) |
| `Examples/Example3_Crack/` | 3D pipe with transverse crack (Figs. 13–16) |

## System requirements

- Windows 10 / 11 (x64)
- Visual C++ Redistributable (2015–2022)
- ~4 GB RAM recommended for Example 2 / Example 3

## Quick start

1. Download `LiToSFEM_demo_setup.exe` from the [Releases](https://github.com/HuijianChen/LiToSFEM-demo/releases/tag/v1.0.0) page and install.
2. Launch `LiToSFEM.exe`.
3. For each example, import the corresponding input file via **File → Open Project**.
4. Click **Solve** to run the TDSFEM simulation; post-processing results are written to the output file and visualized inside the GUI.

Detailed per-example parameters are documented in each `Examples/*/README.md`.

## Known limitations (consistent with the manuscript)

- The current demo does **not** implement absorbing boundary conditions (ABCs) or perfectly matched layers (PMLs). All examples use free-boundary configurations; reflected wavefronts at model edges are physical free-surface echoes.
- Material damping is not activated in the shipped examples.

## Citation

If you use this demo for academic work, please cite the accompanying paper:

> Chen H. et al. LiToSFEM: A time-domain spectral finite element method software with interactive GUI for modelling elastic wave propagation. *MechanoEngineering* (2026).

A versioned snapshot of this repository is archived on Zenodo: [10.5281/zenodo.xxxxx](https://doi.org/10.5281/zenodo.xxxxx).

## Contact

Correspondence: Huijian Chen (huijianc@foxmail.com)
