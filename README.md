
This repository contains the implementation of a 3D U-Net model for brain tumor segmentation. We trained the model using the Brad's 2020 dataset, optimizing both the data preprocessing and training pipeline for improved performance.
Data Preprocessing
The dataset originally contained mask values: 0, 1, 2, 4, but the value 3 was missing. We replaced 4 with 3 to maintain consistency.
We cropped the 3D volumes to 128 × 128 × 128 to focus on the region of interest and optimize training efficiency.
Model & Training
Architecture: 3D U-Net
Optimizer: AdamW
Our preprocessing steps and model adjustments aimed to enhance segmentation accuracy while maintaining computational efficiency.
