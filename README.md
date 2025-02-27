# Edge AI for Continuous Blood Pressure Monitoring

## Project Overview

This repository contains research on developing robust, non-invasive blood pressure monitoring systems using Edge Artificial Intelligence and photoplethysmography (PPG) signals. Our work focuses on creating computationally efficient deep learning architectures that can accurately estimate blood pressure while being deployable on resource-constrained edge devices.

## Research Summary

Our investigation presents a novel methodological framework integrating Edge AI for continuous blood pressure estimation using PPG signals. We evaluated three distinct deep learning architectures:

* A residual-enhanced Convolutional Neural Network
* A transformer-based architecture
* Attentive BPNet (an attention-augmented network)

Through rigorous testing using the MIMIC IV waveform database, our Attentive BPNet architecture demonstrated exceptional performance metrics:
* Systolic Blood Pressure (SBP) estimation: MAE of 6.36 mmHg
* Diastolic Blood Pressure (DBP) estimation: MAE of 4.09 mmHg
* Mean Arterial Pressure (MBP) estimation: MAE of 4.56 mmHg

We also achieved significant model compression (90.71% reduction to 0.13MB) through post-training quantization optimization, enabling deployment on resource-constrained Arduino Nano 33 BLE sense hardware.

## Key Contributions

* Development of a mathematically rigorous and computationally efficient framework for continuous blood pressure monitoring
* Demonstration of the feasibility of implementing sophisticated deep learning architectures on embedded systems
* Establishment of a foundation for developing scalable, personalized health monitoring systems

## Repository Contents

* Presentation slides summarizing our research findings

## Note on Code Availability

**Important**: The original code files are not shared in this repository as we are still in the process of publishing our paper. The code will be made available after publication. Until then, please refer to the attached presentation for an overview of our implementation approach.

## Future Updates

Once our paper is published, we will update this repository with:
* Complete implementation code for all three architectures
* Data preprocessing pipeline
* Model quantization scripts
* Deployment instructions for edge devices

## Citation

If you find our work useful for your research, please consider citing our paper (citation details will be provided after publication).

## Contact

For any questions or inquiries about this research, please open an issue in this repository.

