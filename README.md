# Behavioral Modeling for Autism Severity Prediction

Official implementation of the paper:

**Behavioral Modeling for Autism Severity Prediction:  
A Comparative Analysis of Unimodal and Multimodal Approaches**

## Overview

This repository provides the implementation of three learning scenarios
for ADOS-derived group classification and continuous ADOS score prediction:

1. Skeleton-based motor learning
2. Eye-gaze saliency-based social learning
3. Multimodal social-motor learning

The experiments are conducted using the DREAM dataset.

## Tasks

- Binary ADOS-derived group classification: ASD vs. AD
- Continuous ADOS total score prediction

## Experimental scenarios

### Scenario A: Skeleton-based motor learning

This scenario extracts handcrafted spatial, angular, and statistical
features from upper-body skeletal sequences.

### Scenario B: Eye-gaze saliency-based learning

This scenario projects eye-gaze vectors from the corresponding 3D head
positions and generates KDE-based saliency maps.

### Scenario C: Multimodal social-motor learning

This scenario integrates social and motor features using modality-specific
encoders, unidirectional cross-attention, adaptive gated fusion, and
task-specific prediction heads.
