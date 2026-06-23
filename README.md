# Hi, I'm Adel

I just graduated from **NYU** with a CS B.S. (and a Math minor), specializing in Computational Neuroscience. Because reading neural time-series data isn't painful enough, I do heavy software engineering and distributed systems work on the side. 

When I have free time, I actively contribute to [ray-project/ray](https://github.com/ray-project/ray) or read research papers.

---

## 🛠️ My "Specialties"

* **Scalability over usability:** If it doesn't require a distributed cluster to compute linear regression, I don't want it.
* **103% CPU usage:** Maximizing process efficiency by making my local cooling fans sound like a jet engine.
* **Running large jobs on login nodes:** The ultimate life hack. Keeps my cluster fair-share (`sshare`) metric low while ruining the day for everyone else SSH'd into the cluster.
* **AI force push and pray:** Letting my AI fix my colleagues AI slop code.
* **Fudging ML accuracy at all costs:** Tuning is expensive, so I optimize performance by seamlessly leaking my training data directly into my test validation loop.
* **Always merging local fixes:** If it works on my machine's specific hardcoded path layout, it's ready for production.
* **Stating "STEM is dead":** Considering to switch to painting, but still finishing my math problem sets and manually debugging dependencies until 3:00 AM.

---

## 📦 Open-Source Work: Ray Contributor

* **[Bayesian Searcher Stability & Modernization (Ax, Optuna, BayesOpt) #60512](https://github.com/ray-project/ray/issues/60512):** Roadmap for improving Ray Tune Bayesian searchers and dependency modernization.

  - **[Completed] Modernize AxSearch API to 1.x** — [#60522](https://github.com/ray-project/ray/pull/60522)  
    Upgraded the core tuning stack for `ax-platform` 1.0+ compatibility and stricter validation behavior.
    
    - Updated to Ax 1.x-style `ObjectiveProperties` / `objectives={...}` APIs.
    - Handled `AssertionError` cases introduced by stricter Ax 1.0+ checks.
    - Aligned `tune-requirements.txt` and compiled lockfiles with the modern Ax dependency set.

  - **Related CI / dependency work**
    - [#62596](https://github.com/ray-project/ray/pull/62596) — Split `ci_docgpu` CPU/GPU depsets to resolve pip-compile version suffix conflicts.
    - [#62471](https://github.com/ray-project/ray/pull/62471) — Fixed a Windows Conda `PermissionError` caused by in-place update behavior during cleanup.

  - **[Approved] Require `optuna>=3.0.0` in OptunaSearch** — [#64242](https://github.com/ray-project/ray/pull/64242)  
    Updated docs and added a guard rail for Optuna 3.x compatibility.

  - **BayesOptSearch (“silent stop”)**
    - Duplicate suggestions can be filtered after GP saturation, which may end experiments early without a clear signal.
    - Planned fix: warn when duplicate points are dropped.
    - Planned fix: consider a random/exploratory fallback when the GP repeats the same suggestion.
    - Planned fix: document current semantics in docstrings and/or Ray Tune docs.

  - **[Approved] Docs: Python Dependency Guide** — [#63547](https://github.com/ray-project/ray/pull/63547)  
    Added a developer guide covering Ray’s 3-layer dependency graph, `uv` conflict resolution, and cross-platform edge cases.

---

## 🔬 Research

* **[Under Review / Anonymous Draft] [Evaluation Traps in EEG Disease Classification: Identity Leakage, Lucky Folds, and Objective Mismatch Replicated Across AD, FTD, MDD, and SCZ](https://zenodo.org/records/20630665):** *(Currently under double-blind review;).* Evaluated distributed optimization profiles across multiple neural datasets. Implemented a hybrid **PySpark $\to$ Ray Core** batch data pipeline to isolate and execute thousands of independent, iterative machine learning runs.
---

## 📝 Technical Articles & Data Science

### Featured Writing
* 🌍 **[2 Ways of Analyzing Geographic Culture Through X API v2 + British LLM [Award Winner]](https://medium.com/p/53d26f832876):** An award-winning architectural blueprint on scraping, filtering, and passing regional social telemetry for culture mapping.
* 🐳 **[How You Can Make PySpark Work Across Docker, Singularity, and HPC](https://medium.com/p/890f55970c51):** A deployment manual on bridging heavy enterprise JVM ETL layers across containers and environments (especially  for high-performance computing clusters).
* 💻 **[Fastest Guide to macOS Terminal Setup: Autocomplete, Aliases & Colors](https://medium.com/p/feb48fb35516):** A no-nonsense guide for optimizing Zsh workflows, setting robust aliases, and establishing terminal visual structure.
