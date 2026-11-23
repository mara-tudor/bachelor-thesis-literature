# A004 — Retrieving Shoeprint Images Using Convolutional Neural Networks

**Authors:** Robertson et al.  
**Year:** 2024  
**Area:** Shoeprint image retrieval  
**Reference:** https://doi.org/10.1109/MetroXRAINE62247.2024.10796373  
**Reading status:** Not recorded.  
**Priority:** H

## Research question / objective

Develop an automated system to retrieve matching shoeprints from a database using CNN-based image features.

## Method and algorithms

- Image preprocessing (CLAHE).
- CNN-based feature extraction.
- Feature map comparison using cross-correlation.
- Image scaling and rotation to improve matching.
- Automatic retrieval and ranking of matching shoeprints.

## Dataset and data availability

- FID-300: 300 crime-scene marks, 1,175 reference shoeprints.
- WVU2019: 87 right shoes, 383 crime-scene marks.
- Impress: 300 pairs of shoes, with multiple impressions per shoe.
- Three different datasets used for testing

## Evaluation measures

- Cumulative Matching Probability (CMP).
- S1, S5, S10, S15, S20 (correct match within the top 1%, 5%, 10%, 15% and 20% of results).

## Main findings

- The best FID-300 results were obtained using EfficientNetV2-M with geometric preprocessing.
- The proposed method improved the previous best Top-1% result from 82% to 87.3%

## Limitations or points to verify

- Performance varies considerably between datasets.
- Sensitive to image alignment, rotation and scaling.
- Partial or low-quality shoeprints make matching more difficult.
- Impress dataset produced lower retrieval accuracy.
- Some preprocessing requires compromises, such as automatic cropping that can remove parts of shoeprints

## Relevance to my thesis

- CNN-based forensic image analysis.
- Automatic feature extraction and pattern matching.
- AI-based identification of physical evidence.

## Next actions

- [ ] Obtain and review the full text, if accessible through lawful sources.
- [ ] Confirm dataset and code availability and their licenses.
- [ ] Cross-check claimed results and citation metadata against the original publication.
