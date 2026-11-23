# A002 — Coarse-to-Fine Semantic Alignment: A Hybrid Framework for Forensic Shoeprint Retrieval

**Authors:** HYEONG SEOP SONG et al.  
**Year:** 2026  
**Area:** Footprint Identification  
**Reference:** https://doi.org/10.1109/ACCESS.2026.3695998  
**Reading status:** Not read  
**Priority:** H


## Research question / objective

To develop an AI system that improves shoeprint identification by combining image analysis with textual descriptions of shoeprint patterns, helping distinguish between prints that look similar but have small differences

## Method and algorithms

multimodal AI framework with three main stages. 
1. they trained a visual model on shoe outsole images and then fine-tuned it using real crime-scene shoeprints.
2. they extracted specific tread patterns and connected them with textual descriptions using image and language models.
3. they combined the overall visual features with the smaller pattern details to improve shoeprint retrieval accuracy.

## Dataset and data availability

A private dataset provided by the Korean National Police Agency (KNPA), containing real crime-scene shoeprints and reference shoe outsole images.
- the images are paired and annotated with shoeprint pattern categories identified by forensic experts.
- the dataset is NOT publicly available.

## Evaluation measures

1. Top-K Accuracy: Correct shoeprint within the top K retrieved results.
2. Top-K% Accuracy: Correct shoeprint within a specified percentage of retrieved results.
3. mAP (Mean Average Precision): Overall retrieval accuracy and ranking quality.
4. nDCG: Ranking quality; higher relevance for results appearing near the top.
5. F1 Score: Balance between precision and recall.
6. Weighted F1 Score: F1 score adjusted for class size.
7. Clustered F1 Score: Recognition of similar shoeprint patterns based on semantic similarity, even when exact labels differ.
10. CGE (Cluster Gap Efficiency): Efficiency of clustering improvements in F1 score.

## Main findings

- mAP improvement: +1.6% (TOKEN-ResNet).
- Top-1% accuracy improvement: +2.0% (TOKEN-ResNet).
- Swin Transformer Top-1%: 75.7% → 78.9%.
- Improved ranking of correct shoeprints (e.g. Rank 5 → Rank 1).
- Better identification of small tread patterns.
- Improved retrieval of visually similar and degraded shoeprints.

## Limitations or points to verify

- Private dataset (not publicly available).
- Limited reproducibility due to restricted data access.
- Dependence on expert-defined pattern annotations.
- Complex architecture with relatively high computational requirements.
- Generalization to other forensic datasets not established.

## Relevance to my thesis

- Deep learning for forensic evidence identification.
- Image feature extraction and pattern recognition.
- Combining visual and semantic information.
- Potential application to other types of forensic evidence.

## Next actions

- [ ] Obtain and review the full text, if accessible through lawful sources.
- [ ] Confirm dataset and code availability and their licenses.
- [ ] Cross-check claimed results and citation metadata against the original publication.
