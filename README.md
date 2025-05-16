<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/3/31/Milano-Bicocca_University_logo.svg/1200px-Milano-Bicocca_University_logo.svg.png" height="100"/> <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/c/c3/Python-logo-notext.svg/1869px-Python-logo-notext.svg.png" height="100"/> <img src="https://upload.wikimedia.org/wikipedia/commons/5/53/OpenCV_Logo_with_text.png" height="100"/> <img src="https://static-00.iconduck.com/assets.00/pytorch-icon-1694x2048-jgwjy3ne.png" height="100"/> <img src="https://cdn.prod.website-files.com/646dd1f1a3703e451ba81ecc/64994922cf2a6385a4bf4489_UltralyticsYOLO_mark_blue.svg" height="100"/>  

# COBOL-Litter-Detection 

![COBOL Litter Detection Video](videos/intro.gif)

## Overview

**COBOL (COmmunity-Based Organized Littering)** is a computer vision-based project for my master thesis, designed to detect litter in the wild using deep learning.

The goal of this project is to support environmental monitoring and urban cleanliness by automating the process of identifying various types of litter in images or videos.

## News 🚀 

### UniMiB Trash Dataset 🌱

The **first public multiclass dataset** for litter detection. Based on size instead of typology: stay soon.

<img src = "images/UniMiB_dataset.jpg" width="700">

### Depth YOLO 🔥

We are working on YOLO 4-Channel implementation: a CNN could see better with 3 colour channels + depth relative estimation with SOTA model?

<img src = "images/depth_estimation.png" width="700">

### YOLO p2-p6 architecture on mixed dataset 🧠
We are trying to combine UniMiB, TACO and PlastOPol to train from scratch a YOLO architecture similar to YOLO v5.6u, which used the p6 block in the backbone to identify large objects: we want to catch cigarettes too!

### YOLO hyperparameter tuning
We recorded increases of over 5% in terms of mAP50 on the same datasets as in the paper. 
p.s. *Try enabling the cosine scheduler. It may improve significantly*


## Paper

Our paper is out! You can find it on <a href="https://ieeexplore.ieee.org/document/10761805">**IEEE Xplore**</a>

<img src="images/paper.png" width="700">


## Features

♻️ Introducing new dataset for multiclass litter detection: **UniMiB Trash dataset**.
🔍 Training CNN (YOLO) for Litter Detection with TACO and PlastOPol, SOTA dataset for this task.


## Repository Structure

```
COBOL-Litter-Detection/
┣ 📂 dataset/            # Contains labeled datasets
┣ 📂 models/             # Pre-trained or custom YOLOv8 models
┣ 📂 paper               # Our released paper!
┣ 📂 scripts/            # Python notebook template for train YOLO Model.
┣ 📂 utils/              # Utility functions and helpers
┣ 📂 images-videos/      # Don't care
┣ 📂 thesis              # pdf of full thesis and presentation
📄 README.md          # it's me!
```
