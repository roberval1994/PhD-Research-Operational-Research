# Pesquisa de Doutorado — Pesquisa Operacional (UNIFESP / ITA)

**Otimização de redes de monitoramento de chuva: da geoestatística à computação quântica**

🌐 **Idioma / Language:** **Português** | [English](README.md)

---

[![Field](https://img.shields.io/badge/Área-Pesquisa%20Operacional-blue.svg)]()
[![Institution](https://img.shields.io/badge/UNIFESP-ITA-003366.svg)]()
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

## Sobre esta pesquisa

Este repositório é o **hub** da minha pesquisa de doutorado em **Pesquisa Operacional** na
**UNIFESP / ITA**. A linha de pesquisa aborda um único problema aplicado — **onde alocar
estações de monitoramento de chuva para melhor atender uma cidade** — sob três ângulos
complementares: estatística espacial, otimização matemática e computação quântica.

Em conjunto, os três estudos avançam de *estimar* o campo de chuva, para *otimizar* a rede
de forma clássica, e para *explorar* abordagens quânticas para a mesma decisão.

## Linha de pesquisa

```
          ┌─────────────────────────────────────────────────────────┐
          │   Onde alocar pluviômetros para melhor atender a cidade? │
          └─────────────────────────────────────────────────────────┘
                    │                 │                   │
         ┌──────────▼─────┐ ┌─────────▼────────┐ ┌────────▼───────────┐
         │   Estudo 1     │ │    Estudo 2      │ │     Estudo 3       │
         │ Estimar o      │ │ Otimizar a rede  │ │ Explorar otimização│
         │ campo de chuva │ │ (clássico)       │ │ quântica           │
         │ IDW/Krigagem/  │ │ MCLP, K-Means,   │ │ QUBO + QAOA        │
         │ Splines        │ │ guloso, híbridos │ │ (Qiskit)           │
         └────────────────┘ └──────────────────┘ └────────────────────┘
```

## Os três estudos

| # | Estudo | Métodos principais | Repositório |
|---|---|---|---|
| 1 | **Interpolação Espacial de Precipitação em Redes Esparsas** | IDW, Krigagem Ordinária, Splines; validação cruzada | [repo](https://github.com/roberval1994/Spatial-Interpolation-of-Precipitation-in-Sparse-Rainfall-Networks) |
| 2 | **Otimização Multiobjetivo de Redes Urbanas de Pluviômetros** | MCLP (exato), K-Means ponderado, guloso, híbridos | [repo](https://github.com/roberval1994/Multiobjective-Optimization-of-Urban-Rain-Gauge-Networks) |
| 3 | **Otimização Quântica de Redes de Pluviômetros** | Formulação QUBO, QAOA (Qiskit) | [repo](https://github.com/roberval1994/Quantum-Optimization-Rain-Gauge-QUBO-QAOA) |

## Contribuições

- Um pipeline reprodutível que vai dos dados brutos de pluviômetros às redes de monitoramento otimizadas.
- Benchmarking sistemático de otimização exata, heurística, híbrida e quântica.
- Aplicação real a São José dos Campos (SP, Brasil), integrando população, risco hidrológico e precipitação.

## Reconhecimento

🏆 **3º Lugar – Best Paper Award, ICPR-A 2026.**

## Tecnologias ao longo da pesquisa

`Python` · `GeoPandas` · `PyKrige` · `PuLP` (CBC) · `Gurobi` · `Qiskit` · `scikit-learn` · `Folium`

## Autor

**Roberval Gonçalves Moreira Filho**
Cientista de Dados | Analista de Pesquisa Operacional — Doutorando, UNIFESP/ITA

[![Email](https://img.shields.io/badge/Email-roberval.researcher.or%40outlook.com-red)](mailto:roberval.researcher.or@outlook.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-robervalOr-blue)](https://www.linkedin.com/in/robervalOr)
[![Lattes](https://img.shields.io/badge/Lattes-CNPq-00599C)](http://lattes.cnpq.br/4394523940603239)
[![GitHub](https://img.shields.io/badge/GitHub-roberval1994-black)](https://github.com/roberval1994)

## Licença

Distribuído sob a Licença MIT. Veja [LICENSE](LICENSE).
