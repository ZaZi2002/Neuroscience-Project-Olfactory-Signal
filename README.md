# Practical Assignment 2: Analysis of Local Field Potential (LFP) Signals from an Olfactory Task

## Overview
This project is part of the **Neuroscience of Learning, Memory, Cognition** course. The main objective is to analyze Local Field Potential (LFP) signals recorded from three different brain regions of an anesthetized rat while it performed an olfactory task. These LFP signals provide insights into how different parts of the brain, including the **Hippocampus (HPC)**, **Olfactory Tubercle (OT)**, and **Medial Prefrontal Cortex (mPFC)**, process olfactory stimuli.

The task involves processing and analyzing the LFP data to understand the brain’s response to different odorants.

## Dataset Description
The LFP dataset consists of signals recorded from three distinct channels:
1. **Hippocampus (HPC)**: Involved in memory formation and spatial navigation.
2. **Olfactory Tubercle (OT)**: Plays a role in processing olfactory (smell) information.
3. **Medial Prefrontal Cortex (mPFC)**: Involved in decision-making, cognitive functions, and controlling emotional responses.

### Experiment Setup
The rat was exposed to two different odorants while under anesthesia, and the corresponding LFP signals from the three brain regions were recorded. The task focuses on analyzing the changes in these signals during the exposure to different stimuli.

## Key Concepts
- **Local Field Potential (LFP)**: LFP signals are used to study local neural network activity. These signals capture the summed activity of neurons near the recording electrode.
- **Frequency Domain Analysis**: To understand the spectral content of LFP signals, frequency analysis (such as **Fast Fourier Transform (FFT)**) is employed. This helps in identifying dominant frequencies in the neural signals.
- **Odorant Response**: The analysis focuses on how different brain regions react to olfactory stimuli and whether the response differs between the two odorants.

## Project Tasks
This assignment consists of several key steps in signal processing and analysis:
  
### 1. Signal Preprocessing
- Load and preprocess the raw LFP data from the three brain regions.
- Perform data cleaning, including filtering out noise and handling missing data points.

### 2. Visualization of LFP Signals
- Plot the LFP signals for each brain region to observe how the signals evolve over time.
- Compare the behavior of each brain region when exposed to different odorants.

### 3. Frequency Analysis (FFT)
- Perform **Fast Fourier Transform (FFT)** to transform the LFP signals from the time domain to the frequency domain.
- Identify the dominant frequencies in the LFP signals across the three brain regions.
  
### 4. Odorant Response Comparison
- Compare the LFP responses of the hippocampus, olfactory tubercle, and medial prefrontal cortex to different odorants.
- Explore how neural oscillations in these regions correspond to the presentation of the olfactory stimuli.

## Requirements
To run the notebook and analyze the LFP signals, you will need the following Python libraries:
- **NumPy**: For numerical operations.
- **Matplotlib**: For plotting the LFP signals.
- **SciPy**: For signal processing (FFT and filtering).
- **Pandas**: For data manipulation.

## Notebook Sections
- **Introduction**: Provides background on LFP signals and the experimental setup.
- **Preprocessing**: Loading and cleaning the LFP data.
- **Visualization**: Plotting LFP signals for each brain region.
- **Frequency Analysis**: Performing FFT on the LFP data and analyzing the frequency content.
- **Odorant Response**: Comparing the brain regions' responses to different olfactory stimuli.
  
## Results
The analysis reveals how different brain regions, such as the hippocampus, olfactory tubercle, and medial prefrontal cortex, respond to olfactory stimuli in distinct ways. By examining the frequency domain, we can also observe differences in oscillatory activity between the two presented odorants.

## Learning Objectives
By completing this assignment, students will:

- Understand how LFP signals are recorded and processed.
- Perform basic and advanced signal processing techniques, such as FFT, to analyze neural data.
- Gain insights into how different brain regions respond to sensory stimuli (odorants) and the neural dynamics underlying olfactory processing.
