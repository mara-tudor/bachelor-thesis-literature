# A001 — Enhancing Detection of Bloodstain Patterns and  Footprint Impressions using Deep Learning

**Authors:** Dr.Thangavel Murugan et al.  
**Year:** 2026  
**Area:** Forensic Bloodspatter and Footprint Detection  
**Reference:** https://doi.org/10.1109/ISDFS69419.2026.11459089  
**Reading status:** Not read  
**Priority:** H


## Research question / objective

1. classify bloodstain patterns 
2. make demographic predictions about the footprint impressions produced from shoes

## Method and algorithms

Vision Transformer (ViT-Base/16)
ResNet-18

## Dataset and data availability

2.700 bloodstain images from CSAFE, Noblis, Figshare, and Mendeley repositories & 2.400 footwear images from UNB StepUP-P150

## Evaluation measures

Classification Accuracy; confusion matrix analysis; confidence scores (probabilistic outputs)

## Main findings

94.2% (bloodstain patterns classification); 
91.6% (gender prediction from footwear)

## Limitations or points to verify

Similar bloodstain patterns can be difficult to distinguish. Noise, uneven lighting, low contrast and incomplete footwear impressions can affect results. Dataset bias and limited environmental variability may reduce generalization to real crime scenes.

## Relevance to my thesis

DL applied to forensic image analysis

## Next actions

- [ ] Obtain and review the full text, if accessible through lawful sources.
- [ ] Confirm dataset and code availability and their licenses.
- [ ] Cross-check claimed results and citation metadata against the original publication.
