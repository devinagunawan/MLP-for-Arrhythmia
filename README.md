# MLP Model for Arrhythmia Detection 

⚠️ **NOTICE: UNDER REVIEW FOR PUBLICATION** ⚠️
> **Do not copy, reproduce, or distribute this code.** > The contents of this repository are currently under peer review for academic publication. All rights are reserved by the author. Please do not use or adapt these files without explicit permission until the publication process is complete.

## Overview
This repository contains the Multilayer Perceptron (MLP) model developed as part of a Biomedical Engineering thesis project at **Swiss German University**. The AI project focuses on advanced arrhythmia detection, with the model optimized for edge computing and specifically designed for deployment on microcontrollers. 

### Classification Categories
The model is trained to classify ECG signals into **5 distinct classes**:
* **AFIB:** Atrial Fibrillation
* **PREX:** Pre-excitation Syndrome
* **VT:** Ventricular Tachycardia
* **SVTA:** Supraventricular Tachyarrhythmia
* **NSR:** Normal Sinus Rhythm

## Performance Metrics
The MLP model achieves high reliability in distinguishing between these 5 classes, yielding the following overall metrics on our testing data:
* **Accuracy:** 95.74%
* **F1 Score:** 0.96

## Hardware Deployment
This model has been successfully deployed and tested on the **Raspberry Pi Pico 2**. The scripts included in this repository are formatted to run efficiently within the hardware constraints of the Pico 2 environment.

## Dataset
The raw data used to produce both the training and testing datasets (prior to filtering and preprocessing) was sourced from the **MIT-BIH Arrhythmia Database** via PhysioNet:

🔗 **Dataset Source:** [MIT-BIH Arrhythmia Database v1.0.0](https://physionet.org/content/mitdb/1.0.0/)

---
*For any inquiries regarding the code, the thesis project, or the upcoming publication, please contact the repository owner.*
