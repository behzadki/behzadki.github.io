---
title: "Automated Flake Detection with Deep Learning"
description: "An automated computer vision pipeline for identifying and cataloging 2D material flakes."
img: /assets/img/flake-detection.jpg
img_alt: "Deep learning detection and classification of material flakes in microscope images"
#img_alt: "Microscope image with detected flakes"
importance: 1
category: Research
---


## Overview

This project develops an automated computer vision workflow
for identifying and classifying two-dimensional material
flakes in optical microscope images.

The system supports scientific research by reducing
manual image inspection and organizing detection results
for downstream analysis.

## Methodology

The workflow integrates a DetectoRS-based object
detection model with automated image ingestion,
thickness classification, and structured catalog generation.

Detection outputs are converted into COCO-format
annotations to support dataset regeneration and
subsequent transfer-learning experiments.

## Technical Contributions

My contributions included:

- Developing CSV-to-COCO annotation conversion tools.
- Implementing detection-result organization and prioritization.
- Supporting automated image-processing workflows.
- Integrating software components across evolving environments.
- Supporting feedback-driven model retraining.

## Results

In the reported evaluation, the best transfer-learning
configuration improved overall recall from 0.26 to 0.48,
while maintaining precision at 0.83.

## Limitations

Automatically generated labels can introduce errors
into subsequent training cycles. Human validation
and careful dataset curation remain important.
