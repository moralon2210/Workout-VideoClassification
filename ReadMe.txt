# Workout Video Classification — VideoMAE + PyTorchVideo

This repository centers on a single notebook:

**▶️ Open the notebook:** [WorkoutClassificationVideo.ipynb](./WorkoutClassificationVideo.ipynb)

---

## Notebook
This notebook sets up a **VideoMAE-based workflow** for working with short workout/action clips.
It uses:
- **Hugging Face Transformers** (VideoMAE family)
- **PyTorchVideo** utilities for video transforms and sampling 

## Data — Kaggle Workout/Fitness Video Dataset
This project uses the **Workout/Fitness Video** dataset from Kaggle:  
https://www.kaggle.com/datasets/hasyimabdillah/workoutfitness-video

> Recommended layout after download:
```
repo/
├─ data/
│  ├─ <class_name>/
│  │   ├─ clip1.mp4
│  │   └─ ...
└─ WorkoutClassificationVideo.ipynb
