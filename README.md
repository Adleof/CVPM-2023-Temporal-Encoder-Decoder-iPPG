# CVPM-2023-Temporal-Encoder-Decoder-rPPG

This repo is the official implementation of our paper "A Temporal Encoder-Decoder Approach to Extracting Blood Volume Pulse Signal Morphology from Face Videos" presented at CVPM workshop at CVPR 2023.

10.pdf: Our camera-ready version paper.

mptec.py: Code for converting video into data array

Ground_Truth_preprocessing.ipynb: Code for preprocessing the ground truth PPG signal(For DEAP dataset).

facemesh5ch_normalizedlabel.ipynb: Code for model training/testing.

reautest_facemesh5ch.ipynb: Code for authentication test.

normalized_label22_morefilt.npy: Normalized filtered ground truth for DEAP(Optional, you can generate using code given).

Required package: tensorflow, numpy, scipy, mediapipe, cv2, plotly.
