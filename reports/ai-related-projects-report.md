---
description: Authored 6/6/24
---

# AI-Related Projects Report

### Machine Learning Configuration and Transformation Pipelines

#### Overview

* **Project**: Exploring machine learning configurations for clear and extensible setups.
* **Objective**: To find a configuration method that offers both clarity and flexibility for specific tasks like transformation pipelines.

#### Steps Taken

1. **Research on Configuration Formats**:
   * Explored various configuration formats, focusing on clarity and extensibility.
   * Selected TOML (Tom's Obvious, Minimal Language) for its human-readable syntax and flexibility.
2. **Implementation in Python**:
   * Set up TOML configuration files for different machine learning tasks.
   * Integrated the configuration files with Python scripts to manage transformation pipelines.
   * Ultimately determined TOML was too limiting and switched to YAML instead
3. **Transformation Pipelines with Albumentations**:
   * Used Albumentations library for image augmentation and transformation.
   * Configured transformation steps such as resizing, normalization, and data augmentation through YAML files.
   * Ensured the configuration allows easy modifications and extensions for different datasets and tasks.
4. **Testing and Validation**:
   * Conducted extensive testing to ensure the transformation pipelines work as expected.
   * Validated the results to confirm that the configurations are correctly applied.

***

### Python Script for Image Processing

#### Overview

* **Project**: Developing a Python script to process and move images based on specific criteria.
* **Objective**: To automate the process of sorting and managing images with low contrast and overexposure issues.

#### Steps Taken

1. **Define Criteria**:
   * Established criteria for identifying low contrast and overexposed images.
   * Set thresholds for contrast levels and exposure values.
2. **Image Processing Techniques**:
   * Utilized OpenCV for image processing tasks.
   * Implemented functions to calculate contrast and exposure levels for each image.
   * Developed algorithms to sort images based on the defined criteria.
3. **Memory Management**:
   * Ensured efficient memory usage when processing large volumes of images.
   * Implemented techniques to load and process images in batches to avoid memory overflow.
4. **Concurrency Handling**:
   * Integrated concurrent processing to speed up the image sorting task.
   * Used Python's `concurrent.futures` module to parallelize the processing of images.
5. **Script Optimization**:
   * Optimized the script for better performance and reliability.
   * Conducted profiling to identify and eliminate bottlenecks.

***

### Simplifying LightningDataModule for ResNet Model in PyTorch Lightning

#### Overview

* **Project**: Simplifying a LightningDataModule class for a ResNet model.
* **Objective**: To streamline the data module for better performance and ease of use in training and evaluation.

#### Steps Taken

1. **Initial Setup**:
   * Created a basic LightningDataModule class for the ResNet model.
   * Defined data loading and preprocessing steps within the class.
2. **Data Preparation**:
   * Implemented efficient data loading mechanisms using PyTorch's `DataLoader`.
   * Applied data augmentation and preprocessing steps using Albumentations.
3. **Modular Design**:
   * Refactored the code to ensure a modular design.
   * Separated data loading, preprocessing, and augmentation into distinct functions.
   * Ensured each function is independently testable and reusable.
4. **Simplification and Optimization**:
   * Simplified the data module by removing redundant code and optimizing the logic.
   * Ensured the data module is easy to read and maintain.
   * Conducted performance testing to verify the improvements.
5. **Integration and Testing**:
   * Integrated the simplified data module with the ResNet training pipeline.
   * Conducted extensive testing to ensure compatibility and performance.
   * Validated the training results to confirm the effectiveness of the simplifications.
