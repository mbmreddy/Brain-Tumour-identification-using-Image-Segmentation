# Brain-Tumour-identification-using-Image-Segmentation
Analysis of 3D brain tumor images for tumour identification can be a tedious task. These volumetric medical images 
present a complex challenge in accurately identifying and classifying tumor regions within the brain.Now the task is 
to identify the tumour regions in the brain image using Image segmentation techniques.

# Dataset
The BRATS 2020 dataset, or Brain Tumor Segmentation Challenge 2020 dataset, is a highly regarded 
resource in medical imaging research.- It plays a critical role in advancing the development and evaluation of 
brain tumor segmentation algorithms.
• The dataset's significance lies in its inclusion of multi-modal MRI scans, encompassing four distinct MRI 
sequences: 
 T1-weighted (T1), 
 T1-weighted with contrast enhancement (T1ce), 
 T2-weighted (T2), and 
 Fluid-attenuated inversion recovery (FLAIR).
• These different imaging modalities provide a comprehensive representation of the diverse characteristics of 
brain tumors in clinical scenarios.
• In our approach, we utilize Flair and T1ce images in two channels of the UNET for image segmentation.-
The output comprises four classes pixels with a size of 128x128, displaying the classes of tumors: core, 
edema, enhancing, and no tumor
