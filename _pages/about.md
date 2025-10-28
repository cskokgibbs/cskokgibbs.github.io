---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Hi there! I'm a fifth year Ph.D. candidate at NYU's Center for Data Science, co-advised by Kyunghyun Cho and Richard Bonneau. 
My research focuses on developing algorithms to infer gene regulatory networks from genome-wide sequencing data. 

During my Ph.D., I developed PMF-GRN, a variational inference framework for single-cell gene regulatory network inference.
This approach uses probabilistic matrix factorization to model the latent activity of transcription factors and their regulatory connections to target genes across cells.
By framing this problem probabilistically, PMF-GRN supports principled model selection by directly comparing generative models and hyperparameters during training,
as well as producing uncertainty estimates for interpreting the model's confidence in each predicted interaction.

I also developed GLM-Prior, a genomic language model that predicts TF-gene regulatory interactions directly from sequence.
GLM-Prior fine-tunes the Nucleotide Transformer to learn regulatory interactions between TFs and their target genes across organisms and cell types.
These predictions can be used as prior knowledge to constrain downstream GRN inference. 
My research is supported by the National Science Foundation Graduate Research Fellowship Program (NSF-GRFP).

I have worked as a research scientist intern at Polymathic AI (2025), and as a Bioinformatics intern at Genentech (2023) in the Sequence Modeling and Regulatory Element Design Group. 
Prior to starting my PhD, I worked as a research analyst in the Center for Computational Biology at the Simons Foundation's Flatiron Institute from 2018 to 2021. 
I hold a Bachelors of Science in Mathematics from the University of Miami.

Outside of research, I enjoy training for marathons, cooking, photography, travelling and reading.

# Publications
Skok Gibbs, C; Chen, A; Bonneau, R; Cho, K.
GLM-Prior: A Genomic Language Model for Sequence-Derived Prior Knowledge in GRN Inference.
NeurIPs (2025) 2nd Workshop on Multi-modal Foundation Models and Large Language Models for Life Science.
[[Paper](https://openreview.net/forum?id=TIUUcBIuk6)
[Code](https://github.com/cskokgibbs/GLM-Prior)]

Kim, JH; Skok Gibbs, C; Yun, S; Song, HO; Cho, K. 
Large-Scale Targeted Cause Discovery via Learning from Simulated Data.
Transactions on Machine Learning Research (TMLR) (2025).
[[Paper](https://openreview.net/forum?id=NVgy29IQw8) |
 [Code](https://github.com/snu-mllab/Targeted-Cause-Discovery)]

Skok Gibbs, C; Mahmood, O; Bonneau, R; Cho, K.
PMF-GRN: A Variational Inference Approach to Single-Cell Gene Regulatory Network Inference using Probabilistic Matrix Factorization.
Genome Biology (2024).
[[Paper](https://doi.org/10.1186/s13059-024-03226-6) | 
[Code](https://github.com/nyu-dl/pmf-grn)]

Özel, MN; Skok Gibbs, C, et al. Coordinated control of neuronal differentiation and wiring by a sustained
code of transcription factors. 
Science (2022).
[[Paper](https://www.science.org/doi/10.1126/science.add1884) | 
[Code](https://github.com/cskokgibbs/DMOLN_NetworkScripts)]

Skok Gibbs, C. et al. High performance single-cell gene regulatory network inference at scale: The Inferelator 3.0. 
Bioinformatics (2022).
[[Paper](https://doi.org/10.1101/2022.09.09.507305) | 
[Code](https://github.com/flatironinstitute/inferelator)]

# Awards
NSF Graduate Research Fellowship Program Recipient (2023-2026).

ICML Computational Biology Workshop Best Poster Award & Spotlight presentation (2023).

Winter Q-Bio Best Poster Award (2020).

# Interviews
Nature Technology Feature: Smart software untangles gene regulation in cells (2022)
[[Link](https://doi.org/10.1038/d41586-022-02826-1)]

# Teaching
NYU Center for Data Science Teaching Assistant: Practical Training (2022, 2023, 2024)

# Volunteering
Co-organizer for NYU AI School 2023 [[Link](https://nyu-mll.github.io/nyu-ai-school-2023/)]