[README.md](https://github.com/user-attachments/files/32546827/README.md)
# Field-Acquired Plant Leaf Image Dataset

## Overview

This repository contains the **40 field-acquired plant leaf images** used for external evaluation of the YOLO-ViT plant disease detection framework.

The dataset contains:

- **21 tomato leaf images**
- **19 orange leaf images**
- **40 images in total**

The images were collected under field/acquisition conditions and are intended to complement evaluation on benchmark datasets such as PlantVillage and PlantDoc.

## Dataset Contents

```text
Field-Acquired-Dataset/
├── images/
│   ├── image_001.jpg
│   ├── image_002.jpg
│   ├── ...
│   └── image_040.jpg
├── metadata.csv
└── README.md
```

## Image Distribution

| Crop | Number of Images |
|---|---:|
| Tomato | 21 |
| Orange | 19 |
| **Total** | **40** |

## Metadata

The `metadata.csv` file provides metadata associated with each image.

Fields:

- `image_id` — unique identifier
- `filename` — corresponding image filename
- `crop` — `Tomato` or `Orange`
- `disease_class` — disease/class label, to be completed from the verified annotation
- `ground_truth_label` — verified ground-truth label, to be completed
- `notes` — optional annotation notes

**No disease labels or prediction results are inferred or assigned in this template.**

## Intended Use

The dataset is provided for:

1. External evaluation of plant disease recognition/detection models.
2. Reproducibility of the field-image evaluation reported in the associated research work.
3. Research on plant disease recognition under less-controlled imaging conditions.

## Relationship to Other Datasets

These images are **not part of the original PlantVillage or PlantDoc datasets**. They constitute a separate field-acquired evaluation set.

## Results

Model predictions and performance metrics are intentionally **not included in this template**. Results should only be added after the corresponding ground-truth labels and experimental outputs have been verified.

## Data Availability

The dataset is made available through this repository for research and reproducibility purposes.

## Citation

If you use this dataset, please cite the associated research article:

> [Add the final article citation here after publication.]

## License

[Add the selected dataset/image license here after confirming that the images can legally be redistributed.]

## Contact

[Add corresponding-author/research-group contact information here.]
