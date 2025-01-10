# Domain Generalization for RF-based Human Activity Recognition

## Introduction
This repository provides the official PyTorch implementation of the method described in the paper: "DGAR: A Unified Framework for RF-enabled Human Activity Recognition".

## Requirements
1. Install `PyTorch` and `torchvision` (we use `pytorch==2.2.2` and `torchvision==0.17.2`).

## Datasets
Our dataset (HUST-HAR) can be available from Google Drive: [HUST-HAR-pt](https://drive.google.com/drive/folders/1zISlWYIZAlm0HuXk60p_KGSOPJiYG0WN?usp=sharing).

Our dataset (HUST-HAR-LFM) can be available from Google Drive: [HUST-HAR-LFM-pt](https://drive.google.com/drive/folders/1nl18n0cvw3FIU0rq66ZtOBrsPMpTPuOJ?usp=sharing).

HUST-HAR includes six activities: lie down, pick up, sit down, stand, stand up, and walk. Each action fold contains six sub-fold (subject 1-6). Each subject repeats 100 times.

For example, standup1.mat is a complex matrix, and the dimension is $270 \times 5000$.

Dimension 270: $3 \times 3 \times 30$, three transmitter antennas, three receiver antennas, 30 subcarriers per antenna pair.

Dimension 5000: a sampling rate of 1000 Hz over a 5-second interval.

## Run
Coming soon


## Reference
```

```
