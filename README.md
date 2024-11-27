
# Embolism Detection Using Doppler Ultrasound Signals

## Project Overview

This project focuses on the early detection of embolisms using Doppler ultrasound signals, which are crucial for effective patient care. By analyzing these signals, the project aims to distinguish embolisms from noise using advanced signal processing techniques. The goal is to enhance the reliability of embolism diagnosis through a combination of methods, including peak detection, artifact suppression, and energy analysis.

## Key Features

- **Signal Visualization**: Load and segment WAV audio files, visualize the real and imaginary parts of the recorded signal.
- **Frequency Analysis and Spectrogram**: Calculate and display frequency spectra and spectrograms.
- **Energy Analysis**: Compute energy over epochs and visualize energy variations.
- **Signal Filtering**: Apply low-pass filters and analyze filtered signals to isolate noise.
- **Outlier Removal**: Clean signals by removing outliers and identifying significant noise patterns.
- **Embolism Detection**: Detect embolisms using peak-finding algorithms, visualize detected embolisms, and count occurrences.
- **Envelope Extraction**: Extract and smooth the negative envelope of signals for enhanced analysis.
- **Iterative Detection**: Analyze embolisms across multiple iterations with added noise to detect stable peaks.
- **Artifact Suppression**: Address and suppress artifacts in Doppler signals.
- **Percentile-Based Peak Detection**: Detect peaks using percentile thresholds for refined embolism identification.
- **Peak Selection**: Refine detection by selecting peaks within specific temporal windows.

## Libraries Used

- **NumPy**: For numerical computations and array manipulations.
- **SciPy**: For signal processing (e.g., spectrograms, filters, peak detection).
- **Matplotlib**: For visualizing data and signals.

## Why This Project?

The accurate detection of embolisms using Doppler signals is critical in medical diagnostics. This project combines robust signal processing techniques to create a reliable pipeline for identifying embolisms, contributing to improved clinical outcomes.

