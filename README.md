# CuraView-EVD

**Evidence-Annotated Clinical Hallucination Dataset**

Official dataset release for:

**"CuraView: A GraphRAG-Based Framework for Medical AI Hallucination Generation and Detection"**

[![Paper](https://img.shields.io/badge/Paper-coming%20soon-blue)](#citation)
[![Dataset](https://img.shields.io/badge/Status-data%20pending-orange)](#dataset-status)
[![License](https://img.shields.io/badge/License-MIT-lightgrey)](#license)

## Overview

CuraView-EVD is an evidence-annotated dataset of controlled clinical hallucinations in discharge summaries, produced by the CuraView multi-agent pipeline. Each sample contains sentence-level hallucination labels with structured evidence grades (E1--E4) grounded in patient-specific EHR knowledge graphs.

## Dataset Status

**Data will be uploaded soon.** The dataset is currently being prepared for public release. Please check back later or watch this repository for updates.

## Key Characteristics

- **Granularity**: Sentence-level claim verification against patient-specific EHR evidence
- **Evidence grading**: Four-level scheme (E1 strong support, E2 weak support, E3 no support, E4 direct contradiction)
- **Hallucination types**: Seven clinically meaningful categories:
  1. Diagnosis errors
  2. Medication errors
  3. Examination/laboratory result errors
  4. Temporal errors
  5. Numerical value errors
  6. Negation errors
  7. Fabricated-fact errors
- **Source data**: Based on Discharge-Me benchmark (MIMIC-IV derived)
- **Knowledge representation**: Patient-specific GraphRAG knowledge graphs

## Code Repository

The research code is being organized for public release. For the latest code, see:

- **Main repository**: [CuraView](https://github.com/severin-ye/CuraView) (code is being prepared for public release)

## Citation

```bibtex
@misc{curaview_evd2026,
  title  = {CuraView-EVD: Evidence-Annotated Clinical Hallucination Dataset},
  author = {Ye, Severin and Kong, Xiao and He, Xiaopeng and Yan, Guangsu and Peng, Limei and Oh, Dongsuk},
  year   = {2026},
  note   = {Dataset from CuraView multi-agent pipeline},
  url    = {https://github.com/severin-ye/CuraView-EVD}
}
```

## License

- Dataset: To be determined upon release
- Code: MIT License

## Contact

For questions about the dataset, open a GitHub issue.
