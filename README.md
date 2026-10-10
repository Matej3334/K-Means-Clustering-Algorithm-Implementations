# K-means Clustering of Waste Collection Sites in Europe

Three implementations of the algorithm: Sequential, Parallel and Distributed.
The algorithm places k processing facilities to minimize distance to waste-wood accumulation sites.

## Features
- Three execution modes: sequential, parallel (multi-threaded), distributed (MPI)
- Configurable number of accumulation sites and clusters
- Random generation of extra sites (within Europe, capacity bounded by the dataset max) when more sites are requested than the dataset has
- Optional GUI with OpenStreetMap, zoom/pan, auto-fit on start (default 800x600, resizable); drawing runs independently of computation threads
- Run-time measurement and cycle counting
- Auto-detection of hardware (CPUs, cores, memory)
