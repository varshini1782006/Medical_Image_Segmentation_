Project : Brain Tumor Segmentation (Otsu vs Sauvola)

Objective:
Segment tumor regions in brain MRI images using classical thresholding techniques.

Methods:

Otsu Thresholding (Global)

Sauvola Thresholding (Adaptive)

Evaluation Metrics:

Dice Score

Jaccard Index (IoU)

Dataset:
Kaggle — Brain Tumor Segmentation Dataset

Key Findings:
Both global and adaptive thresholding struggle to accurately segment tumors due to intensity overlap between tumor and normal brain tissues.




Project : Retinal Vessel Extraction (Niblack vs Sauvola)

Objective:
Extract thin blood vessels from retinal fundus images.

Methods:

Niblack Thresholding

Sauvola Thresholding

Dataset:
Kaggle — DRIVE Dataset

Comparison:
Sensitivity for thin vessel detection

Key Findings:
Adaptive thresholding performs better than global methods.
Sauvola is more stable than Niblack in low-contrast regions, but thin vessel detection remains challenging.

Learning:
Understanding local threshold behavior on thin structures.



Project : Cell Nuclei Separation (Watershed)

Objective:
Separate touching or overlapping cell nuclei.

Method:
Marker-controlled Watershed Segmentation

Dataset:
Kaggle — Data Science Bowl 2018

Comparison:
Watershed with markers vs without markers

Key Findings:
Standard watershed causes over-segmentation.
Marker-controlled watershed significantly improves nucleus separation.

Learning:
Over-segmentation control and importance of marker selection.
