# AASL_WMIO

AASL_WMIO is a paired 31-class wall-mediated indirect observation dataset derived from RGB Arabic Alphabets Sign Language symbols.

## Full Name

**AASL_WMIO** stands for:

**Arabic Alphabets Sign Language Wall-Mediated Indirect Observation Dataset**

## Overview

AASL_WMIO is designed for studying semantic inference from wall-mediated indirect optical observations. In this dataset, the semantic source symbols are derived from the RGB Arabic Alphabets Sign Language (AASL) dataset, while the released images correspond to their paired wall-mediated indirect observations.

The dataset is collected under a controlled indirect-view optical geometry. A display terminal presents a source-domain symbol but remains outside the camera field of view. The emitted light is modulated by an occluder, projected onto a wall, and then recorded by a camera as a wall-borne intensity pattern. Therefore, the captured image does not directly show the source symbol; instead, the category-related information is embedded as weak radiometric variations in the wall-mediated observation.

This dataset can be used for research on indirect optical semantic inference, wall-mediated observation, hidden-scene recognition, non-line-of-sight visual analysis, and security-related optical side-channel studies.

## Dataset Statistics

| Item | Value |
|---|---:|
| Number of classes | 31 |
| Total images | 7,855 |
| Training images | 6,271 |
| Validation images | 1,584 |
| Image format | PNG |
| Native image resolution | 128 × 128 |
| Annotation type | Image-level single-label classification |

## Directory Structure

The released dataset follows an ImageFolder-style structure:

```text
AASL_WMIO_v1.0.0/
├── train/
│   ├── class_01/
│   │   ├── image_0001.png
│   │   └── ...
│   ├── class_02/
│   └── ...
├── valid/
│   ├── class_01/
│   │   ├── image_0001.png
│   │   └── ...
│   ├── class_02/
│   └── ...
└── metadata/
    ├── classes.txt
    ├── split_summary.csv
    └── checksums_sha256.txt
