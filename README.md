# Edu-DETR

**Edu-DETR: A Spectral-Spatial Collaborative Network for Efficient Teacher Behavior Analysis in Crowded Classrooms**.

## Status

Our manuscript is currently **under review**.  
The code, pretrained models, and usage instructions are being organized and will be released after the review process is completed.

## Overview

Edu-DETR is an efficient teacher behavior detection framework designed for automated instructional assessment in real classroom environments.

It addresses key challenges in fine-grained teacher behavior analysis, including:

- spatial background redundancy in complex classroom scenes,
- dense crowd occlusion caused by seated students,
- high-frequency visual interference from repetitive classroom structures,
- semantic ambiguity among visually similar pedagogical actions,
- real-time deployment requirements on resource-constrained edge devices.

The framework integrates:

- a Gated Sparse Hybrid Backbone (GSH-Net) for filtering static background redundancy and reducing unnecessary computation,
- a Spectral-Spatial Polarized Encoder (S²P²-Encoder) for suppressing periodic crowd-related interference while enhancing subtle teacher motion cues,
- a Decay-Aware Retention Strategy for distinguishing spatially similar instructional behaviors through multi-scale spatial inductive biases,
- a lightweight feature fusion design that improves behavioral discrimination without increasing inference latency.

## Dataset

We construct **TCB-Det**, a domain-specific benchmark for fine-grained teacher behavior detection in classroom scenes.

TCB-Det is used only for academic evaluation in this study. Due to privacy and ethical considerations related to classroom videos and the presence of minors, the dataset will **not be publicly released**.

The dataset contains annotated images covering five core categories of teacher behaviors:

- Lecturing
- Board Writing
- Roving
- Demonstrating
- Individual Guidance

Although the dataset cannot be shared publicly, the repository will provide implementation details, model configurations, and evaluation protocols to support reproducibility to the extent permitted by privacy constraints.

## Repository Plan

This repository will include:

- training and inference code
- model configuration files
- evaluation scripts
- pretrained model weights, if permitted by the review and privacy requirements
- visualization tools
- usage instructions for reproducing the model architecture and evaluation pipeline

## Citation

If you find this work relevant, please consider citing our paper after publication.  
The citation information will be updated here once the manuscript is accepted.
