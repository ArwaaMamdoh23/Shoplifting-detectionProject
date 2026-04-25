# Shoplifting Detection using Video Preprocessing Pipeline

## Overview
This project focuses on building a complete preprocessing pipeline for surveillance video data to prepare it for shoplifting detection using machine learning models.

The system standardizes raw video data by cleaning, resizing, normalizing, and structuring it into a consistent format suitable for training deep learning models.

## Problem Statement
Surveillance video datasets are often inconsistent in resolution, frame rate, and quality. This project solves this by creating a unified preprocessing pipeline that ensures all video inputs are standardized for reliable model training.

## Dataset
- Surveillance videos (.mp4)
- Two classes: Shoplifting / Non-Shoplifting
- Raw real-world-like video data

## Pipeline Stages

### 1. Data Cleaning
- Remove duplicate videos using SHA256 hashing
- Ensure dataset integrity

### 2. Frame Rate Standardization
- Extract FPS using OpenCV
- Convert all videos to 25 FPS

### 3. Resolution Analysis
- Extract unique video resolutions
- Identify dataset inconsistencies

### 4. Video Resizing
- Resize all videos to 640×640
- Preserve aspect ratio using padding

### 5. Normalization
- Apply min-max normalization per frame
- Standardize pixel intensity values

### 6. Dataset Splitting
- 75% training
- 20% validation
- 5% testing

## Output
A fully cleaned and standardized video dataset ready for training a shoplifting detection model.


## Note
This project focuses on data engineering and preprocessing for video-based behavior recognition systems.



## Author
Arwaa Mamdoh
