# PokerMath Research Group (API)

[![Research Portal](https://img.shields.io/badge/Portal-pokermath.org-0d6b3d.svg)](https://pokermath.org)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Open Science: Datasets](https://img.shields.io/badge/Data-Open%20Access-purple.svg)](https://pokermath.org/research/)
[![Affiliation](https://img.shields.io/badge/Institution-Applied%20Probability%20Institute-gold.svg)](https://pokermath.org/about/)

The **PokerMath Research Group** is an independent quantitative research initiative affiliated with the **Applied Probability Institute**. We engineer deterministic mathematical models, open-access stochastic simulation engines, and game-theoretic benchmarks for imperfect information sequential games, with specialized focus on No-Limit Texas Hold'em and modern poker variant economies.

---

## 🔬 Core Open-Source Repositories

| Repository | Focus & Domain | Language / Stack | License |
| :--- | :--- | :--- | :--- |
| **[`poker-monte-carlo`](https://github.com/pokermath-research/poker-monte-carlo)** | High-throughput stochastic Range vs Range Monte Carlo equity engine | Python 3.11 / Bitwise | MIT |
| **[`preflop-equity-matrix`](https://github.com/pokermath-research/preflop-equity-matrix)** | Academic dataset of 1,326 Texas Hold'em starting hand combinations (21 metrics) | CSV / Open Data | CC-BY-4.0 |
| **[`pot-odds-evaluator`](https://github.com/pokermath-research/pot-odds-evaluator)** | Zero-dependency TypeScript/JavaScript pot odds, break-even equity & Kelly criterion library | TypeScript / ESM | MIT |
| **[`research-papers`](https://github.com/pokermath-research/research-papers)** | Preprints, empirical whitepapers, reproducibility test suites, and BibTeX citations | Markdown / LaTeX | Open Access |

---

## 📊 Research Pillars

1. **Stochastic Equity Convergence**: Bitwise evaluation and Monte Carlo simulation scaling under the Law of Large Numbers ($O(1/\sqrt{N})$ error convergence).
2. **Game Theory Optimal (GTO) Equilibria**: Combinatoric range morphology, blocker distribution shifts, and minimum defense frequencies (MDF).
3. **Capital Growth & Risk of Ruin**: Application of the Kelly Criterion, fractional Kelly sizing, and submartingale downswing modeling in finite bankroll regimes.
4. **Market & Rake Microeconomics**: Empirical decomposition of rake drag and player value preservation across global online gaming networks.

---

## 🌐 Publications & Live Interactive Calculators

All research papers, interactive vanilla JavaScript calculators, and comprehensive glossaries are accessible open-access at **[pokermath.org](https://pokermath.org)**:
- **Interactive Pot Odds & Equity Calculator**: [pokermath.org/tools/pot-odds-calculator/](https://pokermath.org/en/tools/pot-odds-calculator/)
- **Expected Value (+EV) Matrix Tool**: [pokermath.org/tools/ev-calculator/](https://pokermath.org/en/tools/ev-calculator/)
- **1,326 Preflop Equity Monte Carlo Study**: [pokermath.org/research/poker-equity-distribution-study/](https://pokermath.org/en/research/poker-equity-distribution-study/)
- **Poker Rake & Value Preservation Benchmark**: [pokermath.org/benchmarks/poker-rake-comparison/](https://pokermath.org/en/benchmarks/poker-rake-comparison/)

---

### Citation

If you utilize our algorithms, simulation code, or datasets in your academic research, please cite:

```bibtex
@article{pokermath2026empirical,
  title={Empirical Distribution of Preflop Equities and Multi-Street Variance in No-Limit Texas Hold'em: A 1,326-Combination Monte Carlo Study},
  author={{PokerMath Research Group}},
  journal={Applied Probability Institute Research Hub},
  year={2026},
  url={https://pokermath.org/research/poker-equity-distribution-study/}
}
```
