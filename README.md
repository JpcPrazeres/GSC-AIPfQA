This repository contains the dataset, experimental assets, and results associated with a **subjective quality assessment study** developed in the context of an **ICIP 2026 Grand Challenge**, focusing on **Gaussian Splatting Content (GSC)** and **Adaptive / In-Point Feature Quality Assessment (AIPfQA)**.

The repository aggregates all materials required to understand, reproduce, and analyze the subjective evaluation experiments conducted in this work.

---

## Repository Overview

The repository includes:

- Reference and coded video sequences used in subjective tests  
- Camera path definitions used during rendering or playback  
- Subjective evaluation results and metadata  
- Supporting spreadsheets for experiment analysis  

---

## Repository Structure

```
ICIP2026-GSC-AIPfQA/
├── camera_paths/
│   └── ...                 # Camera trajectories used for rendering / playback
├── videos_ref/
│   └── reference/          # Reference (anchor) video sequences
├── videos_coded/
│   └── coded/              # Coded / processed video sequences under test
├── Results.xlsx            # Aggregated subjective evaluation results
├── Subject_List.xlsx       # List of test subjects and related metadata
├── README.md               # Repository description
└── .gitattributes          # Git configuration for large or binary files
```

---

## Folder and File Descriptions

### 📁 `camera_paths/`
Contains camera trajectory definitions used to render or display the video content evaluated in the subjective experiments. These paths ensure consistent viewpoints and motion across reference and coded sequences.

### 📁 `videos_ref/reference/`
Reference (ground-truth) video sequences presented to subjects. These serve as anchors for quality comparison during the subjective evaluation.

### 📁 `videos_coded/coded/`
Video sequences generated using different processing, compression, or adaptive feature configurations. These are the test stimuli evaluated against the references.

### 📄 `Results.xlsx`
Contains the collected subjective evaluation results, such as Mean Opinion Scores (MOS), confidence intervals, or other derived statistics used for analysis.

### 📄 `Subject_List.xlsx`
Metadata related to test participants, including anonymized subject identifiers and any grouping or screening information used in the study.

---

## Intended Use

This repository is intended for:

- Reproducibility of the subjective quality assessment experiments  
- Analysis of subjective quality scores  
- Benchmarking and comparison of Gaussian Splatting–based representations  
- Research on perceptual quality assessment for 3D and novel view synthesis content  

---

## Notes

- No license is currently specified; usage should follow academic best practices.
- Large binary files (e.g., videos) are tracked using Git attributes where applicable.

---

If you use this repository in academic work, please cite the corresponding ICIP 2026 paper.
