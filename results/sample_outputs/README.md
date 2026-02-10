Segmentation Performance (Validation Set)

Dice Coefficient : ~0.48
IoU Score        : ~0.34

Crack Property Extraction:
- Crack area computed from segmented mask
- Crack length computed using skeletonization
- Crack width estimated from area / length

Severity Categories Used:
- No Crack
- Minor Crack
- Moderate Crack

Notes:
- Lightweight CNN trained for limited epochs
- Thin crack segmentation with class imbalance
- Results shown are from unseen validation images

## Results

This folder contains sample outputs and quantitative results from the trained crack detection system.

### Sample Outputs
Images in `sample_outputs/` show:
- Original image with crack highlighted in red
- Predictions on unseen validation data
- Representative cases for No Crack, Minor Crack, and Moderate Crack

### Metrics
- Dice coefficient and IoU are reported on the validation set
- Crack geometry (area, length, width) is computed from predicted masks
- Severity classification is rule-based and explainable

