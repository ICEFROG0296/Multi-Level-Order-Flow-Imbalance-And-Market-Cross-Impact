# MultiLevelOrderFlowImbalanceAndMarketCrossImpact

## Overview
This repository contains the implementation of a quantitative study on **Order Flow Imbalance (OFI)** metrics and their impact on equity markets, focusing on:
- **Multi-level Limit Order Book (LOB)** dynamics.
- **Cross-asset impacts** and predictive modeling of price changes.

Key objectives:
1. Calculate **Order Flow Imbalance (OFI)** at multiple levels of the LOB.
2. Integrate OFI metrics using **Principal Component Analysis (PCA)**.
3. Analyze contemporaneous and lagged **cross-impact** between equities.
4. Evaluate the predictive power of OFI metrics on short-term price changes.

---

## Features
- **Data Preprocessing**: Scripts to clean, preprocess, and extract relevant LOB data.
- **OFI Metric Calculation**: Multi-level OFI computation for bid/ask sides.
- **Cross-Impact Analysis**: Regression-based analysis to measure cross-asset impacts.
- **Visualization**: Generate plots to illustrate trends, relationships, and findings.

---

## Directory Structure
```plaintext
.
├── data/               # Placeholder for raw and processed data
├── notebooks/          # Jupyter notebooks for exploration and analysis
├── scripts/            # Core Python scripts
├── results/            # Outputs (e.g., figures, tables, models)
├── requirements.txt    # Python dependencies
├── README.md           # Project documentation
└── LICENSE             # License file
