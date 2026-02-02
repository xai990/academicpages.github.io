---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* **Ph.D.** in Computer Engineering, Clemson University, Clemson, SC — *Expected May 2026*  
  Advisor: Prof. Melissa C. Smith · GPA: 3.81/4.0
* **M.S.** in Engineering Science, University of the Pacific, Stockton, CA — July 2021  
  GPA: 3.94/4.0
* **B.E.** in Automation Engineering, Changsha University of Science and Technology, Changsha, China — June 2018

Professional Experience
======
* **Applied Research Intern**, MD Anderson Cancer Center, Houston, TX — May 2025 – Nov 2025  
  * Biological reasoning workflows for single-cell epigenomics (H3K4me3, RNAPII); metacell aggregation; validation with biologists (5,065 significant target genes, 96% cross-validation accuracy).

* **Graduate Research Assistant**, Clemson University, Clemson, SC — Jan 2022 – Present  
  * **Latent representation learning & trajectory inference** (Aug 2023 – Present): Hierarchical VAE for biological time-series; latent-space dynamics and pseudotime inference.  
  * **GemDiff** (Jan 2022 – Aug 2023): Transformer-based diffusion model for tumor gene expression; PyTorch DDP/Slurm pipelines; benchmarking (UMAP, distribution matching, functional enrichment).

* **Backend Systems Researcher**, University of the Pacific, Stockton, CA — Aug 2019 – July 2021  
  * A2Cloud-H: hybrid resource recommendation system for scientific workflows on AWS.

Skills
======
* **Machine Learning:** Diffusion models, Transformers, VAEs, GANs; PyTorch (DDP), multi-GPU training, HPC/Slurm, Docker.
* **Computational Biology:** Single-cell multi-omics (scRNA-seq, scATAC-seq), high-dimensional integration, trajectory inference, differential expression, pathway enrichment.
* **Languages & Tools:** Python (Pandas, Scikit-Learn), PyTorch, R; Kubernetes, Linux, AWS/Azure.

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>

Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
