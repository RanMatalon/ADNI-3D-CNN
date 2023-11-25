# ADNI-3D-CNN
Analyzing 3D FMRI images from ADNI (Alzheimer's Disease Neuroimaging Initiative) dataset with 3D CNN (Convolutional Neural Network).
The images are in nii (Nifti) format and contain 3 dimensions.

The dataset contains 3 labels:
* NC - Normal cognitive
* MCI - Mild cognitive impairment
* AD - Alzheimer Disease

Because of the 3 dimensions, the data any image contains is huge, so it was necessary to resize any dimension by 1/2
(Total data kept from the original image is 1/8).

Pay attention to the 3D-Maxpooling layers, which do the big difference from normal CNN.
The network yielded pretty good result - 93% accuracy.
