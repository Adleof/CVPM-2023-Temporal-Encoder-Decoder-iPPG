# CVPM-2023-Temporal-Encoder-Decoder-rPPG

This repo is the official implementation of <a href="https://openaccess.thecvf.com/content/CVPR2023W/CVPM/html/Li_A_Temporal_Encoder-Decoder_Approach_to_Extracting_Blood_Volume_Pulse_Signal_CVPRW_2023_paper.html" target="_blank">our paper</a> "A Temporal Encoder-Decoder Approach to Extracting Blood Volume Pulse Signal Morphology from Face Videos" presented at CVPM workshop at CVPR 2023.

10.pdf: Our camera-ready version paper.

mptec.py: Code for converting video into data array

Ground_Truth_preprocessing.ipynb: Code for preprocessing the ground truth PPG signal(For DEAP dataset).

facemesh5ch_normalizedlabel.ipynb: Code for model training/testing.

reautest_facemesh5ch.ipynb: Code for authentication test.

normalized_label22_morefilt.npy: Normalized filtered ground truth for DEAP(Optional, you can generate using code given).

Required package: tensorflow, numpy, scipy, mediapipe, cv2, plotly.

If you find this work useful, please cite the following paper:

```@InProceedings{Li_2023_CVPR,
    author    = {Li, Fulan and Thapa, Surendrabikram and Bhat, Shreyas and Sarkar, Abhijit and Abbott, A. Lynn},
    title     = {A Temporal Encoder-Decoder Approach to Extracting Blood Volume Pulse Signal Morphology From Face Videos},
    booktitle = {Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR) Workshops},
    month     = {June},
    year      = {2023},
    pages     = {5964-5973}
}
```
