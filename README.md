# Ben Cassie — velvetmonkey

**Claims need receipts.**

*Formal verification, AI research, and a healthy allergy to overclaiming.*

Senior Software Architect (ESG data platforms, API architecture) working at the
seam of **formal verification** and **AI research**. I build verified tools for
AI agents and a machine-checked Lean 4 proof corpus. If it is claimed here, it is
proved, tested, or it says plainly what is trusted.

---

## Verified tools for AI agents

| Repo | What it is |
|---|---|
| [mcp-seal](https://github.com/velvetmonkey/mcp-seal) | Verified MCP approval-gate sidecar. A Lean-proven policy monitor that gates `tools/call` until a human approval exists. |
| [flywheel-memory](https://github.com/velvetmonkey/flywheel-memory) | Compounding knowledge-graph memory for AI agents over open markdown. Hybrid search, self-correcting wikilinks, decision-surface retrieval. |
| [roundtable](https://github.com/velvetmonkey/roundtable) | Zero-config MCP server that convenes multiple AI coding CLIs as one council. |
| [canary](https://github.com/velvetmonkey/canary) | LangGraph pipeline for ESG regulatory-change monitoring: fetch, detect, extract, verify, report. |
| [flywheel-ideas](https://github.com/velvetmonkey/flywheel-ideas) | Local-first falsifiable decision ledger. Turns a vault into a compounding decision system with multi-model dissent and outcome-driven refutation. |
| [flywheel-gravity](https://github.com/velvetmonkey/flywheel-gravity) · [vault-core](https://github.com/velvetmonkey/vault-core) · [flywheel-crank](https://github.com/velvetmonkey/flywheel-crank) | The rest of the Flywheel ecosystem: gravity ranking, shared core, and the Obsidian companion plugin. |

---

## The Lean 4 proof corpus

A cited, importable library of machine-checked mathematics spanning the spine of
modern AI: optimisation, dynamical systems, learning theory. Most repos are
zero-`sorry`; each states its axioms and any documented gaps.

**Live landing page: [https://velvetmonkey.github.io/lean/](https://velvetmonkey.github.io/lean/)** **This page is the
index. Start here rather than hunting the individual repos.**

### Convex optimisation and gradient methods
| Repo | Result |
|---|---|
| [gradient-descent-lean](https://github.com/velvetmonkey/gradient-descent-lean) | GD convergence for smooth convex optimisation. 17 theorems, zero sorry. |
| [nesterov-lean](https://github.com/velvetmonkey/nesterov-lean) | Nesterov accelerated gradient descent. |
| [heavy-ball-lean](https://github.com/velvetmonkey/heavy-ball-lean) | Polyak heavy-ball convergence. |
| [proximal-gd-lean](https://github.com/velvetmonkey/proximal-gd-lean) | Proximal gradient descent for composite objectives. |
| [projected-gd-lean](https://github.com/velvetmonkey/projected-gd-lean) | Projected gradient descent convergence. |
| [subgradient-lean](https://github.com/velvetmonkey/subgradient-lean) | Subgradient method for nonsmooth convex objectives. |
| [mirror-descent-lean](https://github.com/velvetmonkey/mirror-descent-lean) | Mirror descent with Bregman divergence. |
| [frank-wolfe-lean](https://github.com/velvetmonkey/frank-wolfe-lean) | Frank-Wolfe (conditional gradient). |
| [coordinate-descent-lean](https://github.com/velvetmonkey/coordinate-descent-lean) | Cyclic coordinate descent convergence. |
| [admm-lean](https://github.com/velvetmonkey/admm-lean) | ADMM convergence, primal/dual residuals. |
| [newton-lean](https://github.com/velvetmonkey/newton-lean) | Newton's method quadratic convergence. |
| [sgd-lean](https://github.com/velvetmonkey/sgd-lean) | Stochastic gradient descent convergence. |

### Learning theory and online learning
| Repo | Result |
|---|---|
| [pac-learning-lean](https://github.com/velvetmonkey/pac-learning-lean) | PAC learning bounds, Hoeffding inequality. |
| [online-learning-lean](https://github.com/velvetmonkey/online-learning-lean) | FTRL regret bounds for online convex optimisation. |
| [replicator-lean](https://github.com/velvetmonkey/replicator-lean) | Replicator dynamics on the standard simplex. |

### Dynamical systems and stability
| Repo | Result |
|---|---|
| [kuramoto-lean](https://github.com/velvetmonkey/kuramoto-lean) | Finite-N Kuramoto synchronisation. |
| [lyapunov-odes-lean](https://github.com/velvetmonkey/lyapunov-odes-lean) | Lyapunov stability for autonomous ODEs. |
| [lasalle-lean](https://github.com/velvetmonkey/lasalle-lean) | LaSalle's invariance principle. |
| [barbalat-lean](https://github.com/velvetmonkey/barbalat-lean) | Barbalat's lemma and the Lyapunov-Barbalat route. |
| [contraction-lean](https://github.com/velvetmonkey/contraction-lean) | Contraction theory, Banach fixed point. |
| [lotka-volterra-lean](https://github.com/velvetmonkey/lotka-volterra-lean) | Lotka-Volterra predator-prey dynamics. |
| [langevin-lean](https://github.com/velvetmonkey/langevin-lean) | Bounded-noise Langevin dynamics. |

### Distributed systems and consensus
| Repo | Result |
|---|---|
| [crdt-lean](https://github.com/velvetmonkey/crdt-lean) | State-based CRDT convergence (AP): Strong Eventual Consistency, conditional liveness under fairness, concrete instances. |
| [consensus-lean](https://github.com/velvetmonkey/consensus-lean) | Quorum-based consensus safety (CP): quorum intersection implies agreement, at most one value ever chosen. |

### Neural and associative memory
| Repo | Result |
|---|---|
| [hopfield-lean](https://github.com/velvetmonkey/hopfield-lean) | Hopfield network energy descent. |
| [modern-hopfield-lean](https://github.com/velvetmonkey/modern-hopfield-lean) | Modern Hopfield network energy descent. |
| [attention-lean](https://github.com/velvetmonkey/attention-lean) | Hard-attention expressivity (Mathlib). |

### Linear algebra and logic
| Repo | Result |
|---|---|
| [schur-complement-lean](https://github.com/velvetmonkey/schur-complement-lean) | Schur complement nonsingular-inverse API and block matrices. |
| [trace-logic-lean](https://github.com/velvetmonkey/trace-logic-lean) | Hoffman trace logic formalisation. |

### Physics
| Repo | Result |
|---|---|
| [hamiltonian-lean](https://github.com/velvetmonkey/hamiltonian-lean) | Hamiltonian mechanics and Liouville's theorem. |
| [observer-patch-holography](https://github.com/velvetmonkey/observer-patch-holography) | OPH: finite observer-patch reconstruction (active research). |

---

Built in the open. When a repo says zero `sorry`, it means zero `sorry`.

📫 [linktr.ee/thevelvetmonkey](https://linktr.ee/thevelvetmonkey) · [@thevelvetmonke](https://x.com/thevelvetmonke)
