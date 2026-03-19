# NeuroImaging_MastersProject_2

fNIRS Data Analysis & Image Reconstruction
This repository contains the MATLAB implementation for processing functional Near-Infrared Spectroscopy (fNIRS) data and performing 3D image reconstruction. The project was developed as part of the Imaging for Neuroscience course (AA 2023-2024).

📌 Project Overview
The study focuses on evaluating different motion correction techniques and reconstructing hemodynamic responses (HbO and HbR) from Diffuse Optical Tomography (DOT) data. The data was acquired from an adult subject during a visual stimulation task (rotating checkerboard).

🚀 Key Analysis Steps
Preprocessing: Signal-to-Noise Ratio (SNR) assessment and channel quality control.

Motion Correction: Comparative analysis of Wavelet filtering, Spline interpolation, and Targeted PCA (tPCA).

3D Reconstruction: Mapping concentration changes onto MNI152 atlas meshes (Gray Matter and Volumetric) using the Jacobian matrix.

Visualization: Spatiotemporal analysis of brain activation at specific time points (0s, 10s, 15s, 20s).

🛠️ Tools & Requirements
Language: MATLAB

Toolboxes: Homer2, iso2mesh

Anatomical Reference: MNI152 Atlas

📊 Results Summary
The analysis identified Wavelet filtering as the most robust method for this dataset, effectively removing motion artifacts without compromising the physiological signal. Reconstructed images successfully localized the lateralized response in the visual cortex during stimulus presentation.
