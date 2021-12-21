# Overview

JABS projects are separated into 5 major steps: Data acquisition, Behavior annotation, Classifier training, Behavior characterization, and Data integration
Here we provide a concise location for finding instructions on how to complete each step.

Note: This pipeline is still a work in progress. Some links may not yet be public, as we are still working on obtaining licenses for the work.

# Data acquisition

## Hardware

We plan on migrating the items and instructions into a wiki format. However, they are currently available in the following format:
1. [Parts List](JABS&#32;Acquisition&#32;Parts&#32;List.csv)
2. [3D Printed Part Models](DesignFiles/)
3. [3D Model of assembled arena](JABS_hardware_arena.stl.zip)
4. [Hardware Setup](Multi-day&#32;setup&#32;PowerPoint&#32;V3.pptx)

## Recording Software

We share our recording software, which includes 2 components:
1. [Control Server](https://github.com/KumarLabJax/JABS-recording-control-server), which runs on a raspberry pi 3 (or newer) that acts as a web portal
2. [Recording Devices](https://github.com/KumarLabJax/JABS-device-client), which runs on ever recording device.

## Pose Estimation

We predict mouse poses using the following codebase: [link](https://github.com/KumarLabJax/deep-hrnet-mouse).
To find our trained model for single mouse pose, please review the license and find it here: [link](https://zenodo.org/record/5708437)
Our multi-mouse pose model will be released in the future.

# Behavior Annotation and Classifier Training

For classifying behavior, we developed the following software: [link](https://github.com/KumarLabJax/JABS-behavior-classifier)

# Behavior Characterization and Data Integration

For sharing models and integrating genetics, we've developed the following software: [link](https://github.com/KumarLabJax/JabsWebserver)
