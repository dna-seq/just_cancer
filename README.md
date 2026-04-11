# ⚠️ This Repository is Archived

This repository is now **archived** and is no longer maintained. 

### Why?
This project was part of the first generation of the **Just DNA-Seq** platform, which utilized the **OakVar** framework. We have since transitioned to a significantly more powerful and modern architecture.

### What should I use instead?
We now use **just-dna-lite**, a lightweight yet more capable platform that brings several major improvements:

👉 **[Get started with just-dna-lite](https://github.com/dna-seq/just-dna-lite)**

### Key Improvements in the New Generation:
* **Enhanced Performance:** Powered by a high-performance PRS engine (using DuckDB/Polars) that is up to 12x faster than traditional tools.
* **AI Module Creator:** A new agentic pipeline that allows you to turn research papers or PDFs into functional genetic annotation modules in minutes.
* **Expanded Capabilities:** Native support for over 5,000+ Polygenic Risk Scores from the PGS Catalog, epigenetic clocks, and comprehensive variant cross-referencing.
* **Local & Private:** Runs entirely on your machine via Podman/Docker—your genomic data never leaves your computer.
* **Modern UI:** Replaces older command-line workflows with an intuitive web interface for uploading VCF files and generating reports.

Most modules from the previous OakVar-based generation that remained scientifically relevant have been ported and optimized for this new platform. We recommend all users migrate to [just-dna-lite](https://github.com/dna-seq/just-dna-lite) for the latest features and updates.

# just_cancer
Cancer postagregator for longevity reporter of Oakvar. It is a part of [Oakvar-Longevity](https://github.com/dna-seq/oakvar-longevity) module.

# Installation
## Installation through Oakvar

From Oakvar store:
```bash
ov module install just_cancer
```
Or make git clone of the current repository directly into "postaggregators" folder of Oakvar:
```bash
git clone https://github.com/dna-seq/just_cancer
```

## Manual installation

Create a folder with the name "just_cancer" in "postaggregators" folder of Oakvar and put it inside all the files from this git repository.

You can join our [discord](https://discord.gg/5WU6aSANXy) if you want to discuss the project or if you encountered any issues.
