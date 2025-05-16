# COBOL-Litter-Detection

![COBOL Litter Detection Video](videos/intro.gif)

## Overview

**COBOL (COmmunity-Based Organized Littering)** is a computer vision-based project for my master thesis, designed to detect litter in the wild using deep learning.

The goal of this project is to support environmental monitoring and urban cleanliness by automating the process of identifying various types of litter in images or videos.

## News 🚀 

### Depth YOLO 🔥

![Depth Detection](images/depth_estimation.png)

We are working on YOLO 4-Channel implementation: a CNN could see better with 3 colour channels + depth relative estimation with SOTA model.

[DEPT

### UniMiB Trash Dataset 
The **first public multiclass dataset** for litter detection. Based on size instead of typology: stay soon.

### hyperparameter tuning
We recorded increases of over 5% in terms of mAP50 on the same datasets as in the paper. 
p.s. *Try enabling the cosine scheduler. It may improve significantly*

## Paper


## Repository Structure

```plaintext
COBOL-Litter-Detection/
┣ 📂 dataset/            # Contains labeled datasets
┣ 📂 models/             # Pre-trained or custom YOLOv8 models
┣ 📂 paper               # Our released paper!
┣ 📂 scripts/            # Python notebook template for train YOLO Model.
┣ 📂 utils/              # Utility functions and helpers
┣ 📂 videos/             # Demo videos (e.g., intro.mp4 or intro.gif)
┣ 📂 thesis              # pdf of full thesis and presentation
┣ 📂 README.md           # it's me!
