# Self-Supervised Learning for Earth Observation: MAE & DINOv2

This repository contains the code for the project:
> **Self-Supervised Learning: MAE & DINOv2 Models and Practical Implementation**  
> **Nishant Gupta**  
> MSc Artificial Intelligence, Technische Hochschule Ingolstadt  
> Supervised by Prof. Dr. Stefan Kugele and Dr. Mohamed Chouai  
> June 2025

## Overview

This work investigates two state-of-the-art self-supervised learning (SSL) models—Masked Autoencoder (MAE) and DINOv2—applied to multispectral satellite imagery using the SSL4EO-S2C dataset. The project covers both a rapid prototype phase (100-patches) and a large-scale experiment (8-bit, 160GB+ dataset).

## Contents

- `/code/Prototype_Implementation.py` — Implements both MAE and DINOv2 on the 100-patches subset (for rapid prototyping and comparison).
- `/code/DINOv2_Implementation.py` — Scaled-up implementation of DINOv2 on the full 8-bit SSL4EO-S2C dataset.

## Datasets

The following publicly available datasets were used in this project:

- **SSL4EO-S2C 100-patches subset:**  
  [Google Drive Download Link](https://drive.google.com/file/d/1sRWcYbaWs-efXza6kw03GlJQdZHq5iRN/view?pli=1)  
  *A small subset (100 patches) used for rapid prototyping and comparison of MAE and DINOv2.*

- **SSL4EO-S2C 8-bit Full Dataset:**  
  [Mediatum (TUM) Download Link](https://mediatum.ub.tum.de/1702379)  
  *The large-scale 8-bit version (40 GB compressed) used for full-scale DINOv2 training.*

> Please refer to the terms and conditions of the dataset providers for usage and citation requirements.
