# 🧠 fMRI Data Exploration: Auditory Task Analysis

A hands-on neuroimaging project exploring task-based fMRI data structure,
BOLD signal visualization, and GLM-based activation analysis.

---

## 🔍 Research Background

Functional MRI (fMRI) measures BOLD (Blood-Oxygen-Level-Dependent) signal
changes associated with neural activity. This project uses a publicly available
auditory task dataset to practice the core analysis pipeline:
data loading → preprocessing → GLM → interpretation.

This work is motivated by my research interest in **cognitive aging**,
where fMRI is a key tool for examining brain-behavior relationships.

---

## ✅ What I Have Done

- Downloaded and explored real fMRI data (SPM Auditory, Friston et al., 1995)
  via Nilearn's public dataset fetcher
- Inspected NIfTI file structure: shape, affine matrix, TR, voxel size
- Parsed event timing files (onset, duration, trial_type) and visualized
  BOLD signal time series aligned with task conditions (active vs. rest)
- Identified task-responsive voxels by selecting highest-variance brain voxels

---

## 🚀 What I Plan to Do

- **Step 2 – Preprocessing**: spatial smoothing, brain masking (NiftiMasker),
  detrending, high-pass filtering
- **Step 3 – GLM Analysis**: build design matrix with HRF convolution,
  run first-level GLM, generate activation maps (active > rest contrast)
- **Step 4 – ROI Analysis**: extract signal from auditory cortex ROI,
  relate activation magnitude to behavioral measures
- **Step 5 – Cognitive Aging Application**: apply pipeline to aging datasets,
  examine structural-functional brain-cognition relationships

---

## 📂 Project Structure
```
fmri-analysis/
├── notebooks/
│   ├── step1_data_exploration.ipynb   # NIfTI info, BOLD time series
│   ├── step2_preprocessing.ipynb      # Smoothing, masking, detrending
│   └── step3_glm_analysis.ipynb       # Design matrix, contrast maps
└── README.md
```

---

## 🛠️ Tools & Libraries

| Category | Tools |
|---|---|
| Neuroimaging | Nilearn, Nibabel |
| Data Analysis | NumPy, Pandas, SciPy |
| Visualization | Matplotlib |
| Statistics (R) | tidyverse, psych, lme4, ggplot2 |

---

## 👩‍💻 Author

**Hyesoo Kwon**
B.A. Psychology & Brain Cognitive Science, Ewha Womans University
Research Assistant, Cognitive Aging Lab, Seoul National University

📧 hsookwon@ewhain.net
