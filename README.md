# Hi, I'm Adel Nour

I am **NYU Tandon** graduate who just graduated from **NYU Tandon** (with a Math minor), specializing in Computational Neuroscience. Because reading neural time-series data isn't painful enough, I do heavy software engineering and distributed systems work on the side to scratch the itch. 

When I have free time, I actively contribute to [ray-project/ray](https://github.com/ray-project/ray) or read big books that are hard to understand.

---

## 🛠️ My "Specialties"

* **Scalability over usability:** If it doesn't require a distributed cluster to compute linear regression, I don't want it.
* **103% CPU usage:** Maximizing process efficiency by making my local cooling fans sound like a jet engine.
* **Running large jobs on login nodes:** The ultimate life hack. Keeps my cluster fair-share (`sshare`) metric low while ruining the day for everyone else SSH'd into the cluster.
* **AI force push and pray:** Letting my AI fix my colleagues AI slop code.
* **Fudging ML accuracy at all costs:** Tuning is expensive, so I optimize performance by seamlessly leaking my training data directly into my test validation loop.
* **Never doing PRs on local fixes:** If it works on my local machine's specific path layout, it's ready for production.
* **Stating "STEM is dead":** Threatening to give up and switch to painting, but still finishing my math problems and manually debugging dependency issues until 3:00 AM.

---

## 📦  Open-Source Work: Ray Contributor

When I am practicing real, disciplined engineering, I target the Ray ML tuning and dependency layers:

* **[In Review] [#63547 Docs: Python Dependency Guide](https://github.com/ray-project/ray/pull/63547):** Added a developer guide mapping Ray's 3-layer dependency graph, `uv` conflict resolution workflows, and cross-platform architecture edge cases.
* **[Merged] [#60522 Modernize AxSearch API to 1.x](https://github.com/ray-project/ray/pull/60522):** Upgraded core tuning infrastructure for `ax-platform` 1.0+ compatibility and strict error handling.
* **[Closed] [#62596 Split ci_docgpu CPU/GPU depsets](https://github.com/ray-project/ray/pull/62596):** Restructured dependency lockfiles to isolate and resolve complex pip-compile version clashes (`+pt27cpu` vs `+pt27cu128`).
* **[Closed] [#62471 Fix Conda PermissionError on Windows](https://github.com/ray-project/ray/pull/62471):** Isolated container-build race conditions caused by in-place `conda update` behavior during runtime cleanup.

---

## 📝 Technical Articles & Data Science

### Featured Writing
* 🌍 **[2 Ways of Analyzing Geographic Culture Through X API v2 + British LLM [Award Winner]](https://medium.com/p/53d26f832876):** An award-winning architectural blueprint on scraping, filtering, and passing regional social telemetry for culture mapping.
* 🐳 **[How You Can Make PySpark Work Across Docker, Singularity, and HPC](https://medium.com/p/890f55970c51):** A deployment manual on bridging heavy enterprise JVM ETL layers across containers and environments (especially  for high-performance computing clusters).
* 💻 **[Fastest Guide to macOS Terminal Setup: Autocomplete, Aliases & Colors](https://medium.com/p/feb48fb35516):** A no-nonsense guide for optimizing Zsh workflows, setting robust aliases, and establishing terminal visual structure.
