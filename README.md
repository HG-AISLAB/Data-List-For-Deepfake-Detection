# Data-List-For-Deepfake-Detection
This data list was used in the following paper:
'Towards Robust Deepfake Detection based on Heartbeat Analysis'

## Introduction

This dataset is based on the FF++ (FaceForensics++) open dataset for deepfake detection research.   
In this README file, we provide detailed information about the dataset and how to use it for research purposes.

## Dataset Information

- Dataset Name: FF++ (FaceForensics++)
- Dataset Type: uncompressed videos (raw) and compressed videos (c23, c40)
- Number of Raw Dataset: 8,068 fake videos and 1,363 real videos

## Data Filtering

This dataset was constructed based on the following filtering criteria:

1. Only uncompressed videos (raw) were selected to be part of the dataset to avoid video compression noise, which may affect the quality of the HR signal.
2. We selected deepfake videos generated from the same source videos using five different deepfake generation methods (Deepfakes, Face2Face, FaceShifter, FaceSwap, and NeuralTextures).
3. Since the facial region serves as the Region of Interest (ROI) in rPPG, the following criteria were applied for video selection:
   - Videos featuring individuals facing forward.
   - Videos without partial occlusion of faces, such as facial hair, glasses, or accessories.
   - Videos with only one visible person at any given moment.

Considering that each fake video was generated based on two source videos, we only selected fake videos whose source videos both satisfy the criteria.

## Used Experiments

This dataset was used for all of our experiments.  
It consists of a total of 164 videos, with 82 real videos and 82 deepfake videos.

## Dataset Download

You can download this dataset from the following GitHub repository:

[Deepfake Detection Dataset](https://github.com/HG-AISLAB/Data-List-For-Deepfake-Detection.git)

## Reference to the Paper

This dataset was used in the following paper:
[Add the paper title or link here]
