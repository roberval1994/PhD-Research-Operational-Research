# PhD Research — Operational Research (UNIFESP / ITA)

**Optimization of rainfall monitoring networks: from geostatistics to quantum computing**

🌐 **Language / Idioma:** **English** | [Português](README.pt-BR.md)

---

[![Field](https://img.shields.io/badge/Field-Operational%20Research-blue.svg)]()
[![Institution](https://img.shields.io/badge/UNIFESP-ITA-003366.svg)]()
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

## About this research

This repository is the **hub** of my doctoral research in **Operational Research** at
**UNIFESP / ITA**. The research line tackles a single applied problem — **where to place
rainfall-monitoring stations to best serve a city** — from three complementary angles:
spatial statistics, mathematical optimization, and quantum computing.

Together, the three studies move from *estimating* the rainfall field, to *optimizing*
the network classically, to *exploring quantum* approaches for the same decision.

## Research line

```
          ┌─────────────────────────────────────────────────────────┐
          │   Where to place rain-gauge stations to serve a city?    │
          └─────────────────────────────────────────────────────────┘
                    │                 │                   │
         ┌──────────▼─────┐ ┌─────────▼────────┐ ┌────────▼───────────┐
         │   Study 1      │ │    Study 2       │ │     Study 3        │
         │ Estimate the   │ │ Optimize the     │ │ Explore quantum    │
         │ rainfall field │ │ network (classic)│ │ optimization       │
         │ IDW/Kriging/   │ │ MCLP, K-Means,   │ │ QUBO + QAOA        │
         │ Splines        │ │ greedy, hybrids  │ │ (Qiskit)           │
         └────────────────┘ └──────────────────┘ └────────────────────┘
```

## The three studies

| # | Study | Core methods | Repository |
|---|---|---|---|
| 1 | **Spatial Interpolation of Precipitation in Sparse Networks** | IDW, Ordinary Kriging, Splines; cross-validation | [repo](https://github.com/roberval1994/Spatial-Interpolation-of-Precipitation-in-Sparse-Rainfall-Networks) |
| 2 | **Multiobjective Optimization of Urban Rain-Gauge Networks** | MCLP (exact), weighted K-Means, greedy, hybrids | [repo](https://github.com/roberval1994/Multiobjective-Optimization-of-Urban-Rain-Gauge-Networks) |
| 3 | **Quantum Optimization of Rain-Gauge Networks** | QUBO formulation, QAOA (Qiskit) | [repo](https://github.com/roberval1994/Quantum-Optimization-Rain-Gauge-QUBO-QAOA) |

## Contributions

- A reproducible pipeline from raw rain-gauge data to optimized monitoring networks.
- Systematic benchmarking of exact, heuristic, hybrid, and quantum optimization.
- Real-world application to São José dos Campos (SP, Brazil), integrating population, hydrological risk, and precipitation.

## Recognition

🏆 **3rd Place – Best Paper Award, ICPR-A 2026.**

## Tech stack across the research

`Python` · `GeoPandas` · `PyKrige` · `PuLP` (CBC) · `Gurobi` · `Qiskit` · `scikit-learn` · `Folium`

## Author

**Roberval Gonçalves Moreira Filho**
Data Scientist | Operational Research Analyst — PhD candidate, UNIFESP/ITA

[![Email](https://img.shields.io/badge/Email-roberval.researcher.or%40outlook.com-red)](mailto:roberval.researcher.or@outlook.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-robervalOr-blue)](https://www.linkedin.com/in/robervalOr)
[![GitHub](https://img.shields.io/badge/GitHub-roberval1994-black)](https://github.com/roberval1994)

## License

Released under the MIT License. See [LICENSE](LICENSE).
