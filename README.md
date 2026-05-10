# ClusterX ðŸ”¬

<div align="center">

[![Version](https://img.shields.io/badge/version-0.1.0--dev-blue.svg)]()
[![Python](https://img.shields.io/badge/python-3.10%2B-brightgreen)](https://python.org)
[![License](https://img.shields.io/badge/license-MIT-green)](LICENSE)
[![Status](https://img.shields.io/badge/status-early%20development-orange)]()

**Multi-algorithm unsupervised clustering toolkit â€” K-means, DBSCAN, GMM, and hierarchical clustering from scratch in pure Python/NumPy.**

</div>

---

## Overview

ClusterX implements classic unsupervised clustering algorithms from first principles, with no ML framework dependencies. Designed for learning, experimentation, and lightweight clustering tasks.

## Planned Algorithms

| Algorithm | Type | Status |
|-----------|------|--------|
| K-Means | Centroid-based | ðŸš§ In Progress |
| K-Medoids | Centroid-based | ðŸ“… Planned |
| DBSCAN | Density-based | ðŸ“… Planned |
| OPTICS | Density-based | ðŸ“… Planned |
| Gaussian Mixture Models | Probabilistic | ðŸ“… Planned |
| Hierarchical (Agglomerative) | Hierarchical | ðŸ“… Planned |
| BIRCH | Hierarchical | ðŸ“… Planned |
| Spectral Clustering | Graph-based | ðŸ“… Planned |
| Mean Shift | Mode-seeking | ðŸ“… Planned |

## Features (Roadmap)

- Pure Python + NumPy â€” No sklearn, no deep learning frameworks
- Consistent API â€” `.fit()`, `.predict()`, `.fit_predict()` across all algorithms
- Visualization helpers â€” Plot cluster assignments, centroids, dendrograms
- Evaluation metrics â€” Silhouette score, Davies-Bouldin, inertia
- Automatic parameter tuning â€” Elbow method, silhouette analysis, grid search
- Benchmarking suite â€” Compare algorithms on standard datasets

## Quick Start

```bash
git clone https://github.com/Luv-Goel/clusterx.git
cd clusterx
pip install -r requirements.txt

# Coming soon:
# python -m clusterx --algorithm kmeans --data data.csv --k 5
```

## Architecture (Planned)

```
clusterx/
â”œâ”€â”€ clusterx/
â”‚   â”œâ”€â”€ kmeans.py       # K-Means implementation
â”‚   â”œâ”€â”€ kmedoids.py     # K-Medoids
â”‚   â”œâ”€â”€ dbscan.py       # DBSCAN
â”‚   â”œâ”€â”€ optics.py       # OPTICS
â”‚   â”œâ”€â”€ gmm.py          # Gaussian Mixture Models
â”‚   â”œâ”€â”€ hierarchical.py # Agglomerative clustering
â”‚   â”œâ”€â”€ birch.py        # BIRCH
â”‚   â”œâ”€â”€ spectral.py     # Spectral clustering
â”‚   â”œâ”€â”€ meanshift.py    # Mean Shift
â”‚   â”œâ”€â”€ metrics.py      # Evaluation metrics
â”‚   â”œâ”€â”€ utils.py        # Visualization and helpers
â”‚   â””â”€â”€ cli.py          # Command-line interface
â”œâ”€â”€ tests/
â”œâ”€â”€ notebooks/
â”œâ”€â”€ pyproject.toml
â””â”€â”€ README.md
```

## Project Status

ðŸš§ **Early development** â€” Core K-Means implementation in progress. Contributions and ideas welcome!

## License

MIT â€” see [LICENSE](LICENSE).
