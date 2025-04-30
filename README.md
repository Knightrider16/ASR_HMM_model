# ASR-HMM Model

## Description
This repository contains an implementation of an **Automatic Speech Recognition (ASR) system** based on **Hidden Markov Models (HMMs)**. The system is designed to transcribe spoken digits (e.g., "zero", "one", "two", etc.) from audio files.

The model uses **MFCC** (Mel-Frequency Cepstral Coefficients) features extracted from the input audio files and applies **HMM** for decoding the speech into text.

### Key Features:
- **Speech-to-Text**: Converts spoken digits into text using HMM-based ASR.
- **MFCC Features**: Uses MFCC for feature extraction.
- **HMM Decoding**: Hidden Markov Model for sequence prediction.

## Acknowledgments
- **Free Spoken Digit Dataset (FSDD)** by **Zohar Jackson**: This dataset is used for training and testing the ASR model. It contains recorded spoken digits (0-9) from various speakers. You can access the dataset [here](https://github.com/Jakobovski/free-spoken-digit-dataset).
  - This dataset is licensed under the **MIT License**.
- **HMMlearn**: The library used for Hidden Markov Model implementation.

## Installation

To set up this project, follow these steps:

### 1. Clone the Repository
Clone this repository to your local machine using Git:

```bash
git clone https://github.com/Knightrider16/ASR_HMM_model.git
