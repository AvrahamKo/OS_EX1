# OS_EX1

This repository contains starter code for an Operating Systems memory latency exercise.

## Repository Contents

- `memory_latency.cpp` / `memory_latency.h` – main exercise implementation and API.
- `measure.cpp` / `measure.h` – measurement helpers.
- `plot_example.py` – example plotting script for experiment results.
- `Makefile_Example` – example build and packaging file.

## Build

You can compile the program directly with:

```bash
g++ -Wall -std=c++11 -O3 -I. -o memory_latency memory_latency.cpp measure.cpp
```

## Run

```bash
./memory_latency <max_size> <factor> <repeat>
```

The program is expected to print CSV-style output with measured latency values.
