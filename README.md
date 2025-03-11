# Enhanced U-Net Architecture with ResNet Encoder and Attention Mechanisms for Medical Image Segmentation
Glioma is a disease characterized by the growth
of unwanted tissue in the brain. Segmenting brain
lesions in Magnetic Resonance Imaging (MRI)
is challenging due to noise, inhomogeneity, and
deviations in the images. Accurate brain-tumor
segmentation plays a vital role in improving diagnosis and treatment. 

This project explore the use of the U-Net model for tumor segmentation,
with enhancements through ResNet50, spatial attention, and the attention mechanism. Data augmentation is employed to enhance generalizability.
The results indicate that the enhanced
U-Net model with ResNet50 and Attention Mechanism achieves an accuracy of 0.9921, an IoU of
0.4959, a Dice score of 0.1635, and a loss of 0.072.
While the enhanced model does not significantly
outperform the baseline U-Net model in some
metrics, it shows a promising balance between
accuracy and loss, suggesting its potential for further optimization. These results demonstrate the
effectiveness of our approach in improving tumor
segmentation in MRI imaging. 

## Dataset 
The Brain MRI dataset, specifically curated for Glioma
detection and segmentation, was utilized in this project. The
dataset was divided into three subsets: 60% for training (293
samples), 20% for validation (98 samples), and 20% for
testing (98 samples). All images were resized to 250 × 250
pixels during preprocessing to ensure compatibility with the
segmentation model.

<img src="https://github.com/user-attachments/assets/51bb0d21-8e65-441d-a008-cd72035967dd" alt="Screenshot 2024-11-26 130435" width="300" />
<img src="https://github.com/user-attachments/assets/7b6e065e-13a3-4e3c-9ccc-1014e490cb45" alt="Screenshot 2024-11-26 125925" width="300" />

## Example output:
<img src="https://github.com/user-attachments/assets/acc5f465-94ca-4d42-8026-704318a1d53e" alt="Screenshot 2025-03-10 214648" width="300" />
<img src="https://github.com/user-attachments/assets/cb37f4af-d6de-4958-a3d9-b6e2e11d9f94" alt="Screenshot 2024-11-27 022742" width="300" />

## Development Tools 
Python, Tensorflow, Keras, MatplotLib, Jupyter Notebook

## Contributers and Remarks
* Authors Michelle Cheng, Noreen Naz, Maryyam 
* Professor Dr. Hamed Kurumi
