# Monte Carlo for Polymer Reaction Engineering

Hands-on Colab notebooks that teach Monte Carlo simulation from scratch, then apply it to polymer reaction engineering. No prior Monte Carlo experience needed.

Companion to the book **Monte Carlo Methods in Polymer Reaction Engineering: From Mechanisms to Molecular Architecture**. The notebooks focus on running and visualizing the algorithms; the theory and further case studies are in the book.

## Notebooks

| # | Topic | What you'll do | Run |
|---|---|---|---|
| 1 | **Monte Carlo warm-up** | Random numbers, dice, darts and waiting times: the four tricks used everywhere | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/MohammedAlkhayyat/MonteCarloPolymerReactionEngineering/blob/main/01_Monte_Carlo_Warmup.ipynb) |
| 2 | **Chain growth & MWD** | Simulate chains one by one, build molecular weight distributions, combination vs transfer | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/MohammedAlkhayyat/MonteCarloPolymerReactionEngineering/blob/main/02_Chain_Growth_MWD.ipynb) |
| 3 | **Copolymers & composition** | Bernoulli and terminal models, CCD, bivariate length × composition maps | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/MohammedAlkhayyat/MonteCarloPolymerReactionEngineering/blob/main/03_Copolymers_Composition.ipynb) |
| 4 | **Long-chain branching** | Macromonomer pools, branch counting, linear / comb / hyperbranched chains | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/MohammedAlkhayyat/MonteCarloPolymerReactionEngineering/blob/main/04_Long_Chain_Branching.ipynb) |
| 5 | **Step growth & gelation** | AA + BB, AB + A₃, gel point with a disjoint-set (DSU) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/MohammedAlkhayyat/MonteCarloPolymerReactionEngineering/blob/main/05_Step_Growth_and_Gelation.ipynb) |
| 6 | **Gillespie kinetic Monte Carlo** | Adding real time; free-radical polymerization checked against ODEs | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/MohammedAlkhayyat/MonteCarloPolymerReactionEngineering/blob/main/06_Gillespie_Kinetic_MC.ipynb) |
| 7 | **Gillespie minis** | Simplified ATRP and polymer degradation | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/MohammedAlkhayyat/MonteCarloPolymerReactionEngineering/blob/main/07_Gillespie_Minis_ATRP_Degradation.ipynb) |

Work through them in order: each notebook builds on the previous one.

## How to run

**In the browser (recommended):** click an *Open in Colab* button, then **Runtime → Run all**. Nothing to install.

**Locally:**

```bash
pip install -r requirements.txt
jupyter notebook
```

Each notebook runs in a few seconds on a normal laptop.

## License

Code: MIT. Text and figures: CC BY 4.0.

## How to cite

If you use these notebooks, please cite both the notebooks and the book. GitHub's **"Cite this repository"** button (right side of the repo page) gives ready-made APA and BibTeX for the notebooks.

**Notebooks**

```bibtex
@software{mc_pre_notebooks,
  author    = {LASTNAME, FIRSTNAME},
  title     = {Monte Carlo for Polymer Reaction Engineering: Teaching Notebooks},
  version   = {1.0.0},
  year      = {2026},
  publisher = {Zenodo},
  doi       = {10.5281/zenodo.XXXXXXX},
  url       = {https://doi.org/10.5281/zenodo.XXXXXXX}
}
```

**Book**

```bibtex
@book{mc_pre_book,
  author    = {LASTNAME, FIRSTNAME},
  title     = {Monte Carlo Methods in Polymer Reaction Engineering: From Mechanisms to Molecular Architecture},
  publisher = {PUBLISHER},
  year      = {2026},
  isbn      = {978-...}
}
```
