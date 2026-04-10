# Sea Ice Concentration from NIMBUS6 SCAMS radiometer

This project implements a geophysical inversion algorithm to estimate Sea Ice Concentration (SIC) using brightness temperature ($T_B$) data from the Scanning Microwave Spectrometer (SCAMS) aboard the NIMBUS-6 satellite. The repository provides tools to process raw radiometric data and derive high-latitude sea ice maps by modeling the microwave emission of the Arctic surface. It accounts for atmospheric interference using ERA5 reanalysis data. 

## Key Features:
1. Multi-Channel Retrieval: Supports single-channel (22.23/31.65 GHz) and dual-channel inversion logic.
2. Physical Modeling: Applies Radiative Transfer Models to correct for atmospheric effects.
3. High-Performance Computing: Optimized with Numba (JIT) for fast processing of large satellite swaths.
4. Advanced Mapping: Uses Pyresample (KD-Tree) for precise geospatial gridding and Cartopy for visualization.
