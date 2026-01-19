# 🖼️ Image Degradation Robustness Analysis

This project evaluates how image degradation techniques — **Gaussian Noise** and **JPEG Compression** — impact object or face detection performance.




# YOLOv8 Noise Robustness Analysis
This repository contains research and implementation for a performance analysis of the YOLOv8n model under various real-world noise conditions. The project evaluates how synthetic degradations affect the model's ability to detect humans in diverse environments.

## Overview
Modern object detectors like YOLOv8 perform exceptionally well on clean benchmark datasets. However, their robustness in safety-critical or low-light environments is often under-explored. This study systematically quantifies the performance degradation of the lightweight YOLOv8n variant when subjected to three common types of image noise.

## Key Objectives

- Evaluate Sensitivity: Quantify the impact of Gaussian, Salt & Pepper, and Poisson noise on detection accuracy.

Identify Failure Points: Determine the "breaking point" thresholds where detection recall collapses.


- Analyze Real-World Scenarios: Simulate conditions such as sensor thermal noise, transmission errors, and low-light (photon-limited) imaging.

Link to full report:[here](https://github.com/Mshahnawaz1/Robustness-of-Yolo8n-Model/blob/main/minor-project-report.pdf) 

[![PDF Preview](https://github.com/Mshahnawaz1/Robustness-of-Yolo8n-Model/blob/main/minor-project-report.jpg)](https://github.com/Mshahnawaz1/Robustness-of-Yolo8n-Model/blob/main/minor-project-report.pdf)

Mohammad Shahnawaz