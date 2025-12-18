# Dataset Information

The dataset used in this project consists of remote sensing survey maps and thematic maps
prepared specifically for semantic understanding and robustness analysis.

## Dataset Characteristics
- Image size: 256 × 256
- Number of classes: 5
  - LULC
  - River
  - Road
  - Settlement
  - Soil
- Format:
  - Images: JPG
  - Labels: TXT (class index)

## Directory Structure (Local)
train/
 ├── images/
 └── labels/

val/
 ├── images/
 └── labels/

val_1/
 ├── images/
 └── labels/

## Note
The dataset is not publicly shared due to project and academic constraints.
Paths in the notebooks assume this structure when running locally.
