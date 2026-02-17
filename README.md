# Skeleton850 Dataset

## 1. Introduction

**Skeleton850** is an annotated crack skeletonization dataset for pavement crack detection and analysis. The dataset contains 850 crack mask images along with their corresponding skeletonized versions and preprocessed augmentations, designed to facilitate research in crack topology extraction, morphological analysis, and skeleton-based crack detection methods.

### Dataset Statistics

| Folder | # Images | Description |
|--------|----------|-------------|
| `original_mask/` | 850 | Original binary crack mask annotations |
| `skeletonized_mask/` | 850 | Skeletonized crack masks (single-pixel-width representations) |
| `skeletonized_mask_preprocessed/` | 3,530 | Preprocessed and augmented skeletonized masks |

All images are in **PNG** format.

### Dataset Structure

```
Skeleton850/
├── original_mask/                      # Original binary crack masks
│   ├── 00001.png
│   ├── 00002.png
│   └── ...                             # 850 images total
├── skeletonized_mask/                  # Skeletonized crack masks
│   ├── 00001.png
│   ├── 00002.png
│   └── ...                             # 850 images total
├── skeletonized_mask_preprocessed/     # Preprocessed & augmented skeletonized masks
│   ├── 0001.png
│   ├── 0002.png
│   └── ...                             # 3,530 images total
└── README.md
```

## 2. Sample Visualization

| Original Mask | Skeletonized Mask |
|:---:|:---:|
| ![original](original_mask/00001.png) | ![skeleton](skeletonized_mask/00001.png) |

## 3. License

This dataset is made available for **non-commercial research purposes only**.

## 4. Citation

If you use the Skeleton850 dataset in your research, please cite the following paper:

```bibtex
@article{your_paper,
  title={Your Paper Title},
  author={Your Name and Co-Authors},
  journal={Journal/Conference Name},
  volume={},
  number={},
  pages={},
  year={2026},
  publisher={Publisher},
  doi={},
  url={Your Paper Link Here}
}
```

📄 **Paper Link:** [Your Paper Title](https://doi.org/your-doi-link-here)

> **Note:** Please replace the citation information and paper link above with your actual publication details.

## 5. Contact

If you have any questions about the dataset, feel free to contact:

- 📧 **Email:** [your-email@example.com](mailto:your-email@example.com)

## 6. History

- **Version 1.0** (2026/02) — Initial release
