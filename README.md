# Literature Survey — AI for Physical Forensic Evidence

This public repository collects and organizes research literature for a bachelor's thesis exploring artificial intelligence and machine-learning methods for the **analysis and identification of physical forensic evidence**, especially footwear impressions, latent fingerprints, and bloodstain patterns.

## Scope

The emphasis is on image analysis, quality assessment, segmentation, feature extraction, matching/retrieval, model evaluation, reproducibility, and accessibility of public datasets. Digital/cyber-forensics applications are not the focus.

## Contents

- [`Articole1.xlsx`](Articole1.xlsx) — literature-analysis spreadsheet with objectives, methods, datasets, metrics, findings, limitations and thesis relevance.
- [`notes/`](notes/) — one structured note for each of the nine papers.
- [`references.bib`](references.bib) — BibTeX bibliography for all nine sources.
- [`papers/`](papers/) — the two PDFs of the open access articles.
- [`datasets_and_code.md`](datasets_and_code.md) — collected resources and links related to data, implementations and forensic tools.

## Literature considered

| ID | Source | Evidence area | Notes | Review status |
|---|---|---|---|---|
| A001 | [Enhancing Detection of Bloodstain Patterns and  Footprint Impressions using Deep Learning](https://doi.org/10.1109/ISDFS69419.2026.11459089) | Forensic Bloodspatter and Footprint Detection | [Notes](notes/A001-bloodstain-footprint-detection.md) | Not read |
| A002 | [Coarse-to-Fine Semantic Alignment: A Hybrid Framework for Forensic Shoeprint Retrieval](https://doi.org/10.1109/ACCESS.2026.3695998) | Footprint Identification | [Notes](notes/A002-shoeprint-semantic-retrieval.md) | Not read |
| A003 | [Improving and Evaluating Machine Learning Methods for Forensic Shoeprint Matching](https://arxiv.org/abs/2405.14878) | Footprint Identification and Matching | [Notes](notes/A003-shoeprint-matching.md) | Not recorded. |
| A004 | [Retrieving Shoeprint Images Using Convolutional Neural Networks](https://doi.org/10.1109/MetroXRAINE62247.2024.10796373) | Shoeprint image retrieval | [Notes](notes/A004-cnn-shoeprint-retrieval.md) | Not recorded. |
| A005 | [A Novel Methodology Design to Identify the Latent Fingerprint Quality using Learning Assisted Image Processing Technique](https://doi.org/10.1109/I-SMAC61858.2024.10714708) | Fingerprint quality assessment | [Notes](notes/A005-latent-fingerprint-quality.md) | Not recorded. |
| A006 | [Advancing Forensic Fingerprint Recognition: A Next-Generation Robust Systems Approach](https://ieeencr.christuniversity.in/assets/ICNDSA2026_Schedule.pdf) | Forensic fingerprint recognition | [Notes](notes/A006-robust-fingerprint-recognition.md) | To review |
| A007 | [Machine Learning Based Overlapped Latent Fingerprints Segmentation and Separation](https://doi.org/10.1109/TELFOR.2018.8611914) | Overlapped latent fingerprint analysis | [Notes](notes/A007-overlapped-latent-fingerprints.md) | Abstract reviewed |
| A008 | [Unsupervised machine learning for the detection and interpretation of key features in drip patterns](https://pubmed.ncbi.nlm.nih.gov/41033067/) | Bloodstain pattern analysis (BPA) | [Notes](notes/A008-drip-patterns-unsupervised-learning.md) | Abstract reviewed |
| A009 | [Automating Forensic Analysis: Integrating Machine Learning Algorithms for Forensic Evidence and Serial Killer Profiling](https://doi.org/10.1109/MIUCC62295.2024.10783645) | Forensic evidence analysis and offender profiling | [Notes](notes/A009-forensic-automation-and-profiling.md) | Abstract reviewed |

## Research relevance

The shoeprint studies provide baseline approaches for image alignment, feature extraction, matching, and retrieval, as well as the challenges of low-quality partial impressions and private datasets. The fingerprint studies address image quality, overlapping latent prints, and reliable recognition. The bloodstain studies explore neural classification and interpretable geometric/image features. The offender-profiling study is included as wider background, not as a principal basis for developing a physical-evidence recognition system.

_Last organized: 23 November 2026._
