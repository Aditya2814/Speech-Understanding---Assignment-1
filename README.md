## Overview
This project involves analyzing urban sound recordings using different **windowing techniques** for spectrogram generation and classification. The study includes:
- **Short-Time Fourier Transform (STFT)** with Hann, Hamming, and Rectangular windows.
- **Feature extraction using Log-Mel Spectrograms**.
- **Comparison of spectrograms across different audio genres**.
- **Training a classifier to evaluate performance differences**.

## Project Structure
```
├── classical.00000                  # Classical Audio
├── disco.00000                   # Disco Audio
├── jazz.00000                   # Jazz Audio
├── rock.00000                   # Rock Audio
├── report.pdf              # Detailed analysis report
├── analysis.ipynb          # Jupyter notebook with implementation
├── README.md               # Project documentation
```

## Installation
To run this project, install the necessary dependencies:
```sh
pip install librosa numpy scipy scikit-learn matplotlib yt-dlp
```

## IPYNB file contains the following sections:
### 1. Preprocess Audio Data
- Convert MP3 files to WAV format (if needed).
- Extract Log-Mel Spectrogram features using STFT with different window functions.

### 2. Generate Spectrograms
- Apply **Hann, Hamming, and Rectangular windows**.
- Compute **STFT and Mel spectrograms**.
- Visualize and compare spectrograms.

### 3. Analyze Results
- Compare **classification accuracy**.
- Study spectrogram differences among audio genres.

## Notes
- The **Hann and Hamming** windows performed better due to reduced spectral leakage.
- The **Rectangular window** introduced artifacts, leading to lower classification accuracy.

## Author
This project was developed for an academic assignment on **Urban Sound Classification**. Feedback is welcome!

