# A005 — A Novel Methodology Design to Identify the Latent Fingerprint Quality using Learning Assisted Image Processing Technique

**Authors:** Gayathri et al.  
**Year:** 2024  
**Area:** Fingerprint quality assessment  
**Reference:** https://doi.org/10.1109/I-SMAC61858.2024.10714708  
**Reading status:** Not recorded.  
**Priority:** H

## Research question / objective

Develop an AI-based system to evaluate the quality of latent fingerprints and improve their analysis.

## Method and algorithms

- Image preprocessing: Normalization, Gaussian Filter, Histogram Equalization.
- Feature extraction: LBP, FFT, Crossing Number (CN), PCA.
- Classification: Random Forest (RF), Support Vector Machine (SVM).
- Hybrid approach: SVM-RF fusion using weighted predictions.

## Dataset and data availability

- Large forensic fingerprint dataset (>4.6 TB).
- Sources: real crime scenes and controlled environments.
- Different fingerprint quality levels.
- Expert-annotated quality categories.
- Used for model training and validation.
- Availability: Not specified (public/private status unclear).

## Evaluation measures

- Accuracy (%)
- Precision (%)
- Recall (%)
- F1 Score (%)
- Processing Time (ms)

## Main findings

- Hybrid SVM-RF model achieved 97% accuracy.
- Improved fingerprint quality classification.
- Combines the strengths of SVM and Random Forest.
- Potential to improve reliability of forensic fingerprint analysis.

## Limitations or points to verify

- Dataset lacks sufficient diversity of challenging fingerprint samples.
- Further dataset expansion needed.
- Model generalizability could be improved.

## Relevance to my thesis

- AI-based forensic fingerprint analysis.
- Automated image quality assessment.
- Image preprocessing and feature extraction.
- Machine learning for forensic evidence classification.

## Next actions

- [ ] Obtain and review the full text, if accessible through lawful sources.
- [ ] Confirm dataset and code availability and their licenses.
- [ ] Cross-check claimed results and citation metadata against the original publication.
