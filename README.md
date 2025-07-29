# Benchmarking U-NET and Neural Cellular Automata (NCA) for Amodal Image Segmentation

## Introduction: 
This GitHub repository is established to continue researching, benchmarking, and analyzing U-NET and NCA architectures for amodal image 
segmentation. This repository will attempt to establish baselines between both architectures, and provide metrics for evaluating machine 
learning models using convolutional neural networks (CNNs).

The 2025 Lawrence Livermore National Laboratory (LLNL) Data Science Challenge centers on amodal segmentation and occluded content completion, 
utilizing the newly released MOVi-MC-AC dataset, a large-scale, multi-camera video collection with ground truth annotations for modal masks, 
amodal masks, and occluded object content. In response to this challenge, our team conducted a benchmark comparison between the U-Net and Neural 
Cellular Automata (NCA) architectures. NCA is an underexplored architecture, but has shown promising results for image tasks with significantly
less parameters than the U-Net. Our objective was to evaluate their performance, scalability, and adaptability to the dataset's complex multi-view 
and occlusion scenarios. Preliminary results suggest that while U-Net provides stable baseline accuracy and ease of training, NCA demonstrates 
intriguing emergent behavior with a smaller parameter footprint, highlighting its potential for efficient spatial reasoning tasks.

## Challenge Problem: 
The 2025 LLNL Data Science Challenge focused on testing amodal segmentation and occluded content completion using the newly released MOVi-MC-AC dataset—a large-scale, multi-camera video dataset with detailed annotations for visible (modal) masks, full object (amodal) masks, and occluded content. The central challenge was to develop or benchmark models that could infer complete object representations, including parts not directly visible due to occlusion, by leveraging spatial and temporal information across multiple synchronized views.


### Author Notes: 
This research is ongoing alongside other members of the team such as: Melanie Bustos-Gomez, Wesley Hur, Eduardo Lizarzaburu.

Reference models and additional resources are provided by LLNL researchers on their Hugging Face repository: https://huggingface.co/datasets/Amar-S/LLNL_DSC_2025
