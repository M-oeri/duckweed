# 📁 Duckweed Dataset

This dataset contains structured image data related to duckweed, including original images, segmentation masks, and associated metadata. It is intended for use in tasks such as image segmentation, feature extraction, and analysis in computer vision projects.

## 📂 Directory Structure

```
uki_w1_p1_a1/
├── uki_w1_p1_a1_d1.json
├── uki_w1_p1_a1_d1.png
├── uki_w1_p1_a1_d1_mask.png
├── uki_w1_p1_a1_d1_masked.png
├── uki_w1_p1_a1_d5.json
├── uki_w1_p1_a1_d5.png
├── uki_w1_p1_a1_d5_mask.png
├── uki_w1_p1_a1_d5_masked.png
├── uki_w1_p1_a1_metadata.json
├── d1/
│   ├── uki_w1_p1_a1_d1_01_mask.png
│   ├── uki_w1_p1_a1_d1_01_masked.png
│   └── ...
└── d5/
    ├── uki_w1_p1_a1_d5_01_mask.png
    ├── uki_w1_p1_a1_d5_01_masked.png
    └── ...
```

## 📝 File Descriptions

- `*.json`: Metadata files containing information such as image-level attributes, labels, or coordinates.
- `*.png`: Original or processed image files.
- `*_mask.png`: Binary segmentation masks highlighting relevant regions.
- `*_masked.png`: Images after applying the corresponding mask.
- `*_metadata.json`: Aggregated metadata for the entire dataset.
- `d1/`, `d5/`: Subfolders containing segmented mask variants of the associated data entries, which are obtained at day 1 or day 5 after cultivation.

## 💡 Intended Use Cases

- Training segmentation models (e.g., U-Net)
- Mask generation algorithm benchmarking
- Preprocessing and visualization for computer vision tasks
