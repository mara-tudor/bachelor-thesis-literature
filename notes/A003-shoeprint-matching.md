# A003 — Improving and Evaluating Machine Learning Methods for Forensic Shoeprint Matching

**Authors:** Jain et al.  
**Year:** 2024  
**Area:** Footprint Identification and Matching  
**Reference:** https://arxiv.org/abs/2405.14878  
**Reading status:** Not recorded.  
**Priority:** H


## Research question / objective

Develop a machine learning system to compare shoeprints and determine whether they originate from the same shoe

## Method and algorithms

Edge detection, image alignment, similarity feature extraction and Random Forest classification.

## Dataset and data availability

CSAFE datasets containing shoeprints from different shoe models and simulated crime-scene conditions.

## Evaluation measures

Accuracy, AUC, sensitivity, specificity

## Main findings

- Baseline accuracy: 95.7% on clean shoeprints.
- Full model AUC: 0.955 for different shoe models (Pristine 150), compared to 0.780 for baseline.
- Full model accuracy: 88.1–92.46% for blurry levels 2–8.
- Full model accuracy: 72.6% for the most blurry condition (level 10).
- Partial heel accuracy: 86.7%, compared to 67.51% for baseline.
- Training with different shoeprint conditions improved generalization

## Limitations or points to verify

- Simulated crime-scene images rather than actual crime-scene evidence.
- Limited variety of simulated conditions.
- Noise in shoeprint scans affects image alignment.
- Insufficient data for automatic noise removal

## Relevance to my thesis

- AI-based forensic evidence comparison.
- Image processing and feature extraction.
- Automated identification of physical evidence.

## Next actions

- [ ] Obtain and review the full text, if accessible through lawful sources.
- [ ] Confirm dataset and code availability and their licenses.
- [ ] Cross-check claimed results and citation metadata against the original publication.
