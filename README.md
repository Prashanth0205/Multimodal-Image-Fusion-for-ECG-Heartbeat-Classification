# Multimodal Image Fusion for ECG Heartbeat Classification

## Abstract:
The Electrocardiogram (ECG) is a reliable diagnostic tool for critical cardiovascular disorders, including myocardial infarction (MI) and arrhythmia. Due to their
sensitivity to individual differences in ECG signal characteristics, requirement for
explicit feature engineering, and difficulty capturing complex temporal correlations,
machine learning-based approaches for heartbeat classification using ECG may
encounter difficulties. Since deep learning techniques can automatically extract
hierarchical and spatial characteristics directly from raw signal data, they are important for heartbeat classification using ECG, especially when using Convolutional
Neural Networks (CNNs). Using Short-Time Fourier Transform (STFT), Continuos
Wavelet Transform (CWT) and Hilbert-Huang Transform (HHT), we transform the
raw ECG data into three distinct images for input into these frameworks. Finally,
pre-trained models for the classification of ECG heartbeats are trained using these
relevant features. Our investigations on the PTB diagnostics dataset for myocardial
infarction (MI) classification and on PhysioNet’s MIT-BIH dataset for five different
arrhythmia conditions that are consistent with the AAMI EC57 guidelines show the
superiority of the deep learning models used. ResNet-18 gave us the best results
with an accuracy of 98%.

Link to Download Dataset - [Link](https://www.kaggle.com/shayanfazeli/heartbeat)
