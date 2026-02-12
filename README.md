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
└── README.md               # Repository description
```

---

## Folder and File Descriptions

### 📁 `camera_paths/`
Contains camera trajectory definitions used to render or display the video content evaluated in the subjective experiments. These paths ensure consistent viewpoints and motion across reference and coded sequences.

### 📁 `videos_ref/reference/`
Folder containing the reference video sequences presented to subjects.

### 📁 `videos_coded/coded/`
Folder containing the coded video sequences.

### 📄 `Results.xlsx`
Contains the collected subjective evaluation results, such as Mean Opinion Scores (MOS), confidence intervals, or other derived statistics used for analysis.

### 📄 `Subject_List.xlsx`
Information related to test participants, including anonymized subject identifiers and any grouping or screening information used in the study.


---
