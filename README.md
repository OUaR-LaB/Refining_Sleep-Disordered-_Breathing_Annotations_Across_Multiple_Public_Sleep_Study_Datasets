# Refining_Sleep-Disordered-_Breathing_Annotations_Across_Multiple_Public_Sleep_Study_Datasets
Standardized AASM-compliant refinement of sleep-disordered breathing annotations for SHHS, MrOS, and MESA datasets.

# AASM-Standardized Sleep Annotation Converter

This repository provides Python scripts for generating standardized sleep annotations aligned with the American Academy of Sleep Medicine (AASM) scoring guidelines from raw polysomnography (PSG) data.

The pipeline converts raw EDF signal files and dataset-specific annotation files into a unified, standardized annotation format, enabling consistent downstream analysis across large sleep cohorts.

The conversion has been implemented and validated for the following datasets:

Sleep Heart Health Study (SHHS)

Multi-Ethnic Study of Atherosclerosis (MESA)

Osteoporotic Fractures in Men Study (MrOS)

Each dataset is handled with a dedicated conversion script to account for differences in annotation formats and event naming conventions.
