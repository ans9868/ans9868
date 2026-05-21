# Hi, I'm Adel

I just graduated from **NYU** with a CS B.S. (and a Math minor), specializing in Computational Neuroscience. Because reading neural time-series data isn't painful enough, I do heavy software engineering and distributed systems work on the side. 

When I have free time, I actively contribute to [ray-project/ray](https://github.com/ray-project/ray) or read big books that are hard to understand.

---

## 🛠️ My "Specialties"

* **Scalability over usability:** If it doesn't require a distributed cluster to compute linear regression, I don't want it.
* **103% CPU usage:** Maximizing process efficiency by making my local cooling fans sound like a jet engine.
* **Running large jobs on login nodes:** The ultimate life hack. Keeps my cluster fair-share (`sshare`) metric low while ruining the day for everyone else SSH'd into the cluster.
* **AI force push and pray:** Letting my AI fix my colleagues AI slop code.
* **Fudging ML accuracy at all costs:** Tuning is expensive, so I optimize performance by seamlessly leaking my training data directly into my test validation loop.
* **Never doing PRs on local fixes:** If it works on my machine's specific hardcoded path layout, it's ready for production.
* **Stating "STEM is dead":** Considering to switch to painting, but still finishing my math problem sets and manually debugging dependencies until 3:00 AM.

---

## 📦  Open-Source Work: Ray Contributor

* **[In Review] [#63547 Docs: Python Dependency Guide](https://github.com/ray-project/ray/pull/63547):** Added a developer guide mapping Ray's 3-layer dependency graph, `uv` conflict resolution workflows, and cross-platform architecture edge cases.
* **[Merged] [#60522 Modernize AxSearch API to 1.x](https://github.com/ray-project/ray/pull/60522):** Upgraded core tuning infrastructure for `ax-platform` 1.0+ compatibility and strict error handling.
* **[Closed] [#62596 Split ci_docgpu CPU/GPU depsets](https://github.com/ray-project/ray/pull/62596):** Restructured dependency lockfiles to isolate and resolve complex pip-compile version clashes (`+pt27cpu` vs `+pt27cu128`).
* **[Closed] [#62471 Fix Conda PermissionError on Windows](https://github.com/ray-project/ray/pull/62471):** Isolated container-build race conditions caused by in-place `conda update` behavior during runtime cleanup.

---

## 🔬 Research

* 🧠 **[Under Review / Anonymous Draft] [Evaluation Traps in EEG Disease Classification: Identity Leakage, Lucky Folds, and Objective Mismatch Replicated Across AD, FTD, MDD, and SCZ](https://github.com/ans9868/ans9868/blob/main/lucky-fold-neurips.pdf):** *(Currently under double-blind review for NeurIPS; preprint server migration pending).* Evaluated distributed optimization profiles across multiple neural datasets. Implemented a hybrid **PySpark $\to$ Ray Core** batch data pipeline to isolate and execute thousands of independent, iterative machine learning runs.
---

## 📝 Technical Articles & Data Science

### Featured Writing
* 🌍 **[2 Ways of Analyzing Geographic Culture Through X API v2 + British LLM [Award Winner]](https://medium.com/p/53d26f832876):** An award-winning architectural blueprint on scraping, filtering, and passing regional social telemetry for culture mapping.
* 🐳 **[How You Can Make PySpark Work Across Docker, Singularity, and HPC](https://medium.com/p/890f55970c51):** A deployment manual on bridging heavy enterprise JVM ETL layers across containers and environments (especially  for high-performance computing clusters).
* 💻 **[Fastest Guide to macOS Terminal Setup: Autocomplete, Aliases & Colors](https://medium.com/p/feb48fb35516):** A no-nonsense guide for optimizing Zsh workflows, setting robust aliases, and establishing terminal visual structure.
